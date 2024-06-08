# CrispCSS
Welcome to Crisp CSS, a modern, lightweight, and highly customizable CSS framework designed to streamline your web development process. Crisp CSS offers a set of design tools that empower developers and designers to create visually stunning, responsive, and accessible web applications with ease.

## Installation

The installation process is very simple and straight forward. Below are the steps:

### Step 1: Clone CrispCSS Framework Repository

Navigate to the root directory of your working project and clone CrsipCSS framework repository:

```bash
cd /path/to/your_project

git clone https://github.com/luxshie/CrispCSS.git path/to/CrispCSS-directory
```

### Step 2: Include CrispCSS Framework in Your HTML

Edit your HTML files to include the CSS file from the cloned repository. Add the following line within the <head> section of your HTML file:

```html

<link rel="stylesheet" href="path/to/CrispCSS-directory/style.css">
```

## Usage

Once the CripsCSS framework is included in your project, you can start using its classes in your HTML elements. Here are some examples:

```html
<button class="btn-basic">Click Here</button>
<a href="#" class="primary-link"> This is a link button> </a>
```

## Customaiztion

Once the CripsCSS framework is included you can override the default styles provided by the CSS framework by adding your own CSS rules after the framework's CSS file. 

Example for overriding the primary and sceondary color:

```html
$primary-color: red;
$secondary-color: white;
```

compile the scss file and you would be able to use the new primary colors