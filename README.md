# How to start Angular repo with GitHub

1. Create GitHub repo
2. Create Angular app - `ng new my-app`
3. Navigate to you new app folder with the console
4. `git remote add origin <REPO_URL>` - <abbr title="You can find your repo url inside github repository inside the "clone or download" button">?</abbr>
5. `git remote -v` - You can check if it worker, you should see your repo url for the fetch and push
6. `git pull origin master --allow-unrelated-histories`
7. `git push --set-upstream origin master`

Happy Coding!
