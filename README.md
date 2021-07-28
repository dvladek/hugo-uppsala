# Uppsala Theme for Hugo

This is an beta version of an academic theme for Hugo.


## About

This theme has been inspited by the [Hugo Finisterre](https://github.com/jonathan-g/hugo-finisterre) theme by [Jonathan Gilligan](https://www.jonathangilligan.org) and some other academics' personal pages I have visited in the past.

The **hugo-Uppsala** theme supports most of the features from Hugo Finisterre, such as the automatic generation of publication lists from BibTeX files and the dynamic generation of news in the homepage.

In contrast, this is a more lightweight theme redesigned from scratch using [Bootstrap 5](https://getbootstrap.com), [Bootstrap Icons](https://icons.getbootstrap.com) and [SASS](https://sass-lang.com). 


## Installation

1. Install [build prerequisites](#dependencies) on your system.
2. Add the theme repository. To do that, navigate to your themes folder in your Hugo site and use the following commands.
   ```
    mkdir themes
    cd themes
    git clone git@github.com:dvladek/hugo-uppsala.git
    ```
3. Download and install the SASS dependencies. To do that, navigate to the sass project folder and initialize the node.js project with npm.
    ```
    cd assets/style-sass
    npm install
    ```
4. Generate the CSS files in the static directory with `sass main.scss ../../../static/css/main.css`
5. Register hugo-Uppsala as the theme in your Hugo site configuration file.


## Dependencies

Before installing this theme make sure you have installed [Node.js](https://nodejs.org/en/) and [SASS](https://sass-lang.com) in your computer.


## Final note

This theme is fully functional, but I still consider it in beta. I am planning to add new features to the theme as I need them, but for sure my next step will be to extend the research pages to add support for *research areas*, *projects* and *grants*.

It has not been documented yet, but if you want to see the theme in action, you can check [my academic website](https://davidevega.eu).