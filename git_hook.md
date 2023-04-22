```sh
git init
git add .
git commit -m "message"
git remote add origin https://github.com/lendoo73/GitTest.git
git push -u origin main
git config --unset credential.helper
git config --global credential.https://github.com.username lendoo73
```

## Create git webhook

On github repo click on 

Settings -> Webhooks -> Add webhook

Payload URL: `https://f5c9-2a00-23c6-220b-ba01-7c35-a49d-2969-5288.ngrok-free.app/github-webhook/` # from ngrok tunnel
Content type: application/json

[Add webhook]