About this Book
=======================

## Authors

This initial draft was written by [Peter H. Charlton](https://peterhcharlton.github.io).

It is hoped that it can become a collaborative project involving additional contributors.

## Creating the book

The book was created as follows (largely following the instructions provided [here](https://jupyterbook.org/start/your-first-book.html)):
1. Install Jupyter book via conda-forge (as detailed [here](https://jupyterbook.org/start/overview.html))
2. Create a template book (as detailed [here](https://jupyterbook.org/start/create.html))
3. Modify the template to include content from Peter Charlton's original project guidelines (available [here](https://peterhcharlton.github.io/info/tools/project_guidelines.html)).
4. Build the book (as detailed [here](https://jupyterbook.org/start/build.html)).

## Editing the book

There are two ways to edit the book:
1. **Online:**
2. **On a local computer:** This approach is only possible for administrators:
   - Make edits to the files on a local computer.
   - Upload the files through a git push:
   ```
   git add ./*
   git commit -m "commit message"
   git push
   
   ```
   - Build the book locally: ``jupyter-book build project_guidelines``
   - Upload the built book to GitHub pages: ``ghp-import -n -p -f _build/html``