Webp "new" image format from 2010 by Google, but not so easy with compability

jpg 87kb --> 11kb webp

```
npm i
node app.js

```


## How to use images

<picture>
      <source type="image/webp" srcset="image.webp">
      <source type="image/jpeg" srcset="image.jpg">
      <img src="image.jpg" alt="My Image">
</picture>
