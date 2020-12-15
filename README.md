# Marcoolo

Marcoolo is an easy to use and highly configurable color palette which you can integrate in your SCSS projects.  

It's filled with colors I use on a daily base for my freelance clients and personal projects.

The added colors are in rgba format so they are fully adjustable.

## Usage

Install it from npm:

```console
npm install --save-dev marcoolo
```

Use it in your Sass files by calling the function provided with the correct parameters.

```scss
/**
 * @param {string} base-color
 * @param {string} tone
 */

p {
  color: marcoolo(oranges, pumpkin);
}
```
## For your information

The name of this project is a contraction of "Marc" (in honor of my grandfather that passed away in 2017) and "colors". 