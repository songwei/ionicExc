# Ionic Practice Project

## Required Installation
- node.js (8.x.x)
- git
- ionic cli: 
`npm install -g ionic`
- cordova:
`npm install -g cordova`


## Create project
    # blank template; no Ionic Appflow SDK; 
    ionic start ionicExc --type=angular

    # Install @ionic/lab? Yes
    ionic serve -l

## commit 1: Add 'menu-button'、'menu' and 'menu-toggle'.
 
app.component.ts:   
    Add datas of menu items.

home.page.html:   
Add a [menu-button](https://github.com/ionic-team/ionic/blob/master/core/src/components/menu-button/menu-button.tsx), it will be render as [menu-toggle](https://github.com/ionic-team/ionic/blob/master/core/src/components/menu-toggle/menu-toggle.tsx) including button with menu icon. 
    
Other components related to menu:
- [menu-controller](https://github.com/ionic-team/ionic/blob/master/core/src/components/menu-controller/menu-controller.ts) 
- [menu](https://github.com/ionic-team/ionic/blob/master/core/src/components/menu/menu.tsx)

app.component.html:  
    add split pane and a menu including 3 menu items(menu-toggle).
