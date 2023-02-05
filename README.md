# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links))
  - [Built with](#built-with)
  - [Useful resources](#useful-resources)
- [Author](#author)




## Overview

### Screenshot

![](./screenshot.png)



### Links

- Live Site URL: (https://qr-code-component-six-xi.vercel.app/)


### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow
- [React](https://reactjs.org/) - JS library
- [Sass](https://sass-lang.com/) - For styles

## Snippet

```html
<h1>Some HTML code I'm proud of</h1>
```
```css
.card{
    width: 220px;
    background: white;
    padding: 15px;
    text-align: center;
    border-radius: 20px;
    font-size: 15px;
    font-family: 'Outfit', sans-serif;

    img{
        width: 220px;
        border-radius: 10px;
        // margin-bottom: 10px;
    }

    .title{
        font-weight: 700px;
        color: hsl(218, 44%, 22%);
    }

    .info{
        font-size: 11px;
        font-weight: 400;
        color: hsl(220, 15%, 55%);
    }
}
```
```js
import "./qrCode.scss";

const QrCode = () => {
  return (
    <div className="card">
      <img src="assets/images/image-qr-code.png" alt="logo" />
      <h3 className="title">
        Improve your front-end skills by building projects
      </h3>
      <p className="info">
        Scan the QR code to visit Frontend Mentor and take your coding skills to
        the next level
      </p>
    </div>
  );
};

export default QrCode;

```

## Author

- Frontend Mentor - [@ryandav007](https://www.frontendmentor.io/profile/ryandav007)

