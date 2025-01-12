<h1 align="center">Welcome to glitch-cdn 😘</h1>
<p>
  <img alt="Version" src="https://img.shields.io/npm/v/glitch-cdn" />
  <img alt="Stars" src="https://img.shields.io/github/stars/rama0dev" />
</p>

> With this module you can publish files automatically on the Glitch.com CDN

> ⚠️Content that you upload to the server will not show up in the "Assets" tab

> ❗ Glitch.com CDN has a limit of 250mb per file

> ❗ Glitch.com may remove your bucket if they notice that you are mainly using the project for cdn and not for hosting applications on their hosting service.

## Install

```sh
npm i glitch-cdn
```

## Usage

```js
var glitchcdn = require("glitch-cdn");

//Structure upload2glitch.upload(authorization, projectId, file, url) 
glitchcdn.upload("1c0612ac-e403-4a0b-95e9-3a75d1f650f9","e3de541d-95d7-4ed6-a3ee-89abefa4211b",`./frog.png`,`img/cutepictures/frog.png`, (returndata)=>{
    console.log(returndata) 
})
```

## How get authorization and projectId:
<p>
  <img alt="Version" src="https://raw.githubusercontent.com/rama0dev/glitch-cdn/main/md/auth.png" />
</p>



## Author

👤 **Rama**

* Website: https://ramaprojects.ru/
* Github: [@rama0dev](https://github.com/rama0dev)

## 🤝 Contributing

Contributions, issues and feature requests are welcome!<br />Feel free to check [issues page](https://github.com/rama0dev/glitch-cdn/issues). 

## Show your support

Give a ⭐️ if this project helped you!
