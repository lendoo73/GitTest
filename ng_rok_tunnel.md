# Ngrok


## [Install ngrok](https://ngrok.com/download)


Run as administrator
```sh
choco install ngrok
```

https://www.twilio.com/docs/usage/tutorials/how-use-ngrok-windows-and-visual-studio-test-webhooks

`ngrok config add-authtoken 2OmRnXM3vul9TgrMtn2wsoZUf8q_3zcW131xLgbvmTAvCj74F`

Authtoken saved to configuration file: C:\Users\ccselko\AppData\Local/ngrok/ngrok.yml

## Open tunnel 

```sh
ngrok http 8181
```

open on `http://localhost:4040`

Configuration command line URL:
`https://f5c9-2a00-23c6-220b-ba01-7c35-a49d-2969-5288.ngrok-free.app`

This URL need to add on GitHub webhook
