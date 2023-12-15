# pandora-next-deploy
在 HuggingFace 等平台上部署 Pandora-Next

点击部署至HuggingFace👉[![Deploy to HuggingFace](https://img.shields.io/badge/%E7%82%B9%E5%87%BB%E9%83%A8%E7%BD%B2-%F0%9F%A4%97-fff)](https://huggingface.co/login?next=%2Fspaces%2Flinzjian666%2FPandoraNext%3Fduplicate%3Dtrue%26visibility%3Dpublic)

## 用到的变量
  |变量名|是否必须|
  |---|---|
  |CONFIG_JSON|是|
  |TOKENS_JSON|否|

### 以下是一个`CONFIG_JSON`的示例
```json
{
  "bind": "0.0.0.0:8181", //如无必要,请勿改动此行
  "tls": {
    "enabled": false,
    "cert_file": "",
    "key_file": ""
  },
  "timeout": 600,
  "proxy_url": "",
  "license_id": "",
  "public_share": false,
  "site_password": "",
  "setup_password": "",
  "server_tokens": true,
  "proxy_api_prefix": "",
  "isolated_conv_title": "*",
  "disable_signup": false,
  "auto_conv_arkose": false,
  "proxy_file_service": false,
  "custom_doh_host": "",
  "captcha": {
    "provider": "",
    "site_key": "",
    "site_secret": "",
    "site_login": false,
    "setup_login": false,
    "oai_username": false,
    "oai_password": false,
    "oai_signup": false
  },
  "whitelist": null
}
```
  * 详细说明[参见此处](https://github.com/pandora-next/deploy/?tab=readme-ov-file#config-%E9%85%8D%E7%BD%AE)

### `TOKENS_JSON` [参见此处](https://github.com/pandora-next/deploy/?tab=readme-ov-file#tokens-%E9%85%8D%E7%BD%AE)
