# the miau cave <3 VSCode theme

## A flower shop cave inspired theme made using agenomicsphd's tutorial

I wanted to create a vscode theme to give people a little taste of what the miau cave feels and looks like (miau = meow). it's dark because it's a cave, but colorful because of the flowers <3

### instructions 
1. open a terminal and run this commands to install yo code

2. use the arrow keys to select the following options and enter your text when it applies: 'New color theme', 'No start fresh', name your theme, choose an identifier (you can leave it as is), write a description, chose a theme name to show the user, select a base theme 'dark' or 'light', initialize a git repository: 'yes'

3. navigate to your theme

4. on the themes folder open the file with 'your_theme_name-color-theme.json'

5. pick some color palettes you like from coolors (try to pick ones with high contrast i used the accessibility tool in adobe color )

6. search for vs-code-theme-color-generator by coder coder and put your colors in the spaces folowing the labels indications.

7. click the 'GIMME MY THEME' button to get the json file code with your colors, copy the code and paste it into 'your_theme_name-color-theme.json' file

8. to view how the theme looks before publishing it go to run and click start debugging. that will open up a new window where you'll see how your theme looks and anytime you save the changes on the json file it'll update how the theme looks

9. go to the azure devops page, sign up or log in. if you're signing up exit the page once you see the page where you have to enter your address then go to the devops log in page, and log in.

10. go to the user settings and create a personal access token, give it a name, select 'all accessible organizations' on the drop down menu, click on expiration and select custom defined, scroll to the bottom and click on 'show all scopes', find marketplace and select 'manage'

11. click on create, copy the token and save for later.

12. go to http://marketplace.visualstudio.com/manage , click on new extension, enter your publisher name and id (the id will be the name without spaces) and then click on create.

13. go back to vscode, open your package.json file and bellow "version":..., add 

"publisher": "your publisher id",
"repository": {
    "type": "git",
    "url": "your_github_repo_url"
}

14. write your README (yes, do it!)

15. in vscode open a terminal and run 'npm install -g vsce', then 'vsce login your publisher id', then paste your access token

16. then run 'vsce package', then 'vsce publish'

17. now if you go back to the vs marketplace page you'll see an extension with your theme name was created! just wait a couple of minutes for it to get verified and then go to vscode again to search for your theme in the extensions, click install and you are done!!!!!!

### Hope this was somewhat helpful. have fun!!