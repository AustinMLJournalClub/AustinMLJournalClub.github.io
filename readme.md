# Austin Journal Club Blog

Our blog uses [quarto](https://quarto.org/) platform and hosted via [GitHub Pages](https://pages.github.com/). This is a short guide for uploading blog posts using quarto.

1. [Install quarto](https://quarto.org/docs/get-started/hello/vscode.html). I chose the VS Code option.
2. Clone the blog repository.
3. Create an issue (issue title example: "Upload a blog post for the Feb 2023 meeting") and assign yourself.
4. Check out a new branch (branch name example: "6-write_blog")
5. Create a folder in `/posts`. The name of the folder should be the date of the meeting in YYYYMMDD format (e.g., `posts/20221027/`).
6. Create `index.qmd` inside the folder. This is the main file for your blog.
7. The top section of a blog post is a YAML block with document options. You must fill out `title, author, date, description, categories`.

    ```yaml
    ---
    title: "Paper title"
    author: "Author name"
    date: "YYYY-MM-DD"
    image: "This image will show on the main page (this is optional).jpg"
    description: Short description of the post. It will show on the main page.
    categories: [paper]
    ---
    ```

8. Before writing the body, please include the following right after the YAML block:

    ```markdown
    :::{.callout-note}
    - Paper: [paper title](link to original paper)
    - Presenter: [first name](linkedin profile)
    - Attendees: [first name 1 (alphabetical order)](linkedin profile), [first name 2](linkedin profile), ... 
    :::
    ```

9. To give everyone some context, I highly suggest starting the body with "Why this paper" paragraph.
10. If you want to include any images, you can include them in the same folder as `index.qmd`.
11. You can use `quarto preview` to preview the rendered look.
12. Once you are done with the post, run `quarto render`. This will automatically generate and modify html files in the `/docs` and the main folders.
13. Add all the changes, commit, and make a merge request to `main`.
14. Assign the attendees of the meeting as reviewers, and go through a review process.
15. Once your branch is merged after the review, close your issue ticket and delete the remote branch.

Currently the blog is hosted via `gh-pages` branch, and thus after `main` is updated, we will rebase main to `gh-pages` and the blog website will be automatically updated with your post.