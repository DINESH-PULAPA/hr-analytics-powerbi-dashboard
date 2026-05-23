# Push to GitHub

From the project root (`d:\HR_DashBoard_BI`), run:

```powershell
# initialize repo (if not already initialized)
git init
git add .
git commit -m "chore: initial project scaffold"

# create remote repo via GitHub web UI or CLI (example using gh CLI):
# gh repo create <your-username>/<repo-name> --public --source=. --remote=origin --push

# or add remote manually (after creating repo on github.com):
# git remote add origin https://github.com/<your-username>/<repo-name>.git
# git branch -M main
# git push -u origin main
```

If you want me to run the local git init and commit here, say so — I cannot create the remote repo for you, but I can show exact commands.
