```sh
git init
git add .
git commit -m "message"
git remote add origin https://github.com/lendoo73/GitTest.git
git push -u origin main
git config --unset credential.helper
git config --global credential.https://github.com.username lendoo73
```