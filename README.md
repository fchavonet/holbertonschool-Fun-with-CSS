<img  height="50px" align="right" src="https://raw.githubusercontent.com/fchavonet/fchavonet/main/resources/images/logo-holberton_school.png" alt="Holberton School logo">

# Fun with CSS

<details>
        <summary>
        CLICK TO ENLARGE 😇
        </summary>
        📄 <a href="#description">Description</a>
        <br>
        🎓 <a href="#objectives">Objectives</a>
        <br>
        📋 <a href="#requirements">Requirements</a>
        <br>
        📝 <a href="#instructions">Instructions</a>
        <br>
        🔨 <a href="#tech-stack">Tech stack</a>
        <br>
        📂 <a href="#files-description">Files description</a>
        <br>
        ♥️ <a href="#thanks">Thanks</a>
        <br>
        👷 <a href="#authors">Authors</a>
</details>

## 📄 <span id="description">Description</span>

In this project, I explore creative web design using only HTML and CSS. My goal is to enhance static pages with dynamic layouts and animations, all without JavaScript.

You can test the results of my work through the following links:

- [0. Sprite languages](https://fchavonet.github.io/holbertonschool-Fun-with-CSS/0-index.html).
- [1. Move the (under)line](https://fchavonet.github.io/holbertonschool-Fun-with-CSS/1-index.html).
- [2. Toggle](https://fchavonet.github.io/holbertonschool-Fun-with-CSS/2-index.html).
- [3. Menu](https://fchavonet.github.io/holbertonschool-Fun-with-CSS/3-index.html).

To compare, feel free to check the <a href="#instructions">instructions</a> section.

## 🎓 <span id="objectives">Objectives</span>

I aim to deepen my CSS skills by creating engaging, interactive designs. This project highlights the power and versatility of CSS in modern web development.

## 📋 <span id="requirements">Requirements</span>

- I am not allowed to import external CSS framework (like Bootstrap).
- I am are not to use Javascript.

## 📝 <span id="instructions">Instructions</span>

<details>
    <summary>
        <b>0. Sprite languages</b>
    </summary>
    <br>

By using this HTML:

```
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8" />
        <title>HBTN - 0- Sprite</title>

        <link href="0-styles.css" media="all" rel="stylesheet" type="text/css">
    </head>
    <body>
        <ul>
            <li>HTML<span class="icon i-html"></span></li>
            <li>CSS<span class="icon i-css"></span></li>
            <li>JavaScript<span class="icon i-js"></span></li>
        </ul>
    </body>
</html>
```

And this image file: [0-sprite.png](https://s3.eu-west-3.amazonaws.com/hbtn.intranet/uploads/medias/2020/2/d416199ca6ecdbd0f8a3.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIA4MYA5JM5DUTZGMZG%2F20240817%2Feu-west-3%2Fs3%2Faws4_request&X-Amz-Date=20240817T192013Z&X-Amz-Expires=345600&X-Amz-SignedHeaders=host&X-Amz-Signature=c0b79806d42a48f320404d8b640bcad7a537ba2fb7972d62de69de66be8e82e7)

Create `0-styles.css` and generate this layout:

<img src="./resources/images/task0-sprite_languages.png" alt="Sprite languages screenshot">

You are not allowed to change the image and the HTML - sprite is cool!

#
**Repo:**
- GitHub repository: `holbertonschool-Fun-with-CSS`.
- File: `1-index.html`, `1-styles.css`.
<hr>
</details>

<details>
    <summary>
        <b>1. Move the (under)line</b>
    </summary>
    <br>

By using this HTML:

```
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8" />
        <title>HBTN - 1- Underline</title>

        <link href="1-styles.css" media="all" rel="stylesheet" type="text/css">
    </head>
    <body>
        <h2>
            Hello <a href="https://www.holbertonschool.com">Holberton!</a>
        </h2>
    </body>
</html>
```

Create `1-styles.css` and generate this layout where the underline is hidden by default and appeared slowly:

<img src="./resources/images/task1-move_the_underline.gif" alt="Move the (under)line">

You are not allowed to change the HTML.

#
**Repo:**
- GitHub repository: `holbertonschool-Fun-with-CSS`.
- File: `0-index.html`, `0-styles.css`.
<hr>
</details>

<details>
    <summary>
        <b>2. Toggle</b>
    </summary>
    <br>

By using this HTML:

```
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8" />
        <title>HBTN - 2- toggle</title>

        <link href="2-styles.css" media="all" rel="stylesheet" type="text/css">
    </head>
    <body>
        <div class="toggle">
            <input type="checkbox" name="toggle" class="toggle-cb" id="toggle-0" checked>
            <label class="toggle-label" for="toggle-0">
                <div class="toggle-inner"></div>
                <div class="toggle-switch"></div>
            </label>
        </div>
    </body>
</html>
```

Create `2-styles.css` and generate this layout where the `<input>` is has this custom toggle layout:

**Checked:**

<img src="./resources/images/task3-checked.png" alt="Checked">

**Unchecked:**

<img src="./resources/images/task3-unchecked.png" alt="Unchecked">

You are not allowed to change the HTML.

#
**Repo:**
- GitHub repository: `holbertonschool-Fun-with-CSS`.
- File: `2-index.html`, `2-styles.css`.
<hr>
</details>

<details>
    <summary>
        <b>3. Menu</b>
    </summary>
    <br>

By using this HTML:

```
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8" />
        <title>HBTN - 2- toggle</title>

        <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css">
        <link href="3-styles.css" media="all" rel="stylesheet" type="text/css">
    </head>
    <body>

        <nav class="menu">
            <input type="checkbox" href="#" class="menu-open" name="menu-open" id="menu-open"/>
            <label class="menu-open-button" for="menu-open">
                <span class="menu-line menu-line-1"></span>
                <span class="menu-line menu-line-2"></span>
                <span class="menu-line menu-line-3"></span>
            </label>

            <a href="#" class="menu-item"> <i class="fa fa-area-chart"></i> </a>
            <a href="#" class="menu-item"> <i class="fa fa-bar-chart"></i> </a>
            <a href="#" class="menu-item"> <i class="fa fa-line-chart"></i> </a>
            <a href="#" class="menu-item"> <i class="fa fa-pie-chart"></i> </a>
            <a href="#" class="menu-item"> <i class="fa fa-table"></i> </a>
        </nav>

    </body>
</html>
```

Create `3-styles.css` and generate this layout/animation:

<img src="./resources/images/task4-menu.gif" alt="Menu animation screenshot">

You are not allowed to change the HTML.

#
**Repo:**
- GitHub repository: `holbertonschool-Fun-with-CSS`.
- File: `3-index.html`, `3-styles.css`.
<hr>
</details>

## 🔨 <span id="tech-stack">Tech stack</span>

<p align="left">
    <img src="https://img.shields.io/badge/HTML5-e34f26?logo=html5&logoColor=white&style=for-the-badge" alt="HTML5 badge">
    <img src="https://img.shields.io/badge/CSS3-1572b6?logo=css3&logoColor=white&style=for-the-badge" alt="CSS3 badge">
</p>

## 📂 <span id="files-description">File description</span>

| **FILE**       | **DESCRIPTION**                                         |
| :------------: | ------------------------------------------------------- |
| `Resources`    | Contains the images required for the projects.          | 
| `0-index.html` | Index page for the task `0. Sprite languages`.          |
| `0-styles.css` | CSS style sheet for the task `0. Sprite languages`.     |
| `1-index.html` | Index page for the task `1. Move the (under)line`.      |
| `1-styles.css` | CSS style sheet for the task `1. Move the (under)line`. |
| `2-index.html` | Index page for the task `2. Toggle`.                    |
| `2-styles.css` | CSS style sheet for the task `2. Toggle`.               |
| `3-index.html` | Index page for the task `3. Menu`.                      |
| `3-styles.css` | CSS style sheet for the task `3. Menu`.                 |
| `README.md`    | The readme file you are currently reading 😉.           |

## ♥️ <span id="thanks">Thanks</span>

A big thank you to all my Holberton School peers for their help and support throughout these projects.

## 👷 <span id="authors">Authors</span>

**Fabien CHAVONET**
- Github: [@fchavonet](https://github.com/fchavonet)
