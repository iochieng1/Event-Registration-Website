# Kisumu Developer Meetup - HTML Learning Project

## Overview

The **Kisumu Developer Meetup** project is a simple event landing page built with HTML5. It provides information about a local developer meetup, displays an event schedule, and allows attendees to register through a form.

This project demonstrates the use of semantic HTML elements, tables, forms, metadata, accessibility improvements, and basic webpage organization.

---

# Features

* Semantic HTML5 page structure
* Event information section
* Schedule table with activities and times
* Registration form with validation
* Responsive viewport configuration
* SEO-friendly metadata
* Accessible form labels and inputs
* Structured footer information

---

# HTML Elements Used

## 1. `<!DOCTYPE html>`

Declares the document as an HTML5 webpage.

```html
<!DOCTYPE html>
```

### Purpose

* Ensures browsers render the page using HTML5 standards.

---

## 2. `<html>`

Root element of the webpage.

```html
<html lang="en">
```

### Purpose

* Contains all webpage content.
* Specifies English as the document language.

---

## 3. `<head>`

Stores metadata and configuration information.

```html
<head>
```

### Elements Included

#### Character Encoding

```html
<meta charset="UTF-8">
```

Ensures proper display of text and special characters.

#### Viewport

```html
<meta name="viewport" content="width=device-width, initial-scale=1.0">
```

Makes the page adapt better to mobile devices.

#### Description

```html
<meta name="description"
      content="Kisumu Developer Meetup - Connect, learn, and grow with fellow developers.">
```

Provides search engines with a summary of the page.

#### Title

```html
<title>Kisumu Developer Meetup</title>
```

Displayed on the browser tab.

---

## 4. `<body>`

Contains all visible content displayed to users.

```html
<body>
```

---

## 5. `<header>`

Introduces the webpage.

```html
<header>
    <h1>Kisumu Developer Meetup</h1>
    <p>Connect, Learn, and Grow with the Local Tech Community</p>
</header>
```

### Purpose

* Displays the event name.
* Provides a short event slogan.

---

## 6. `<main>`

Contains the primary content of the webpage.

```html
<main>
```

### Purpose

* Groups the most important content.
* Improves accessibility.

---

## 7. `<section>`

Used to organize content into meaningful parts.

The page contains:

### About Section

```html
<section id="about">
```

### Schedule Section

```html
<section id="schedule">
```

### Register Section

```html
<section id="register">
```

### Purpose

* Creates logical content groups.
* Improves navigation and readability.

---

## 8. Headings (`<h1>` and `<h2>`)

### Main Heading

```html
<h1>Kisumu Developer Meetup</h1>
```

### Section Headings

```html
<h2>About the Event</h2>
<h2>Schedule</h2>
<h2>Register</h2>
```

### Purpose

* Establishes content hierarchy.
* Improves accessibility and SEO.

---

## 9. Paragraphs (`<p>`)

Used throughout the page.

Examples:

```html
<p>Connect, Learn, and Grow with the Local Tech Community</p>
```

```html
<p>
Join developers, designers, and tech enthusiasts
from Kisumu for a day of networking and learning.
</p>
```

### Purpose

* Provides descriptions and supporting information.

---

## 10. Table Elements

### Table

```html
<table border="1">
```

### Table Head

```html
<thead>
```

### Table Body

```html
<tbody>
```

### Rows

```html
<tr>
```

### Headings

```html
<th>Time</th>
<th>Activity</th>
```

### Data Cells

```html
<td>09:00 AM</td>
<td>Registration & Networking</td>
```

### Purpose

* Displays event schedule information in a structured format.

---

## 11. Form

```html
<form action="#" method="post">
```

### Purpose

* Collects attendee registration information.

---

## 12. Labels

```html
<label for="name">Name</label>
<label for="email">Email</label>
```

### Purpose

* Improves accessibility.
* Associates labels with input fields.

---

## 13. Inputs

### Name Field

```html
<input
    type="text"
    id="name"
    name="name"
    placeholder="Enter your full name"
    required
>
```

### Email Field

```html
<input
    type="email"
    id="email"
    name="email"
    placeholder="Enter your email"
    required
>
```

### Purpose

* Accepts user information.
* Provides built-in validation.
* Displays helpful placeholder text.

---

## 14. Button

```html
<button type="submit">
    Register
</button>
```

### Purpose

* Submits the registration form.

---

## 15. Footer

```html
<footer>
```

Example:

```html
<p>&copy; 2026 Kisumu Developer Meetup. All rights reserved.</p>
```

### Purpose

* Displays copyright information.
* Appears at the bottom of the page.

---

# Website Structure

```text
HTML
│
├── Head
│   ├── Meta Charset
│   ├── Viewport Meta
│   ├── Description Meta
│   └── Title
│
└── Body
    ├── Header
    │   ├── H1
    │   └── Intro Paragraph
    │
    ├── Main
    │   ├── About Section
    │   ├── Schedule Section
    │   │   └── Table
    │   │       ├── Thead
    │   │       └── Tbody
    │   │
    │   └── Register Section
    │       └── Form
    │           ├── Labels
    │           ├── Inputs
    │           └── Submit Button
    │
    └── Footer
        └── Copyright Text
```

---

# Accessibility Improvements

This version includes several accessibility enhancements:

* Labels connected to form fields using `for` and `id`.
* Semantic elements such as `header`, `main`, `section`, and `footer`.
* Proper heading hierarchy.
* Required form validation.
* Descriptive placeholder text.

---

# Future Enhancements

Potential improvements include:

* Add external CSS styling.
* Improve mobile responsiveness.
* Add event location and date.
* Include speaker profiles.
* Add navigation links.
* Connect the registration form to a backend service.

---

# Learning Outcomes

By completing this project, you will gain experience with:

* Semantic HTML5 structure
* Metadata and SEO basics
* Responsive webpage setup
* Tables and tabular data
* Forms and validation
* Accessibility best practices
* Page organization and hierarchy
* Event landing page development

This project serves as a practical introduction to building well-structured and accessible webpages using HTML.

