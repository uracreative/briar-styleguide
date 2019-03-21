# About

Briar is a messaging app designed for activists, journalists, and anyone else who needs a safe, easy and robust way to communicate. Unlike traditional messaging apps, Briar doesn't rely on a central server - messages are synchronized directly between the users' devices. If the internet's down, Briar can sync via Bluetooth or Wi-Fi, keeping the information flowing in a crisis. If the internet's up, Briar can sync via the Tor network, protecting users and their relationships from surveillance.

This guide aims to provide standards, principles and components to design consistent views related to the Briar Project. These pages are a living document and we welcome contributions, feedback and suggestions.


# Getting started

The Briar style guide is based on Bootstrap, an open-source toolkit for developing with HTML, CSS, and JS. We are currently on v4.1.0.

To use the Briar style guide, you can download our scss style (components.scss) and import it in your project with bootstrap included. SASS is a CSS extension language.

If you want to use SASS you can download the complete archive for the style guide. The scss folder under assets contains all the sass files. Since we use bootstrap, we only add a few styles without modifying bootstrap core or defining new elements whenever possible.

Bootstrap contains a few JavaScript libraries for extra interaction with the DOM. We use these libraries but do not add extra JavaScript, so that only few elements are affected if you disable JavaScript.

This styleguide has been built using Jekyll. Jekyll is a simple, blog-aware, static site generator. You can build this yourself by installing Jekyll.

# Building

Need to change to hugo asap

Before you can modify the contents, you need to have Ruby and Jekyll installed.
You can do that by running the following command.

`gem install bundler jekyll`

After you install Jekyll, you need to clone the repo on your system.
You can do that by running the command.

`git clone $REPO`

After you have cloned the repo on your system, start by installing the bundle using the following command.

`bundle install`

Afterwards, execute the following command to build the project and to be able to browse it locally on your browser.

`bundle exec jekyll serve`


That's it! Now you can begin to modify the files and they will be automatically built and displayed on your localhost upon a page refresh.

When you're done with the changes, press Ctrl+C to stop the localhost process.
