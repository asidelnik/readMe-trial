
## Git Contribution Instructions
1. **Fork this repo**
2. **Clone your forked repo**
```
git clone https://github.com/<gitHubUserName>/join-dev-design.git
```

3. **Set up a new upsteam remote** (for pulling updates from Microsoft's repo to your local version)
```
git remote add upstream https://github.com/Microsoft/join-dev-design.git
```
4. **Pushing a change**
   - To avoid merge conflicts, pull Microsoft repo updates
```
git pull upstream master
```
    - Check that your changes are working
    - Add, commit & push (to your personal github repo)
```
git push origin master
```
5. **Pull request** (personal repo into Microsoft repo)
   - base fork: Microsoft/join-dev-design ⬅ head fork: userName/join-dev-design
