## Decorate GitHub ReadMe.md ##

https://github.com/tchapi/markdown-cheatsheet/blob/master/README.md

## FrontEnd Helper ##

* Rendering web page in browser https://blog.logrocket.com/how-browser-rendering-works-behind-scenes
* DOM vs Virtual DOM https://www.google.com/amp/s/www.geeksforgeeks.org/reactjs-virtual-dom/amp/
* UI Components - Refer to material-ui  https://mui.com/
* JS ShortHand - https://blog.logrocket.com/16-useful-typescript-javascript-shorthands-know
* Destructuring - https://medium.com/@pyrolistical/destructuring-nested-objects-9dabdd01a3b8
* useAXIOS - https://dev.to/ms_yogii/useaxios-a-simple-custom-hook-for-calling-apis-using-axios-2dkj
    * Set base url -  axios.defaults.baseURL = 'https://jsonplaceholder.typicode.com'.
    * So that we can directly use - .get('/posts') inside axios
* Form Handling - Refer to useFromHook


## Git Command ##

* Push Code on Git on a particular branch 
  * git add . - it adds all the files which we want to push 
  * git commit -m "some message" - commits the code 
  * git push - push the committed code 
  * git pull - take pull of pushed code 
* Fetch all repo ::   git fetch —all
* Create new branch and switched to it ::   git checkout -b (branch name)
* GIT STASH -  If u have already done some changes on a particular branch and u want to switch to some other branches then 
  * git stash ::  stored in stash memory 
  * git checkout -b (branch name) :: now switched to some other branch 
  * git stash pop :: to pop from stash memory 
