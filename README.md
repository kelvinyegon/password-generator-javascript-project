

# Password Generator (JavaScript Project)

this is a  simple and responsive Password Generator built using **HTML, CSS, and JavaScript**.
it  helps  users to generate strong random passwords based on selected criteria.



## Features

* it has Adjustable password length (1–30 characters)
* it includes
  * ✅ Lowercase letters (a–z)
  * ✅ Uppercase letters (A–Z)
  * ✅ Numbers (0–9)
  * ✅ Symbols (~!@#$%^&*)
* you can  Copy password to clipboard with one click
* then Clean and modern UI
* Fully responsive layout



##  Project Structure


password-generator/
│── index.html
│── styles.css
│── script.js
│── README.md




##   the Technologies Used are

* **HTML5** – for the  Structure
* **CSS3** –  used for the Styling and layout
* **JavaScript (Vanilla JS)** –  for the Functionality and password generation
* **Google Material Icons** –  to Copy  all the icon

##  How It Works

1. User selects:

   * Password length using slider
   * Character types using checkboxes
2. When "Generate Password" button is clicked:

   * Selected character sets are combined
   * A random password is generated
3. Clicking the copy icon:

   * Copies password to clipboard
   * Shows confirmation icon temporarily



##  How to Run the Project

1.  you may Download or clone the repository.
2.  you should Make sure all  that all the files are in the same folder:

   * `index.html`
   * `styles.css`
   * `script.js`
3. Open `index.html` in your browser.

No installation required.



## Password Generation Logic

The generator:

* Combines selected character sets
* Randomly picks characters using:

```javascript
Math.floor(Math.random() * allChars.length)
```

* Repeats until selected length is reached



## Preview

* Gradient background
* Centered card layout
* Modern shadow effects
* Interactive copy button



## Example Output

gT7#kP9!
`



##  this are the Future Improvements (Optional Ideas)

*  to Add password  thats strength indicator
* to  Prevent generation if there is no checkbox that is selected
*  to Add animation effects
*  to Add dark and  light theme toggle
*for use of   crypto-based secure random generator


## Author

kelvin chesang yegon
 
 
 
 
 to access this code git clone https://github.com/kelvinyegon/password-generator-javascript-project


