# Student Portal

A simple college **Student Portal** web page built with plain HTML and introductory CSS.
It is the solution to the lab *HTML + Introduction to CSS*.

A student can:

1. View their profile
2. See their skills
3. View their weekly class schedule
4. Register for a course

## Files

| File | Purpose |
|---|---|
| `student-portal.html` | The web page (HTML only). It loads the styles with `<link rel="stylesheet" href="style.css">`. |
| `style.css` | All the CSS: colors, selectors and layout. |
| `README.md` | This file. |
| `VIVA.md` | Practice questions and answers for the viva. |

## How to run

1. Keep `student-portal.html` and `style.css` in the same folder.
2. Double-click `student-portal.html` to open it in a browser (Chrome, Edge, Firefox).
3. No installation and no internet connection needed.

> If the styles do not appear, check that `style.css` is in the same folder and the file name matches the `href`.

## Page structure (lab parts)

| Lab part | What was built |
|---|---|
| Part 1 | Complete document: `<!DOCTYPE html>`, `<html>`, `<head>`, `<title>`, `<body>`, plus `<header>`, `<nav>`, `<main>`, `<section>`, `<footer>` |
| Part 2 | Header with the title, and a `<nav>` with links to Home, Profile, Courses and Register (they jump to sections using `#id`) |
| Part 3 | Profile table with `<thead>`, `<tbody>`, `<th>`, `<tr>`, `<td>` |
| Part 4 | Skills as an unordered list (`<ul>`) with 5 items |
| Part 5 | Weekly schedule table, Monday to Friday, 3 time slots |
| Part 6 | Registration form: text, email and text inputs, a `<select>`, radio buttons, checkboxes, Submit and Reset, all with `<label>` |
| Part 7 | Colors for `<h1>` and `<h2>`, light page background (in `style.css`) |
| Part 8 | Element, class (`.highlight`) and ID (`#student-name`) selectors |
| Bonus | "Top Performer" badge using `<span class="badge">` |

## Form details

- Every control has a `<label>` connected with `for` and `id`.
- Both radio buttons share `name="learning-mode"`, so only one can be selected.
- The checkboxes share `name="skills"`, so several can be selected.
- The dropdown starts on **Select Course**, which has an empty value.
- Name, email, student ID, course and learning mode use `required`, so the browser
  asks the student to fill them before Submit works.
- The form has no `action`, so Submit reloads the page and the entered values
  appear in the address bar. **Reset** clears the form.

## CSS used

- **Required by the lab:** `color`, `background-color`, element selectors, the class `.highlight`, the ID `#student-name`.
- **Small extras for a neat layout:** `font-family`, `font-weight`, `text-align`, `padding`, `margin`, `width`, `border`, `border-collapse`, `border-radius` (badge only), `text-decoration`, `list-style-position`, and one `nav a:hover` rule.
- Every extra can be deleted and the page still works; it just looks plainer.

## Lab rules check

- HTML and CSS only
- No JavaScript
- No Bootstrap, Tailwind or other framework
- No Flexbox or Grid
- Semantic, indented HTML with no duplicate IDs

## Final checks before submitting

1. All five sections are visible.
2. Both tables display correctly.
3. Selecting Online deselects Offline (and the other way round).
4. Headings, class and ID colors are applied.
5. Submit with an empty form shows browser messages; Reset clears everything.
6. Change the sample details (name, ID, email) to your own if your teacher expects that.
