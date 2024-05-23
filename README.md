# Books
## finished
### https://exploringjs.com/impatient-js/toc.html
### https://github.com/getify/Functional-Light-JS/tree/master/manuscript

# Tech
- https://bundlephobia.com/ (find the cost of adding a npm package to your bundle)
- https://d3js.org/ (data visualization)
- https://github.com/streamich/react-use (useful hooks)
- react-virtualized and react-window (lazy load)
- React Query (data fetching)
- SWR (data fetching)
- Tailwind CSS (css framework)
- Web push (push notifications) https://www.youtube.com/watch?v=HlYFW2zaYQM
- Prometheus (monitoring)
- GraphQL (query for api)
- NX (monorepo maintenance) https://nx.dev/
- Prerender (web site index and crawling) https://prerender.io/

# Links for reading/solving
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
### https://ydkjs-exercises.com/
## not finished
### https://edabit.com/challenges
### https://leetcode.com/problemset/all/?difficulty=Easy
### https://www.w3resource.com/javascript-exercises/

# Useful links
### https://github.com/reduxjs/cra-template-redux
### https://github.com/hypetechdev
### https://www.matthewgerstman.com/tech/performance-testing-anonymous-functions/
### https://medium.com/@jan.hesters/usecallback-vs-usememo-c23ad1dc60
### https://www.youtube.com/watch?v=9UL0mmkK2qM (Goxi jenkins)
### https://www.youtube.com/watch?v=oOvURgHcd4w&list=PLUDwpEzHYYLseflPNg0bUKfLmAbO2JnE9&index=1 (Manual testing full course)

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

## git chery pick commit from another branch
``` bash
 git cherry-pick -x ngr23fgasdgsdg4342...
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
ssh-add ~/.ssh/id_rsa

- copy content of public key
- add new key in git

## remove all branch except develop
```git
git branch | grep -v "develop" | xargs git branch -D 
```

## install nvm macOs

```bash
	⁃	terminal:
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.35.0/install.sh | bash

	⁃	add to .bash_profile:
export NVM_DIR=~/.nvm
source ~/.nvm/nvm.sh

	⁃	terminal
Source .bash_profile

	⁃	terminal
nvm install 10.14.2

	⁃	terminal
nvm alias default 10.14.2
```

## VSC navigating through aliases

create file:
self-service-cvui/jsconfig.json
With this content:

```js
{
  "compilerOptions": {
    "baseUrl": ".",
    "paths": {
      "@locales/*": ["./src/locales/*"],
      "@messages/*": ["./src/locales/messages/*"],
      "@config/*": ["./src/config/*"],
      "@data/*": ["./src/data/*"],
      "@shared/*": ["./src/shared/*"],
      "@services/*": ["./src/services/*"],
      "@redux_setup/*": ["./src/redux_setup/*"],
      "@CONSTANTS/*": ["./src/constants/*"],
      "@modules/*": ["./src/modules/*"],
      "@test-utils/*": ["./test-utils/*"],
    }
  }
}
```

# Mandatory concepts:

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

# Future Presentations:
1. Best Practise React Dialogs
1. React Portals
1. Intersection observer, windowing
