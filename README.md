# detailed-policy

## the brief

Hi Neal,

This is the brief - Ken has been asking for this view for a few weeks and I haven't been able to help him as well as I should have.

I need to make this view ready for the Enterprise.  Unfortunately, it uses some items and has some option that we used for the GE model.

This task is quite simple, but is the sort of thing I end up doing every day or so.

Refer to Vuetify docs for some things:
[Vuetify v1.5.x](https://v15.vuetifyjs.com/en/)

Tasks:

1. Remove the **Regulation** and **Regulatory Supplement** switches.
2. At the top bar, remove the select dropdowns for **Org Function** and **Product Service**
3. Rename the dropdown for **Manual** to **Policy**

Bonus points:

  - Change the colour of the components (Vuetify) to an Orange and Grey theme (the corporate colours...)
  - Create an easy way to change the theme of the components

## Setting it up

I have excluded the customer data deliberately

To get the customer data to appear, you need to put the js file into the same working directory as the git repo.  There is a script tag in the HTML vue file which points to a file named `customer-data.js`.  The file itself just declares a global variables with the JSON data that gets used in the model.

## Recommendations

I have a bunch of tools I use to help myself do these web tasks

### My quick install script for all of these

Install scoop - see below for link

Open PowerShell and run this script:

`scoop install git nodejs vscode`

Then cd to the desired directory and clone the repo

`git clone https://github.com/frosty-fingers/detailed-policy`

Then you can install Vue Devtools on your browser if you want (see below)

### Scoop: Windows Package Manager

This is an underrated library - it lets you install things from the command line.  It's like `sudo apt-get` on Linux or Homebrew for Mac.

It's quite useful if you want to get new packages and stuff like that, for example it makes installing Node a lot easier, and other programming languages.  It also means you don't have to deal with admin privilege popups.

For example:

`scoop install git` will install git

[scoop](https://scoop.sh/)

### Visual Studio Code

I would give this editor a try - it's really popular and has a lot of extensions.  It seems to work well with JS apps and has lots of themes which I like to mess around with.

It also has syntax highlighting for Vue and useful stuff for git.

[Visual Studio Code](https://code.visualstudio.com/)

### Vue Dev Tools

A browser add-on that provides options for debugging VueJS apps.  May not be needed but could be useful for figuring things out.

Click F12 and click the Vue tab to access it

[vue-devtools](https://github.com/vuejs/vue-devtools)

### Other packages: Git and NodeJS

I'm assuming you have probably these installed...
