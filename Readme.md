# Simple image to url converter

- Author : [Omindu Anjana](https://github.com/omigetapi/)

***

## Installation 
```sh
npm i @ominduanjana/telegram-image-to-url
```

***

## Example
```ts
let { img2url } = require('@ominduanjana/telegram-image-to-url')

const path = './omi.jpg'

img2url(path).then(url => {
    console.log(url); //=> https://telegra.ph/file/a45e08f53773b1a6a16af.jpg
})
```
***
