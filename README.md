# Common commands

Setting proxy
* `git config --global http.proxy http://proxyuser:proxypwd@proxy.server.com:8080`
* `git config --global https.proxy https://proxyuser:proxypwd@proxy.server.com:8080`

Unsetting the proxy
* `git config --global --unset http.proxy`
* `git config --global --unset https.proxy`

Existing repo
* `git clone /path/`
* `git clone username@host:/path/`

Commiting changes locally
* `git add <file>`
* `git add *`
* `git commit -m "Commit message"`

Pushing commits to remote
* `git push origin master`
* `git push origin <branch>`

Remote is not set
* `git remote add origin <server>`

Branches
* `git checkout -b <branch name>`
* `git checkout master`
* `git branch -d <branch name>`
