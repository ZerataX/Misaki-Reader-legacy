**This is an online manga reader build with [Node.Js][Nodejs], [Express][Express] and [MongoDB][MongoDB]**


~~this is very much a work in progress by an novice, 
but it's a fun project and I hope it'll become somewhat useful to you.~~

I hope to find time to redo this project with some fun frameworks or something.

### Setting up
Just install the npm package or any equivalent on your system then, using
your newly installed npm install the express framework:
```
npm install express --save
```

Then do the usuals

```
npm install
npm start
```


### Tweaks
if you want to use the login by persona, you have to change

```javascript
const PORT = 8080;
const AUDIENCE = "http://localhost:" + PORT;
```

to your domain


Powered by ❤ with [Bootstrap][Bootstrap]

[Express]: https://github.com/strongloop/express
[Nodejs]: https://github.com/nodejs/node
[MongoDB]: https://github.com/mongodb/node-mongodb-native
[Bootstrap]: https://github.com/twbs/bootstrap
