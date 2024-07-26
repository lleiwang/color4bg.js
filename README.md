![color4bg.js](https://color4bg.com/static/images/github/01-logo.jpg)



# color4bg.js [![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/)
Super easily generate dynamic, abstract, and visually stunning background images for your web pages based on WebGL and JavaScript. High performance.


## Demo
Please visit: [color4bg.com](https://www.color4bg.com)

![color4bg.js](https://color4bg.com/static/images/meta-og-image.jpg)


## 🚀 Features
- Customizable Colors: You can specify an array of up to 6 colors that will be used to generate the background pattern.
- Dynamic Animation: The generated background can be set to loop, creating a mesmerizing, fluid animation.
- Consistent Patterns: By providing a seed value, you can ensure that the same pattern is generated every time, making it easy to integrate into your web design.
- Easy Integration: Simply import the **Bg class and create an instance with your desired settings.


## 📦 Usage
To use color4bg.js, follow these steps:

> For example, if you want to add Aesthetic Fluid Bg:

1. Import the AestheticFluidBg module js file:
```javascript
import { AestheticFluidBg } from "../build/jsm/AestheticFluidBg.module.js"
```

2. Create an instance of AestheticFluidBg with your customized settings:
```javascript
let colorbg = new AestheticFluidBg({
    dom: "box",
    colors: ["#D1ADFF", "#98D69B", "#FAE390", "#FFACD8", "#7DD5FF", "#D1ADFF"],
    seed: 1000,
    loop: true
})
```

| Key | Value     | Describe                       |
| :-------- | :------- | :-------------------------------- |
| `dom`      | `string` | Id of DOM element where to append colorbg, no need to add "#" |
| `colors`      | `Array` | An array of up to 6 hexadecimal color values |
| `seed`      | `Number` | A Pseudo-random numerical value used to generate a  consistent pattern. |
| `loop`      | `Bool` | Determines whether the background should animated looply or not |



#### For more usage, see examples


## All Background(Bg) Types
![all bg](https://github.com/user-attachments/assets/6e4faace-6baa-42f1-8e0e-e969a277412f)





## License
This project is licensed under the MIT License.
