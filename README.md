# Resume in LaTeX with Overleaf

This repository contains the LaTeX source files for my professional resume. It is managed using Overleaf and synced with GitHub for version control.

## Features

- **Professional Design**: Clean and impactful resume layout using LaTeX.
- **Version Control**: Maintain multiple versions and track changes easily.
- **Overleaf Integration**: Seamlessly edit and compile using Overleaf with GitHub synchronization.

## How to Use

### Step 1: Clone the Repository  
To get started, clone this repository to your local machine:

```bash
git clone https://github.com/modhtanmay/resume-latex.git
cd resume-latex
```

### Step 2: Edit the Resume
Make updates to the resume by editing the resume.tex file:
- Open the file in Overleaf or your preferred LaTeX editor.
- Update your personal information, work experience, and additional sections as needed.
- Save your changes after editing.

### Step 3: Compile the Resume
You can compile the resume using one of the following methods:

Option A: Compile Using Overleaf
- Upload the repository to Overleaf.
- Open the resume.tex file.
- Click the "Recompile" button to generate the PDF.

Option B: Compile Locally
- If you prefer to compile locally, use the pdflatex command:

```bash
pdflatex resume.tex
```
This will generate a resume.pdf file in the same directory.

### Step 4: Sync Changes with GitHub
To ensure your updates are saved to GitHub:
Add your changes to the staging area:

```bash
git add .
```

Commit the changes with a descriptive message:
```bash
git commit -m "Updated resume with new content"
```

Push the changes to the remote repository:
``` bash
git push
```
