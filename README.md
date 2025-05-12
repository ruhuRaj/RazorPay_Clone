
  
 <span align="center"> 
   
<a href="https://www.linkedin.com/in/ncodes/">![alt text](https://img.shields.io/badge/Linkedin-blue?styele=&logo=linkedin)</a><a href="https://github.com/code-ea">![ alt text](https://img.shields.io/badge/Github-black?styele=&logo=github)</a><a href="https://tailwindcss.com/docs/installation">![ alt text](https://img.shields.io/badge/Tailwind-gray?styele=&logo=TailwindCSS)</a>
   
 </span>
  

# Razorpay-Clone

This open-source project aims to replicate the user interface and user experience of the RazorPay website's frontend. RazorPay is a popular payment gateway that provides a smooth payment processing experience for businesses and their customers.

HTML and TailwindCSS are the technologies used in this project.

Tailwind CSS is a utility-first CSS framework that enables users to create applications faster and easier. It provides a wide range of responsive utility classes that can be used to control the layout, color, spacing, typography, shadows, and more to create a completely custom component design without leaving your HTML or writing a single line of custom CSS


## Demo

>**https://code-ea.github.io/Razorpay-Clone/**


## Tech Stack

>**HTML, TailwindCSS**


## Installation

**Step 1:** Install tailwindcss and its peer dependencies via npm, and create your tailwind.config.js file.

>**Terminal**
```bash
▶ npm install -D tailwindcss postcss autoprefixer
▶ npx tailwindcss init
```
**Step 2:** Add tailwindcss and autoprefixer to your postcss.config.js file, or wherever PostCSS is configured in your project.


>**postcss.config.js**

```bash
module.exports = {
  plugins: {
    tailwindcss: {},
    autoprefixer: {},
  }
}
```
**Step 3:** Add the paths to all of your template files in your tailwind.config.js file.

>**tailwind.config.js**

```bash
/** @type {import('tailwindcss').Config} */
module.exports = {
  content: ["./src/**/*.{html,js}"],
  theme: {
    extend: {},
  },
  plugins: [],
}
```
**Step 4:** Add the @tailwind directives for each of Tailwind’s layers to your main CSS file.


>**main.css**

```bash
@tailwind base;
@tailwind components;
@tailwind utilities;
```
**Step 5:** Run your build process with npm run dev or whatever command is configured in your package.json file.


>**Terminal**

```bash
▶ npm run dev
```
**Step 6:** Make sure your compiled CSS is included in the <head> (your framework might handle this for you), then start using Tailwind’s utility classes to style your content.

>**index.html**

```
<!doctype html>
<html>
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link href="/dist/main.css" rel="stylesheet">
</head>
<body>
  <h1 class="text-3xl font-bold underline">
    Hello world!
  </h1>
</body>
</html>
```


## Documentation

><a href="https://tailwindcss.com/docs/installation">**Getting started with Tailwind**</a>

><a href="https://razorpay.com/">**Razorpay Official**</a>





## Support

>For support, email **nitinkrsingh88@gmail.com**.
