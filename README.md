# NUMUGISHA Emelyne | Portfolio

A responsive personal portfolio website built with HTML and CSS.

## Live Website

[View the portfolio](https://numugishaemelyne.github.io/myportfolio/)

## Features

- Responsive layout for desktop and mobile screens
- About, skills, projects, and contact sections
- Smooth scrolling navigation
- Contact link using the portfolio email address

## Built With

- HTML5
- CSS3

## Project Structure

```text
.
├── images/
│   └── image.jpeg
├── styles/
│   └── main.css
├── index.html
├── LICENSE
└── README.md
```

## Run Locally

Open `index.html` directly in a browser, or serve the folder with any static web server:

```bash
python3 -m http.server 8000
```

Then visit http://localhost:8000.

## Test Plan (Task 1)

The following test plan defines the checks used for the portfolio website and matches the log IDs used in the test logs (TC-01, TC-02, etc.). A test is considered PASS when the expected URL, section visibility, or user action result is observed; a negative test is expected to fail or be handled gracefully and must be logged as a failure.

| Test ID | What is tested | Steps | Expected result |
| --- | --- | --- | --- |
| TC-01 | Portfolio homepage loads | Open the live portfolio URL and wait for the page to load. | The homepage loads successfully and the page title is not empty. |
| TC-02 | About navigation link works | Click the About menu link in the navigation bar. | The browser URL updates to the About section (for example, ends with #about). |
| TC-03 | Projects navigation link works | Click the Projects menu link. | The browser URL updates to the Projects section (for example, ends with #projects). |
| TC-04 | Contact navigation link works | Click the Contact menu link. | The browser URL updates to the Contact section (for example, ends with #contact). |
| TC-05 | Email or contact action works | Click the email/contact button or link on the page. | The mail client or contact link opens correctly with the valid contact target. |
| TC-06 | Negative test: missing section/incorrect locator | Try to locate a known missing section or deliberately incorrect link selector (for example, a section that does not exist). | The test fails or is handled gracefully and the failure is logged with the correct error details. |
| TC-07 | Page title and main sections are visible | Reload the homepage and inspect the page title and major sections. | The title remains visible and the About, Projects, and Contact sections are still present. |

## License

This project is licensed under the [MIT License](LICENSE).
