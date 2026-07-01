# Kisumu Developer Meetup - HTML Learning Project

## Overview

This project is a simple event landing page for a developer meetup in Kisumu. The webpage provides information about the event, displays a schedule section, and includes a registration form for attendees.

The project introduces event website structure and combines several important HTML concepts such as semantic layout, tables, and forms.

---

# HTML Elements Used

## 1. `<!DOCTYPE html>`

Declares the document as an HTML5 webpage.

```html
<!DOCTYPE html>
```

### Purpose

* Tells the browser to use HTML5 standards.

---

## 2. `<html>`

The root element of the webpage.

```html
<html lang="en">
```

### Purpose

* Contains all page content.
* Specifies English as the page language.

---

## 3. `<head>`

Stores metadata about the webpage.

```html
<head>
```

### Elements Inside

#### `<meta>`

```html
<meta charset="UTF-8">
```

### Purpose

* Supports special characters and proper text display.

---

## Missing Element

A title should be included inside the head section.

Example:

```html
<title>Kisumu Developer Meetup</title>
```

This title appears on the browser tab.

---

## 4. `<body>`

Contains everything visible on the webpage.

```html
<body>
```

---

## 5. `<header>`

Represents the introductory section of the page.

```html
<header>
    <h1>Kisumu Developer Meetup</h1>
</header>
```

### Purpose

* Displays the event name.
* Gives visitors immediate context.

---

## 6. `<h1>`

Main page heading.

```html
<h1>Kisumu Developer Meetup</h1>
```

### Purpose

* Identifies the event.
* Improves accessibility and SEO.

---

## 7. `<main>`

Contains the primary content of the webpage.

```html
<main>
```

### Purpose

* Holds the most important content.
* Helps screen readers identify page content.

---

## 8. `<section>`

Groups related content together.

The page contains three sections:

### About Event

```html
<section>
    <h2>About Event</h2>
</section>
```

### Schedule

```html
<section>
    <h2>Schedule</h2>
</section>
```

### Register

```html
<section>
    <h2>Register</h2>
</section>
```

### Purpose

* Organizes the webpage into logical parts.

---

## 9. `<h2>`

Secondary headings used for page sections.

Examples:

```html
<h2>About Event</h2>
<h2>Schedule</h2>
<h2>Register</h2>
```

### Purpose

* Creates structure within the page.
* Improves readability.

---

## 10. `<table>`

Creates a table.

```html
<table>
```

### Purpose

* Displays event schedule information.

---

## 11. `<tr>`

Creates a table row.

```html
<tr>
```

### Purpose

* Organizes information horizontally.

---

## 12. `<th>`

Creates table headings.

```html
<th>Time</th>
<th>Activity</th>
```

### Purpose

* Labels table columns.

---

## 13. `<form>`

Creates a registration form.

```html
<form>
```

### Purpose

* Collects attendee information.

---

## 14. `<label>`

Describes an input field.

Examples:

```html
<label>Name</label>
<label>Email</label>
```

### Purpose

* Helps users understand what information is required.

---

## 15. `<input>`

Accepts user input.

Name field:

```html
<input type="text">
```

Email field:

```html
<input type="email">
```

### Purpose

* Allows users to enter information.
* Email type provides built-in validation.

---

## 16. `<button>`

Creates a clickable button.

```html
<button type="submit">
    Register
</button>
```

### Purpose

* Submits the registration form.

---

## 17. `<footer>`

Represents the footer section.

```html
<footer>
```

### Purpose

* Displays information at the bottom of the page.

---

## 18. `<p>`

Creates a paragraph.

```html
<p>Event Website</p>
```

### Purpose

* Displays footer text.

---

## Error 2: Extra Closing Section Tag

The code contains:

```html
</section>
```

after the table without a matching opening section.

This creates invalid HTML structure.

The table should remain inside the Schedule section.

Correct structure:

```html
<section>
    <h2>Schedule</h2>

    <table>
        ...
    </table>
</section>
```

---

## Suggested Schedule Table

```html
<table>
    <tr>
        <th>Time</th>
        <th>Activity</th>
    </tr>

    <tr>
        <td>09:00 AM</td>
        <td>Registration</td>
    </tr>

    <tr>
        <td>10:00 AM</td>
        <td>Web Development Session</td>
    </tr>

    <tr>
        <td>12:00 PM</td>
        <td>Networking</td>
    </tr>
</table>
```

---

# Website Structure

```text
HTML
│
├── Head
│   ├── Meta Charset
│   └── Title (Recommended)
│
└── Body
    ├── Header
    │   └── H1
    │
    ├── Main
    │   ├── About Event Section
    │   ├── Schedule Section
    │   │   └── Table
    │   │
    │   └── Register Section
    │       └── Form
    │           ├── Labels
    │           ├── Inputs
    │           └── Button
    │
    └── Footer
        └── Paragraph
```

---

# Improvements To Make

### Add Event Description

```html
<p>
Learn web development, networking, and career growth
with fellow developers in Kisumu.
</p>
```

### Add Event Location

```html
<p>Venue: Kisumu Innovation Hub</p>
```

### Add Date

```html
<p>Date: 15 July 2026</p>
```

### Add Required Validation

```html
<input type="text" required>

<input type="email" required>
```

### Add Placeholder Text

```html
<input type="text" placeholder="Enter your name">

<input type="email" placeholder="Enter your email">
```

### Add CSS Styling

Style:

* Header
* Schedule table
* Registration form
* Buttons
* Footer

---

# Learning Outcomes

After completing this project, you should understand:

* Semantic HTML structure
* Event landing page design
* Tables
* Forms
* Labels and inputs
* Buttons
* Sections
* Headers and footers
* Basic validation concepts

This project is a solid beginner event website and combines multiple HTML skills into a single practical webpage.
