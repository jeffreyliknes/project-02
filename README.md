# Project 2 - Instanews App

This is a project produced from the following lessons from Week 3 to Week 4:

1. Ajax, JSON, and APIs
2. Gulp
3. Sass / CSS Preprocessors
4. CSS3 Transitions & Transforms

---

## Installation Instructions
1. Go to terminal and type the following.
```
git clone https://github.com/nejmal/project-02.git
```
2. Go to project directory.
```
cd project-02
```
3. Open the index.html file in a browser and read some interesting news!

---

## Technologies Used
- HTML
- CSS
- JavaScript
  - jQuery
- Git
- GitHub
- Terminal
  - Homebrew
- Ajax
  - JSON
  - APIs
- Node.js
  - npm
  - Gulp
    - Uglify
    - Rename
    - ESLint
    - Browsersync
- Sass
  - SCSS
- CSS3
  - Transitions
  - Transforms
  - Keyframe animations

---

## Personal Learnings
Below are the subsequent learning outcomes.

### Network
Types of responses can be viewed on developer consoles under '**Network**'.
```
- 1xx: Informational
- 2xx: Success
- 3xx: Redirection
- 4xx: Client Error
- 5xx: Server Error
```

### Ajax (Asynchronous JavaScript And XML)
Other events are not blocked from happening while request is sent and arrival of response.
- *XMLHttpRequest (XHR) objects* interact with servers.

### jQuery's Ajax Methods
**To make Ajax requests:**
```
$.ajax()
.load()
$.get()
$.post()
$.getJSON()
$.getScript()
```
**To deal with Ajax responses:**
```
.done()
.fail()
.always()
.abort()
```

### JSON (JavaScript Object Notation)
Most common way to format data from Ajax and it is easy for humans and computers to use.

### API (Application Programming Interface)
A way to serve clients.

### Node.js
Allows JavaScript to be used outside of the browser.
- *Node Package Manager (npm)*
  - **Gulp**
    - [Gulp Plugins](http://gulpjs.com/plugins/)
      - Uglify: minifies files
      - Rename: rename files
    - Named tasks
  - [ESLint](https://eslint.org/)
    - *Linting*: process of using a program to find potential errors when analyzing code.

### Sass / SCSS
Preprocessor that takes one form of data and changes it to another form of data.

### Features
- **Nested rules**
  ```scss
  .x {
    style;
    y {
      style;
      style;
      z {
        style;
      }
    }
  }
  ```
- **Variables**
  ```scss
  $x: sth;
  ```
- **JS-style comments**
  ```scss
  // sth
  or /* sth */
  ```
- **Mixins**
  ```scss
  @mixin
    @include
  ```
  - **Media query**
    ```scss
    @mixin {
      @media (){
        @content; // Allows content to directly
      }
    }
    ```
- **Operations**
  ```scss
  BEDMAS
  ```
- **Functions**
  ```scss
  @function {}
  @extend
  ```

### CSS3 Transitions
Changes properties over a desired amount of time.

**Syntax**
```scss
.x {
  // shorthand
  transition: ; 

  // long form
  transition-property: all;
  transition-duration: 1s;
  transition-timing-function: 'ease-in-out';
  transition-delay: 1.5s
}
```

### CSS3 Transforms
Modifies(rotate | translate | scale | skew) elements in their coordinates.
- 2D
- 3D

### Keyframe Animations
Allows control over a CSS animation sequence.
**Syntax**
```scss
@keyframes resize {
  0% {
    style;
  }
  50% {
    style;
  }
  100% {
    style;
  }
}

// long form
.x {
  animation-name: resize;
  animation-duration: 3s;
  animation-iteration-count: infinite or #;
  animation-direction: alternate;
  animation-timing-function: ease-in-out;
}

// shorthand
.x {
  animation: resize 5s infinite alternate ease-in-out;
}
```
