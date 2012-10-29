Single Post View
==============

This is taken directly from Diaspora's existing source code. The feature itself is being taken out, but it's a nifty way to present content, so I figured I'd scoop it up and put it in a GitHub repo before it gets lost to the ages.

The Single Post View is an immersive way to display content, and was used to display full-page user posts. The viewer is written mostly in Backbone.js, and this repo has a couple of related models thrown in to demonstrate the existing implementation. Please take note, this probably will take some refactoring to make it useful beyond just being a Diaspora post viewer. There are a few files in here that may actually be unnecessary, however everything you need to get it working should be in here. As Diaspora is a Rails app, the pieces for constructing the Single Post View retain the same file locations as they were in Diaspora.

If you'd like to make improvements to make this more universally available to different apps, please submit a pull request!

Authors: This software was created by Maxwell Salzberg and Daniel Grippi, and is licensed under the AGPL v 3.0.
