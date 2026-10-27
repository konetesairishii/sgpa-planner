# sgpa-planner
# SGPA Planner

A simple, student-focused web tool to calculate and plan Semester Grade Point Average (SGPA).

SGPA Planner helps students estimate their semester performance by entering course credits and grade points. The goal is to make academic planning easier, clearer, and more accessible.

## Features

- **SGPA Calculator** — Calculate SGPA using course credits and grade points.
- **Course-wise Input** — Enter details for individual subjects.
- **Instant Results** — View your calculated SGPA based on the entered values.
- **Simple Interface** — Designed to be straightforward and easy to use.
- **Browser-based** — Use it directly in your browser without installing software.

## Calculation

SGPA is calculated using the credit-weighted average:

\[
\text{SGPA} = \frac{\sum(\text{Credits} \times \text{Grade Points})}{\sum \text{Credits}}
\]

Each course's grade points are multiplied by its credits. The products are added together and divided by the total credits.

*Results depend on the grade points and credit values entered. Always verify your institution's grading rules.*

## Built With

- HTML
- CSS
- JavaScript

## Getting Started

### Use Online

Open the deployed website using the project link in the repository description.

### Run Locally

1. Clone this repository:

   ```bash
   git clone https://github.com/YOUR-USERNAME/sgpa-planner.git
   ```

2. Open the project folder.
3. Open `index.html` in your browser.

No additional installation is required for the basic browser-based version.

## Project Structure

```text
sgpa-planner/
├── index.html
├── snist_target_sgpa_planner.html
└── README.md
```

The structure above reflects the files currently expected in the repository. Update it if you organise the CSS, JavaScript, or assets into separate folders.

## Purpose

This project was created as a learning project to practise web development and build a useful academic planning tool for students.

## Future Improvements

- Save and manage multiple semester records
- Add clearer input validation
- Support configurable grading systems
- Improve accessibility and mobile usability

## Disclaimer

This is an independent student project and is not an official academic tool. Calculated results are estimates and should be checked against your institution's official grading regulations.

## License

No license has been specified yet. Unless a license is added, the repository's default copyright protections apply.
