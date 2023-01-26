# Austin Machine ML Journal Club Blog

This is the repository for Austin Machine Learning (ML) Journal Club blog. This blog is a [Quarto](https://quarto.org/) website and uses [GitHub Pages](https://pages.github.com/) as a hosting service.

## How to start blogging

1. Install [Quarto](https://quarto.org/). I used the VS code option.
2. Clone this blog repository
3. Create a new branch.
   - We plan to adopt a **peer-review policy** for all our posts. Members who were either presented at the meeting or who read the paper will become the reviewers of a `paper` post.
   - Since all posts are built from the `gh-pages` branch, authors need to create their own branch to create a new post. Once done, authors can submit a pull request to start the review process.
   - During the review process, members can comment on the manuscript or on any missing discussions during the meeting. Once the review is done, the branch will be merge to `gh-pages` and it will be automatically published.
4. To create a new post, create a folder under `/docs/posts` and add an `index.qmd` file to the directory (see [Creating a Blog](https://quarto.org/docs/websites/website-blog.html) from Quarto docs for more information on how to create a post using `.qmd` format).
   - Use [`quarto preview`](https://quarto.org/docs/computations/python.html#workflow) to set up a live preview of changes in your post.
5. Once you are done with your post, run `quarto render` to render your `index.qmd` post to html.
6. Add all changes to your commit. Make sure you don't forget `docs/index.html` because if this file is not updated, your post will not be shown.
7. Make a pull request from your branch to `gh-pages`, and assign reviewers.
