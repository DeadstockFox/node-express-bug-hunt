# Node & Express Bug Hunt!

**READ ALL INSTRUCTIONS BEFORE STARTING**

There are 10 bugs in total, can you find them all? There are hints throughout (???), you should only need to make minor modifcations to 10 lines of code.

**Don't race through the files looking for the issues!** They should all have a console log or error that help you identify them. Read the console so that you know what error will cause each bug. The last one is tricky since it doesn't throw any errors. Document the error, line number and your fix in this README for each of the bugs.

## Setup
```
npm install
npm start
```

> NOTE: A couple of bugs prevent the server from starting.

## Error List

TODO: Add the error here followed by the line of code you fixed.

### Bug 0

`ReferenceError: app is not defined`

Fixed `quote.router.js` line 28: switch `app` to `router`. _This is the solution to the first bug._

### Bug 1


'Router.use() requires a middleware function but got a ' + gettype(fn)

Fixed 'quote.router.js' line line 25: added 'module.exports = router' 


Bug 2

local 404 error, failed to load resource

Solution: Server.Js Line 18: Changed line to app.use(express.static('server/public'));

Bug 3

Local 404 error, AxiosError in status. 

Solution: Client.Js Line 7: Changed url to '/quotes',
          quote.router.js line 8: changed url to '/',


Server is listening on port: 5007, cannot GET/ when loading page.


...

## Extra Practice (Optional)

Complete the JS debugging exercises at:

- https://education.launchcode.org/intro-to-professional-web-dev/chapters/errors-and-debugging/exercises.html
