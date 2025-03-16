## Resume

This repository contains my resume in LaTeX. Every time a push is made, the PDF is built and committed to the repository by GitHub Actions.

### Local requirements

- [LaTeX](https://www.latex-project.org/get/)
- [Cursor](https://cursor.sh/) (recommended) or your favorite text editor

### How to use?

1. Clone the repository.

```bash
git clone https://github.com/onurravli/resume.git
cd resume
```

2. Change the content of the `resume.tex` file with your own content.

3. To build the PDF locally, you can use the following command:

```bash
pdflatex resume.tex
```

4. To build the PDF with GitHub Actions, you can push the changes to the repository.

```bash
git add resume.tex
git commit -m "docs: update resume.tex"
git push
```

### Output

The generated PDF will be available as `resume.pdf` in the repository root. You can find the latest version [here](./resume.pdf).

### License

This project is licensed under the MIT License. See the [LICENSE.md](./LICENSE.md) file for details.
