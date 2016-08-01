# grails-sitemesh-bug
App to demonstrate the sitemesh bug.

The layout looks fine if you run this with `grails run-app`, but if you build and run the WAR file, `main.gsp`
is not rendered in the layout.  

The localhost:8080 throws an exception that it can't find the index view, which is probably related; but if
you navigate to `/slice`, you can see the view is not rendering `main.gsp`.
