# urls

A dumb and configurable tool to open frequently-visited browser tabs.

## usage

```
$ urls reddit
$ urls github requests
```

## install

```
$ git clone https://github.com/ryantuck/urls.git ~/src/urls
$ ln -s ~/src/urls/urls /usr/local/bin/urls
```

## configure

Create a file at `~/.urls_config.yml` like so:

```yml
github:
  base_url: https://github.com
  opts:
    requests: /requests/requests
    urls: /ryantuck/urls
reddit:
  base_url: https://reddit.com
  opts:
    np: /r/neutralpolitics
    til: /r/todayilearned
```
