# HNG Stage 1B - Testable Profile Card

## Description

This project is a responsive and accessible Profile Card built using HTML, CSS, and JavaScript. It follows semantic HTML practices and includes required `data-testid` attributes for automated testing.

---

## Features

* Semantic HTML structure (`article`, `figure`, `nav`, `section`)
* All required `data-testid` attributes present on visible elements
* Dynamic current time displayed in milliseconds using `Date.now()`
* Accessible avatar image with meaningful alt text
* Social link (LinkedIn) opens in a new tab with proper security attributes
* Hobbies and dislikes displayed as structured lists
* Keyboard accessible navigation (focusable links)
* Responsive layout (mobile, tablet, desktop)

---

## Technologies Used

* HTML
* CSS (Flexbox + Media Queries)
* JavaScript

---

## How to Run Locally

1. Clone the repository
2. Open `index.html` in your browser

---

## Key Decisions

* Used semantic HTML elements for better accessibility and structure
* Ensured every visible element includes a `data-testid` for stable testing
* Used `aria-live="polite"` to announce time updates for screen readers
* Used Flexbox for responsive layout

---

## Trade-offs / Limitations

* Static profile data (no backend or dynamic user input)
* Only one social link included
* Avatar uses a placeholder image (can be replaced with real image URL)

---

## Accessibility Notes

* All images include descriptive `alt` text
* Links are keyboard accessible and have visible focus styles
* Time updates are announced using `aria-live`
* Semantic elements improve screen reader navigation

---

## Live Demo

https://chizaram-julius.github.io/hng-stage-1b-profile-card/

---

## GitHub Repository

https://github.com/chizaram-julius/hng-stage-1b-profile-card

