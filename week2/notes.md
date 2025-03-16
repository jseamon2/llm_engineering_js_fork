### Pull updates to forked repository
* Add remote repository upstream
```
git remote add upstream <github link>
```
* Fetch changes
```
git fetch upstream
```
* Checkout main branch and merge
```
git checkout main
git merge upstream/main
```
* Push the changes
```
git push origin main
```
or
```
git pull upstream main
```