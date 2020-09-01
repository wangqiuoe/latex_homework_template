## Declaration
clone from <https://github.com/jstrieb/homework-template.git>,
and make some customized changes

## Usage & Notes
Once the installed, using the template is as simple as invoking `homework` as the designated document class and including some additional options. For example:
```
\documentclass[name=Jacob\ Strieb, id=xxx, course=Linear\ Algebra, hwname=Homework\ 01]{homework}

\begin{document}
    Content...
\end{document}
```

## Document Class Options

The following key-value parameters are accepted by the document class at declaration.
- `name` (required) – name of the student typing the assignment
- `course` (required) – course identifier
- `id` (required) – Student ID (used for student email)
- `hwname` (required) - name of homework
- `emaildomain` (optional) – email address domain to be used with student ID; defaults to `lehigh.edu`
