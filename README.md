# Books
## finished
### https://exploringjs.com/impatient-js/toc.html
### https://github.com/getify/Functional-Light-JS/tree/master/manuscript
## not finished
### https://web.mit.edu/alexmv/6.037/sicp.pdf

# Links
## finished
### https://gist.github.com/alexserver/2fcc26f7e1ebcfc9f6d8
### https://levelup.gitconnected.com/design-patterns-in-modern-javascript-development-ec84d8be06ca
### https://www.robinwieruch.de/react-hooks-fetch-data
### https://levelup.gitconnected.com/state-management-in-react-using-context-api-and-hooks-931c9842f204
### https://egghead.io/lessons/react-redux-the-single-immutable-state-tree
### https://medium.com/backticks-tildes/setting-up-a-redux-project-with-create-react-app-e363ab2329b8
### https://medium.com/netscape/creating-custom-middleware-in-react-redux-961570459ecb
### https://www.freecodecamp.org/news/scaling-your-redux-app-with-ducks-6115955638be/
### https://www.hawatel.com/blog/handle-window-resize-in-react/
### https://medium.com/osedea/git-rebase-powerful-command-507bbac4a234

# Coding Practise Chalenges
## finished
### https://github.com/timoxley/functional-javascript-workshop
## not finished
### https://edabit.com/challenges
### https://leetcode.com/problemset/all/?difficulty=Easy

# Useful links
### https://github.com/reduxjs/cra-template-redux

# Useful code

### aliases for mac
.bash_profile
``` 
sudo touch .bash_profile
sudo nano .bash_profile
```
## git reset

``` bash
git reset --hard HEAD~200
```

## git chery pick last commit
``` bash
 git cherry-pick develop
```

## git recursive cloning

``` bash
git submodule update --init --recursive
```

## specific version of node

https://www.sitepoint.com/quick-tip-multiple-versions-node-nvm/

## specific version of yarn

https://stackoverflow.com/questions/44448084/how-do-i-change-the-version-of-yarn-used

## ssh

ssh-keygen -t rsa -b 4096 -C "end53184@adobe.com"

- copy content of public key
- add new key in git

## mozzila allow not secure connection

- Open a new window in Firefox and type "about:config" without the quotes and hit enter
- Confirm that you want to continue
- In the search field, type in security.enterprise_roots.enabled and hit enter, you'll be left with one field
- If it's marked as "false" then double-clicking it should turn it to "true"
- reset mozzila

## remove all branch except develop
```git
git branch | grep -v "develop" | xargs git branch -D 
```



### Mandatory concepts:

1. hoisting
1. expressions and statements
1. appy, call, bind
1. callback
1. type conversions
1. logical operators
1. switch
1. imidiatelly invoked functions
1. es6
1. arrow functions
1. param default values
1. string interpolation
1. property shorthand
1. desctructuring
1. rest, spread
1. Prototypes
1. Objects
1. Arrays
1. scopes
1. closure
1. var, let, const
1. functions
1. this
1. promises
1. async functions
1. pure function
1. side effect
1. recursion
1. event loop
