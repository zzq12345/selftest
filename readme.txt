echo "# selftest" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/zzq12345/selftest.git
git push -u origin main
