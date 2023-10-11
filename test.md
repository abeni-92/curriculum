# Experimenting the work flow to contribute to open source for The Odin 
# Project curriculum 

## steps :-

### 1. fork the github repo to contribute
### 2. clone the forked repo
### 3. create a feature branch and add the feature you want
### 4. add the main branch from the repo we want to contribute
	git remote add upstream 'github repo'
### 5. make our main branch to be up to date
	git fetch upstream	
	git checkout main
	git merge upstream/main
    or in one liner: git pull upstream main
### 6. merge our main branch to the feature-branch first to resolve conlflicts 
before merging to the main
	git checkout feature-branch
	git merge main

### 7. then push our branch to our forked github repo
	git push origin feature-branch
		

