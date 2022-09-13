# Simple image to url converter
##   👇 👇 👇 

- Author : [Omindu Anjana](https://github.com/OminduBro/)

***

## Installation 
```sh
npm i @omindubro/telegram-image-to-url
```

***

## Example
```ts
let { img2url } = require('@omindubro/telegram-image-to-url')

const path = './omi.jpg'

img2url(path).then(url => {
    console.log(url); //=> https://telegra.ph/file/a45e08f53773b1a6a16af.jpg
})
```
***
