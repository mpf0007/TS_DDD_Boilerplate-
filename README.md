## Table of Contents

`
MongoDb has no official build for ubuntu 22.04 at the moment.
Ubuntu 22.04 has upgraded libssl to 3 and does not propose libssl1.1
You can force the installation of libssl1.1 by adding the ubuntu 20.04 source:
`


> $ echo "deb http://security.ubuntu.com/ubuntu focal-security main" | sudo tee
> /etc/apt/sources.list.d/focal-security.list

> $ sudo apt-get update

> $ sudo apt-get install libssl1.1
> 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