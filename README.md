# Material Child Theme
This is a material inspired child theme created for Divi.

-


## General Settings

#### Layout Settings
- Theme Accent Color: #02A8F3

#### Typography
- Body Text Size: 14px
- Line Height: 1.250em
- Header Font: Roboto
- Body Font: Roboto
- Body Text Color: #717171
- Header Text Color: #202020

#### Background
- Background Color: #F2F2F2

-

## Header & Navigation

#### Primary Menu Bar
- [x] Make Full Width
- Menu Height: 48px
- Logo Max Height: 48px
- Text Size: 14px
- Text Color: #FFFFFF
- Active Link Color: #FFFFFF
- Background Color: #2095F2
- Dropdown Menu Background Color: #FFFFFF
- Dropdown Menu Line Color: rgba(255,255,255,0)
- Dropdown Menu Text Color: #717171

#### Secondary Menu Bar
- [x] Make Full Width
- Text Size: 14px
- Background Color: #1875D1

#### Fixed Navigation Settings
- Fixed Menu Height: 48px

#### Header Elements
- [x] Show Social Icons
- [x] Show Search Icon

## Buttons

#### Buttons Style
- Text Size: 14px
- Text Color: rgba(255,255,255,0.99) // Fixes Text Color Glitch
- Background Color: #02A8F3
- Border Width: 0
- Border Radius: 3
- Add Button Icon: No

#### Buttons Hover Style
- Background Color: #02A8F3


## Footer


#### Layout
- Footer Background Color: #2095F2

#### Widgets
- Widget Header Color: #FFFFFF
- Widget Bullet Color: #FFFFFF

#### Footer Menu
- Footer Menu Background Color: #2095F2
- Footer Menu Text Color: #FFFFFF

#### Bottom Bar
- Background Color: #1875D1
- Text Color: #FFFFFF
- Social Icon Size: 14px
- Social Icon Color: #FFFFFF

# Divi Child Theme Template
This is a premade template for creating a Divi Child Theme. This repo comes preinstalled with 3 different paths...
- [CSS](#css-path)
- [Preprocessor](#preprocessor-path)

## CSS Path
If you don't have any experience working with preprocessors, this is the best path for you.

#### Step 1: Cloning the Repo
The first step to getting start with building a child theme is cloning this repo. If you don't have [Git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git) installed, you can download the [ZIP file](https://github.com/elegantthemes/divi-child-theme-init/archive/master.zip) and drop it into your `wp-content/themes` folder.

1. Let's start by navigating to your `wp-content/themes` folder instead your WordPress directory.
2. Once you're there, open `terminal` in the current folder.
3. Now with `terminal`, use the following commands to clone: `git clone git@github.com:elegantthemes/divi-child-theme-init.git`

#### Step 2: Development
Now that you have the repo cloned or installed, you can start development.

1. If you haven't already, navigate to your `divi-child-theme-init folder`.
2. Open up `style.css` in your favorite editor and code away!


## Preprocessor Path
If you want to speed up your development, you can choose one of the following preprocessors installed.

#### Requirements
Below are a list of applications/software that you will need preinstalled before continuing down this path.
- [Git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)
- [Node.js](http://nodejs.org/)
- [GruntJS](http://gruntjs.com/) - _A JavaScript Task Runner_
- [Sass](http://sass-lang.com/install) - _If you're using Sass/Scss_


#### Step 1: Installing Node.js
The first step is getting NodeJS installed. If you already have it installed go ahead and skip to step [#2](#step-2-installing-gruntjs).

1. Head over to `https://nodejs.org/en/` and install the latest version of Node.js
2. Now that it's installed, run `node -v` to verify that you have the latest version installed.
3. Head over to step [#2](#step-2-installing-gruntjs).


#### Step 2: Installing GruntJS
The next step is setting up GruntJS locally. If you already have it installed go ahead and skip to step [#3](#step-3-installing-git).

1. Now that you have Node installed, let's install GruntJS by running the following command: `npm install -g grunt-cli`.
2. Head over to step [#3](#step-3-installing-git).

-

#### Step 3: Installing Git
After installing Node and Grunt, you can now install Git. If you already have it installed go ahead and skip to step [#4](#step-4-cloning-repo).

1. Go to `https://git-scm.com/book/en/v2/Getting-Started-Installing-Git` and follow the to installing git for the correct machine.
2. Head over to step [#4](#step-4-cloning-repo).

-

#### Step 4: Cloning Repo
1. With git now installed, navigate to `wp-content/themes` folder.
2. Clone the repo using the following command: `git clone git@github.com:elegantthemes/divi-child-theme-init.git`.
3. Now with the repo cloned, you can navigate to it by typing in `cd ` and dragging the divi child theme folder into your terminal.
3. Head over to step [#5](#step-5-installing-packages).

-

#### Step 5: Installing Packages
1. From current directory, install node packages with the following command: `npm install`.
2. Head over to step [#6](#step-6-running-grunt).

-

#### Step 6: Running Grunt
1. From the current directory, run the following command: `grunt`.
2. Once grunt has been initiated, you can start your development.

## Copyright & License
Copyright 2015 ElegantThemes. Code released under the [GNU license](https://github.com/elegantthemes/divi-child-theme-init/blob/master/LICENSE).
