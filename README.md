# BCA Brain Box

BCA Brain Box is a centralized, student-friendly study resource website for BCA
students. It organizes unit-wise notes, model papers, previous-year question
papers, and lab manuals across semesters.

The project is a lightweight static website built with HTML and CSS. It does
not require a framework, build step, or server-side backend.

## Subjects

### Semester 1
- Problem Solving Technique
- Discrete Structure
- Computer Architecture

### Semester 2
- OOPS Using Java
- Data Structures
- Operating System

### Semester 3
- Database Management System (DBMS)
- Python Programming
- Computer Networks

### Semester 4
- Design and Analysis of Algorithms
- Internet Technologies
- Artificial Intelligence

### Semester 5
- Data Analytics
- Web Programming
- Software Engineering
- Cryptography and Network Security
- Quantitative Techniques

## Project Structure

```text
.
├── index.html          # Main landing page
├── contribute.html     # Study material submission page
├── css/
│   └── style.css       # Shared styles
├── pages/
│   └── semester1.html ... semester5.html
└── subjects/
    └── subject-*.html  # Subject resource pages
```

## Run Locally

1. Clone or download this repository.
2. Open `index.html` directly in a browser, or serve the project with a simple
   local web server:

```bash
# Python 3
python -m http.server 8000
```

3. Visit `http://localhost:8000/`.

## Contributing

Contributions are welcome. You can submit study materials through the
[Contribute page](contribute.html), or contribute through GitHub by:

1. Forking the repository.
2. Creating a feature or content branch.
3. Adding or updating an HTML page.
4. Verifying every relative link and resource link.
5. Opening a pull request with a clear description.

Please review submissions for relevance and accuracy before sharing them.

## Adding a Subject

1. Create a subject page in `subjects/` using the existing subject pages as a
   template.
2. Update the appropriate semester page in `pages/`.
3. Link the subject page with a relative path.
4. Use `target="_blank"` for external resource folders.
5. Test navigation from the homepage to the subject page and back.

## Disclaimer

This project is for educational purposes and is built by students for students.
