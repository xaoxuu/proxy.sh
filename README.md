# proxy.sh

export http_proxy config

```
export http_proxy="http://127.0.0.1:$P1"
export HTTP_PROXY="http://127.0.0.1:$P1"
export https_proxy="http://127.0.0.1:$P1"
export HTTPS_PROXY="http://127.0.0.1:$P1"
```

## Install

```
curl -s https://xaoxuu.com/install | sh -s proxy.sh
```

## Usage

```
proxy 58884
```

equal to:

```
export http_proxy="http://127.0.0.1:58884"
export HTTP_PROXY="http://127.0.0.1:58884"
export https_proxy="http://127.0.0.1:58884"
export HTTPS_PROXY="http://127.0.0.1:58884"
```
