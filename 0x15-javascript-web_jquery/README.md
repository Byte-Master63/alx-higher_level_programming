# 0x15. JavaScript - Web jQuery

## Project Overview

This project is designed to introduce the basics of jQuery, a fast, small, and feature-rich JavaScript library. It focuses on using jQuery to manipulate the DOM, handle events, and simplify tasks that are typically more complicated in vanilla JavaScript. Throughout this project, you'll learn how to integrate jQuery into a webpage to improve its functionality and user experience.

## Technologies Used

- HTML
- CSS
- JavaScript
- jQuery (v3.x)

## Project Objectives

- Learn how to incorporate jQuery into a webpage.
- Use jQuery to select HTML elements and manipulate their properties.
- Implement event handling with jQuery for interactive web pages.
- Learn how to simplify common tasks like animations, DOM manipulation, and AJAX requests using jQuery.

## Tasks and Features

### 1. **Task 0**: Introduction to jQuery
- Set up the project with the required files and load jQuery via CDN.

### 2. **Task 1**: jQuery DOM Manipulation
- Using jQuery, select and manipulate elements in the DOM (e.g., change text, hide/show elements, etc.).

### 3. **Task 2**: Event Handling
- Set up basic event handlers (click, mouseover, etc.) using jQuery.

### 4. **Task 3**: CSS Manipulation
- Use jQuery to dynamically change the CSS properties of HTML elements.

### 5. **Task 4**: Animations
- Implement simple animations such as fading, sliding, and toggling elements with jQuery.

### 6. **Task 5**: AJAX Requests with jQuery
- Make simple AJAX requests to retrieve data from an external source (e.g., JSON) and update the webpage dynamically.

## Installation

To set up this project locally, follow these steps:

1. Clone the repository:

    ```bash
    git clone https://github.com/your-username/0x15-javascript-web-jquery.git
    cd 0x15-javascript-web-jquery
    ```

2. Open the `index.html` file in your browser.

3. Ensure that jQuery is included via a CDN link or by downloading the library to your project.

## Examples

Here are some common jQuery operations that you'll encounter:

- **Select an element**:
    ```javascript
    $('#myElement')  // Selects the element with id="myElement"
    ```

- **Change text of an element**:
    ```javascript
    $('#myElement').text('New Text');
    ```

- **Add a CSS class to an element**:
    ```javascript
    $('#myElement').addClass('active');
    ```

- **Hide an element**:
    ```javascript
    $('#myElement').hide();
    ```

- **AJAX request**:
    ```javascript
    $.ajax({
        url: 'https://api.example.com/data',
        method: 'GET',
        success: function(response) {
            console.log(response);
        }
    });
    ```

