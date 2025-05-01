# Code Quiz Challenge

This project is an interactive web application where users can test their coding skills. The application is a quiz platform that includes multiple-choice questions and coding tasks.

## Project Features

- User registration and login
- Multiple-choice questions
- Coding questions with live code execution
- Scoreboard and statistics
- Theme switching (light/cream)
- Contact form
- Admin message system

## jQuery Plugins and jQuery-UI Widgets Used

### jQuery Plugins:

1. **jQuery Validation Plugin (v1.16.0)**
   - Usage: Input validation in the contact form
   - File: `https://cdn.jsdelivr.net/jquery.validation/1.16.0/jquery.validate.min.js`
   - Implementation: Form validation rules and custom validation methods (phoneUS) in the `contact.html` page

2. **jQuery DataTables (v1.13.6)**
   - Usage: Search, sorting, and pagination features in the score table
   - File: `https://cdn.datatables.net/1.13.6/js/jquery.dataTables.min.js`
   - Implementation: Advanced table features for the score list in the `score.html` page

3. **jQuery Theme Switcher (Custom)**
   - Usage: Dynamic theme switching (light theme/cream theme)
   - File: `scripts/theme.js`
   - Implementation: Theme toggle button and theme preference storage with localStorage on all pages

### jQuery UI Widgets:

1. **jQuery UI Dialog**
   - Usage: Quiz results and user notifications
   - File: `https://code.jquery.com/ui/1.13.2/jquery-ui.js`
   - Implementation: Displaying quiz results and user feedback in the `quiz.html` page

2. **jQuery UI Datepicker**
   - Usage: Date selection in the contact form
   - File: `https://code.jquery.com/ui/1.13.2/jquery-ui.js`
   - Implementation: Expected response date selection in the `contact.html` page

## Running Requirements

1. Run the project on a web server or local server
2. Open the `index.html` file
3. You will be automatically redirected to the login page on first access
4. Register or log in (any username/password is accepted)

## Browser Requirements

- Modern web browsers (Chrome, Firefox, Safari, Edge)
- JavaScript must be enabled
- localStorage support required

## Working URL

- Working version of the project: https://0xefeba.github.io/code-quiz-challenge

## Project Team

- Efe Bekir Altop
- Furkan Macit 
