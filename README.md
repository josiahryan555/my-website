# My Personal Website

This is my personal website (still under development).
It is adapted from my [final project](https://github.com/jryanb0b/personal-website) in CS336 Web Development in 2022 at Calvin University by Clare Schellenberg, Germaine Hounakey, and Josiah Ryan.

This project was generated with [Angular CLI](https://github.com/angular/angular-cli).

## To Run

1. Clone this repository to your computer
2. Open your terminal or powershell at the '/my-website' folder.
3. Enter: `npm install`.  This will download all the necissary node package modules to support this code. (If it suggests entering `npm audit fix` do so.)
4. Enter: `ng serve`. This will host this wepage on a port of your computer so you can see it in your browser.  Navigate to [`http://localhost:4200/`](http://localhost:4200/) in your web browser. The application will automatically reload if you change any of the source files.
5. You should be able to see and interact with the app at that link.

## To Deploy
[Instructions](https://angular.io/guide/deployment)
Note: right now the webpage is in a branched named `gh-pages`.  This is where the /docs folder is that is deployed.  This process must be done in that branch, and it will be deployed there.  Maybe I should just merge the branchs.  But for now, this process must be done in the `gh-pages` branch
1. In a console, navigate to the project root and enter this line of code: `ng build --output-path docs --base-href /my-website/`.  This builds the website.
2. Push and publish the branch
3. Check and see if it works!  You may need to navigate to `settings/pages` in github/my-website to update the deployed site.  It also may take several minutes to work ¯\_ (ツ)_/¯