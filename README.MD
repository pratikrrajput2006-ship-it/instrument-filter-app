#  Music Instruments Filter App

##  Description

This is a simple web application that displays musical instruments and allows users to filter them by category using a dropdown menu.

---

##  Features

* View instruments with name and price
* Filter instruments by category:

  * All
  * Woodwinds
  * Brass
  * Percussion
* Dynamic content update without page reload

---

##  Technologies Used

* HTML5
* CSS3
* JavaScript (ES6)

---

##  Project Structure

```
 project-folder
│── index.html
│── style.css
│── script.js
```

---

##  How It Works

* Instrument data is stored in a JavaScript array
* When the user selects a category:

  * The array is filtered using `filter()`
  * HTML cards are generated using `map()`
  * Cards are displayed using `innerHTML`

---

##  Example Functionality

* Select **Woodwinds** → shows only flute, clarinet, oboe
* Select **Brass** → shows trumpet, trombone, french horn
* Select **All** → shows all instruments

---

##  Learning Concepts

* DOM manipulation
* Event handling (`change` event)
* Array methods (`filter`, `map`)
* Dynamic rendering in JavaScript

---

##  Future Improvements

* Add search functionality
* Add instrument images
* Connect to real API
* Improve UI/UX

---

##  How to Run

1. Download or clone the repository
2. Open `index.html` in your browser

---

##  Author

Pratik Rajput.
