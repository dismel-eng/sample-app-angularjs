## Contents
 
### The main app module bootstrap
- *app.module*.js: Loads the top-level states, and does some configuration

### Top-level states
- *app.state*.js: The root application
- *app.component*.js: A template/controller which displays the header nav-bar for authenticated in users

- *home.state*.js: The home state for authenticated users
- *home.component*.js: A template/controller that has links to the main submodules

- *login.state*.js: The login state
- *login.component*.js: A template/controller for authenticating a guest user

- *welcome.state*.js: The welcome state
- *welcome.component*.js: A template/controller which displays a welcome screen for guest users

### Directories
- *bootstrap*: This code assembles the different ES6 modules and starts it running.
- *contacts*: The Contacts submodule
- *mymessages*: The My Messages submodule
- *prefs*: The Preferences submodule
- *routerhooks*: Global ui-router hooks
- *services*: Global services
- *util*: : Utility functions