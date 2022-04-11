About this Book
=======================

## Authors

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tr>
    <td align="center"><a href="https://peterhcharlton.github.io/"><img src="https://avatars.githubusercontent.com/u/9865941?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Peter H Charlton</b></sub></a><br /><a href="#content-peterhcharlton" title="Content">🖋</a></td>
  </tr>
</table>

<!-- markdownlint-restore -->
<!-- prettier-ignore-end -->

It is hoped that it can become a collaborative project involving additional contributors.

## Contributing to the book


To contribute to this book, either:
```{dropdown} **1. Propose edits:** Follow these instructions to propose a specific change
- Go to the page you would like to edit
- Hover over the ![GitHub-Mark](GitHub-Mark-32px.png) button at the top of the page, and click 'suggest edit' from the dropdown list that appears.
- This will take you to GitHub, where you can edit the page directly and submit the proposed edits for approval. You will require a GitHub login to do this.
```
```{dropdown} **2. Suggest areas for improvement:** Follow these instructions to make a general suggestion
- If your suggestion relates to a specific page, then go to that page.
- Hover over the ![GitHub-Mark](GitHub-Mark-32px.png) button at the top of the page, and click 'open issue' from the dropdown list that appears.
- This will take you to GitHub, where you can post suggestions for improvement. You will require a GitHub login to do this.
```
When contributing, please either contribute your own ideas/text, or clearly acknowledge the original source of the ideas/text.

## Creating the book

The book was created as follows (largely following the instructions provided [here](https://jupyterbook.org/start/your-first-book.html)):
```{dropdown} **Steps to create the book:** 
1. Install Jupyter book via conda-forge (as detailed [here](https://jupyterbook.org/start/overview.html))
2. Create a template book (as detailed [here](https://jupyterbook.org/start/create.html))
3. Modify the template to include content from Peter Charlton's original project guidelines (available [here](https://peterhcharlton.github.io/info/tools/project_guidelines.html)).
4. Build the book (as detailed [here](https://jupyterbook.org/start/build.html)).
5. Publish the book online (storing the source files in a GitHub repository, and publishing the book using GitHub pages, as detailed [here](https://jupyterbook.org/start/publish.html)).
```

## Editing the book

There are two ways to edit the book:
```{dropdown} **1. Edit online:** Open to all
- Submit a proposed edit using the instructions provided above under ['Contributing to the book'](#contributing-to-the-book).
- This will be reviewed in due course.
```
```{dropdown} **2. Edit on a local computer:** Only open to project administrators
- Clone the repository

`cd /Users/petercharlton/Documents/GitHub/; git clone https://github.com/peterhcharlton/project_guidelines`
- Make edits to the files on a local computer.
- Upload the files through a git push (as detailed [here](https://jupyterbook.org/start/publish.html#create-an-online-repository-for-your-book)):

`cd /Users/petercharlton/Documents/GitHub/project_guidelines; git add ./*; git commit -m "brief edit"; git push`
- Build the book locally (as detailed [here](https://jupyterbook.org/start/build.html#build-your-books-html)): 

`cd ../.; jupyter-book build project_guidelines`
- Upload the built book to GitHub pages (as detailed [here](https://jupyterbook.org/start/publish.html#publish-your-book-online-with-github-pages)):

`cd project_guidelines; ghp-import -n -p -f _build/html`
```

