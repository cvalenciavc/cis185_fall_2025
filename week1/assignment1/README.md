# Assignment 1 

# HTML Elements Exploration Assignment

**Student Name:** Claudine Valencia  
**Course:** CIS 185
**Assignment One:** HTML Elements Challenge  
**Date:** Oct. 7, 2025

## Project Overview

This project demonstrates the use of various HTML elements beyond the basic ones covered in class. I've created a web page that showcases different HTML elements and their functionality, along with custom CSS styling.

## HTML Elements Implemented

### 1. `<details>` and `<summary>`
**Purpose:** Creates collapsible content sections  
**How I used it:** Created an expandable section to reveal next projects 
**Why it's useful:** Saves space on the page while organizing content in an interactive way

```html
<details>
  <summary>Next project</summary>
  Stay tuned!
</details>
```

### 2. `<figure>` and `<figcaption>`
**Purpose:** Groups media content with its caption  
**How I used it:** Added an image with a descriptive caption below it  
**Why it's useful:** Gives more description to the image and encapsulates media content

```html
<figure>
    <img src="https://media.istockphoto.com/id/1189789308/photo/gorgeous-fluffy-black-cat-wearing-moony-sunglasses-pet-portrait.jpg?s=2048x2048&w=is&k=20&c=96XDG_qs27pN_R1AZ_Y-zAo800hz5cdWH6Ck7ZXPJW0=" alt="Black Cat with Sunglasses">
    <figcaption>Casper the Cuddly Cat</figcaption>
</figure>
```

### 3. `<blockquote>`
**Purpose:** Indicates that the enclosed text is a quotation. 
**How I used it:** Inserted a quote including source and date
**Why it's useful:** Separates content from main body paragraph

```html
<blockquote>
    "Those who dream by day are cognizant of many things which escape those who dream only by night" - from Eleonora, 1841
  </blockquote>
```

### 4. `<textarea>`
**Purpose:** represents a multi-line plain-text editing control
**How I used it:**Included text for the `<label>` to indicate a question, and the `<textarea>` reveals the answer 
**Why it's useful:** useful when you want to allow users to enter a sizeable amount of free-form text

```html
<label for="story">What is "A Dream Within A Dream" about?</label>
  <br>
  <textarea id="story" name="story" rows="5" cols="33">
  The poem explores the fragile boundary between reality and illusion. 
  The author grieves the loss of a loved one and reflects on how life seems to be slipping away. 
  That everything seems to lingering between a dream and reality, losing the grasp between the two...
  </textarea>
```

### 5. `<footer>`
**Purpose:** Contains information about the author of the section, copyright data or links to related documents
**How I used it:** Indicates the author of the page 
**Why it's useful:** Helps users find important information about the page

```html
<footer> 
    <p>©2025 CCCValencia</p>
  </footer>
```

## CSS Styling Applied

I applied custom styling to the following elements:

- **`<figure>`**: Added border, stacked image vertically and added padding
- **`<figcaption>`**: Gave a dark background, italic font, centered caption text
- **`<footer>`**: LLarger font size, light gray font color and space above footer

## Resources Used

- [MDN HTML Elements Reference](https://developer.mozilla.org/en-US/docs/Web/HTML/Reference/Elements)
- [W3Schools CSS Reference](hhttps://www.w3schools.com/cssref/index.php)
- [Google Fonts](https://fonts.google.com/)
- [Adobe Stock Photos](https://stock.adobe.com/photos)


## Files Included

- `index.html` - Main HTML file with all implemented elements
- `README.md` - This documentation file

---