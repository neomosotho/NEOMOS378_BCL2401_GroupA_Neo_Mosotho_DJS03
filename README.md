# DJS03 Project Brief: Book Connect - Abstractions

Dive into the delightful world of "Book Connect," where literary adventures await at your fingertips! Browse, explore, and uncover your next great read from a vast, vibrant collection. Whether you're a fan of thrilling mysteries, epic fantasies, or heartwarming romances, "Book Connect" brings the magic of books directly to you. Happy reading! 

The "Book Connect" project provides an opportunity for students to refine a fully functional version of an application. The focus of this project is to enhance the code's maintainability, extendibility, and readability by applying concepts of objects and functions for abstraction. This will not only streamline future modifications but also consolidate students' understanding of higher-level programming concepts, including documentation, Styleguides, and abstraction principles.

## Features
Book Previews: Display a list of books with previews that include the book's image, title, and author.

Filter Options: Users can filter books by genre, author, and title.

Theme Switching: Toggle between day and night themes based on user preference.

Detailed Book Reviews: View detailed information about a selected book in an overlay.

## Project Structure
The project structure includes several key components and scripts:

data.js: Contains the data and constants for books, authors, genres, and the number of books per page.
main.js: Main JavaScript file that initializes the application and manages the core functionality.

## Abstraction for maintainability
## Modular Functions:

Functions like createBookPreviews and createOptions were designed to perform specific tasks, making them easy to understand and test.
This abstraction allows these functions to be reused across different parts of the application or even in different projects, enhancing code reusability and reducing duplication.

## Shadow DOM for Scoped Styles:

Using Shadow DOM in Web Components (this.attachShadow({ mode: 'open' })) scopes styles to the component, preventing styles from leaking out or being affected by global styles.
This ensures consistent styling and reduces the complexity of managing CSS in large projects.

## Challenges:
Maintaining Performance: Ensuring that the application remains performant after adding the abstraction layers.
Understanding and implementing abstractions.

## Feedback:
This project was very challenging. I managed to complete it based on the requirements.