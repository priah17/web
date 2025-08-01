git add .
git commit -m "Testing Jenkins Poll SCM"
git push
git commit --amend -m "webhook"
git push alias main --force
