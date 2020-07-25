# Minimal Mock Server

## Requirements

- Ruby 2.7+

## Install

```
$ git clone {This repository}
```

## Usage

Start server:

```
$ ./mock
```

Throw requests:

```
$ curl -i 'localhost:8181/users'
$ curl -i 'localhost:8181/users?id=1'
```

Edit config:

```
$ vi mock-config.json
```

The config file is reloaded every time, so you don't need to restart the server.

## LICENSE

MIT License.
