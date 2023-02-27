# Basic Node and Express

This is the boilerplate code for the Basic Node and Express Challenges. Instructions for working on these challenges start at https://www.freecodecamp.org/learn/apis-and-microservices/basic-node-and-express/

---

Submit ``` http://localhost:3000 ``` as the url for completing challenges locally.
- Live app can be viewed locally in a browser using the same url.

Open Terminal and use ```$ npm start ``` to run before submission.

[VSCode Node.js tutorial page](https://code.visualstudio.com/docs/nodejs/nodejs-tutorial)

---

```
app.use("/public",express.static(__dirname + '/public'));

```
- get and use static assests like css file.

```
app.get("/", (req, res) => {
  res.sendFile(absolutePath);
});
```
- serves html file upon request (in example ```http://localhost:3000 ```)

- ```__dirname``` rerturns root directory. (best practice for node according to course.)
