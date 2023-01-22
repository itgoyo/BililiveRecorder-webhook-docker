# BililiveRecorder-webhook-docker

Dockerized [BiliveRecorder](https://github.com/BililiveRecorder/BililiveRecorder) with [baidupcs](https://github.com/qjfoidnh/BaiduPCS-Go) upload webhook.

## How to use

- Add a [`.env` file](https://docs.docker.com/compose/environment-variables/#the-env-file) with these variables

  - RECORDER_USER: username for BiliveRecorder
  - RECORDER_PASS: password for BiliveRecorder
  - BAIDUPCS_BDUSS: bduss for baidupcs login. See [baidupcs](https://github.com/qjfoidnh/BaiduPCS-Go#%E7%99%BB%E5%BD%95%E7%99%BE%E5%BA%A6%E5%B8%90%E5%8F%B7) for how to retrieve.
  - BAIDUPCS_STOKEN: stoken for baidupcs login. See [baidupcs](https://github.com/qjfoidnh/BaiduPCS-Go#%E7%99%BB%E5%BD%95%E7%99%BE%E5%BA%A6%E5%B8%90%E5%8F%B7) for how to retrieve.

- Run `docker compose up`