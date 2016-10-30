# Palette

Theming platform for WordPress, which includes tools to make themes easier for developers, theme shops, and users.  This platform seeks to move pain points and manual processes into software.  Let's build a software solution that handles common issues with themes.

## Features

This platform will include the following features:

1. Theme Switcher Memory
2. Theme Customization and Pushing Updates

### Theme Switching Memory

A user switches to a different theme.  Right now, if the previous theme had different widgetized sidebar areas, inpost metaboxes, and other features, those are lost.  The content remains in the database.  However, to the user, the impression is the content is gone.  Let's solve that problem.

The idea is to remember and present the opportunity for the user to relocate content into the new structure.  For example, let's present a "memory" area for the widgetized areas.  Let the user then drag these into the new theme's locations.

### Theme Customization and Pushing Updates

The prevalent customization model is for developers and users to edit the theme directly.  Hum, but what happens when the themer or theme shop needs to make an update to the theme?  Ah, the developer or user must know what changed in what file and then manually merge these changes together.  That's the wrong strategy.  It's problematic and leads to themes not being updated or support tickets to the theme shop and frustrated users.

Let's solve that problem.  Let's programmatically merge updates and theme customizations together.  Let's retain the customizations and give themers/theme shops the ability to push updates.  We can solve this problem through software and make it utterly easy and reliable for users without ever touching the code.

## On GitLab

This platform and community is on [GitLab](https://gitlab.com/uptechlabs/Palette).  Want to contribute? Awesome, we welcome your input. Come join us. 
