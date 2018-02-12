```
   ______              __           __
  /\__  _\          __/\ \__       /\ \
  \/_/\ \/     ___ /\_\ \ ,_\      \_\ \
     \ \ \   /' _ `\/\ \ \ \/      /'_` \
      \_\ \__/\ \/\ \ \ \ \ \_  __/\ \L\ \
      /\_____\ \_\ \_\ \_\ \__\/\_\ \___,_\
      \/_____/\/_/\/_/\/_/\/__/\/_/\/__,_ /
```

Batch scripts for Ruby production environment install on Ubuntu Server.

[![wercker status](https://app.wercker.com/status/2dd2ff58518cae2dd75e4556e6d931c5/s/master "wercker status")](https://app.wercker.com/project/bykey/2dd2ff58518cae2dd75e4556e6d931c5)

## Requirements

* Ubuntu Server 14.04

## Usage

Install packages first

```bash
sudo apt-get update
sudo apt-get install -y curl
curl -sSL https://git.io/vAqVI | bash
```

### Install Nginx

Nginx [official package](http://nginx.org/packages/ubuntu/)

```bash
curl -sSL https://git.io/vAqVU | bash
```

### Install RVM + Ruby

```bash
curl -sSL https://git.io/vAqVJ | bash
```

Use Ruby China mirror site for RubyGems and Ruby:

```
MIRROR=1 curl -sSL https://git.io/vAqVJ | bash
```

### Install Redis

```bash
curl -sSL https://git.io/vAqah | bash
```

### Install ElasticSearch

```bash
curl -sSL https://git.io/vAqay | bash
sudo service elasticsearch status
```

## Install Docker

```bash
curl -sSL https://git.io/vAqa7 | bash
sudo docker info
```

## Install Haproxy

```bash
curl -sSL https://git.io/vAqad | bash

```