Rally Utilization Chart
============

![Title](https://raw.github.com/RallyApps/UtilizationChart/master/screenshots/title-screenshot.png)

## Overview

The Utilization Chart app shows the task estimate total for the iteration divided by the sum of the capacity estimate for all team members with a capacity estimate.

It displays trends over the latest 15 iterations (including the estimate for the current iteration in progress).

## How to Use

### Running the App

If you want to start using the app immediately, create an Custom HTML app on your Rally dashboard. Then copy App.html from the deploy folder into the HTML text area. That's it, it should be ready to use. See [this](http://www.rallydev.com/help/use_apps#create) help link if you don't know how to create a dashboard page for Custom HTML apps.

Or you can just click [here](https://raw.github.com/RallyApps/UtilizationChart/master/deploy/App.html) to find the file and copy it into the custom HTML app.

## Customize this App

You're free to customize this app to your liking (see the License section for details). If you need to add any new Javascript or CSS files, make sure to update config.json so it will be included the next time you build the app.

This app uses the Rally SDK 1.32. The documentation can be found [here](http://developer.rallydev.com/help/app-sdk). 

Available Rakefile tasks are:

    rake build                      # Build a deployable app which includes all JavaScript and CSS resources inline
    rake clean                      # Clean all generated output
    rake debug                      # Build a debug version of the app, useful for local development
    rake deploy                     # Deploy an app to a Rally server
    rake deploy:debug               # Deploy a debug app to a Rally server
    rake deploy:info                # Display deploy information
    rake jslint                     # Run jslint on all JavaScript files used by this app, can be enabled by setting ENABLE_JSLINT=true.

## License

UtilizationChart is released under the MIT license.  See the file [LICENSE](https://raw.github.com/RallyApps/UtilizationChart/master/LICENSE) for the full text.