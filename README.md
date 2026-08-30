# Austin ML Journal Club

[![Website](https://img.shields.io/badge/website-live-blue)](https://austinmljournalclub.github.io/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Follow-0077B5)](https://www.linkedin.com/company/austin-ml-journal-club)

**The Austin ML Journal Club concluded in August 2026. There will be no further sessions.** See the [closing announcement](https://austinmljournalclub.github.io/posts/202608-closing/index.html). This repository stays online as the club's archive.

## About

From October 2022 to July 2026, the Austin ML Journal Club brought together ML/AI practitioners to explore cutting-edge research through focused discussion and collaborative learning. We met monthly(ish) across 22 sessions to dive deep into papers that were shaping our rapidly evolving field, aiming to nurture deep conversations and practitioner insights that reveal how the sausages get made.

Our blog posts capture the insights, debates, and practical perspectives that emerged when practitioners moved beyond surface-level summaries to examine how methods actually work in practice.

## What You'll Find Here

- **Paper Discussions**: In-depth analyses and critiques of ML/AI research papers
- **Critical Perspectives**: Honest assessments of methodologies, claims, and practical implications
- **Community Insights**: Diverse viewpoints from practitioners across industry and academia

All 22 session write-ups are listed on the [Archives](https://austinmljournalclub.github.io/archives.html) page.

## Contributing

The club has concluded, so this repository is no longer accepting session write-ups or paper suggestions. Corrections to existing posts are still welcome via issue or pull request.

See our [Quarto guidelines](quarto.md) for a record of how posts were produced.

## Technical Details

This blog is built with:
- **[Quarto](https://quarto.org/)** - Publishing system for technical content
- **GitHub Pages** - Hosting, served from the committed `docs/` directory

### Local Development

To preview the site locally:

```bash
# Install Quarto (see https://quarto.org/docs/get-started/)

# Preview the site
quarto preview

# Render the site
quarto render
```

Rendering regenerates `docs/`, which must be committed for the live site to update.

### Repository Structure

```
.
├── posts/          # Blog posts (one directory per post)
├── docs/           # Rendered site (auto-generated, committed)
├── _quarto.yml     # Site configuration
├── index.qmd       # Homepage
├── about.qmd       # About page
├── archives.qmd    # Session index
├── reading_list.qmd # Reading list
└── styles.css      # Custom styles
```

## Community Standards

The club operated under the **Chatham House Rule** - participants were free to use information shared during meetings, but could not reveal the source or identity of speakers. This created a safe space for open intellectual exchange. Our [Code of Conduct](https://austinmljournalclub.github.io/code_of_conduct.html) is kept as a record of the standards that applied.

## Organizer

[Hongsup Shin](https://www.linkedin.com/in/hongsupshin/) organized the Austin ML Journal Club, managing meeting coordination, paper selection, and blog maintenance. He is a Senior AI & LLM Engineer at NVIDIA with a background in computational neuroscience and behavioral ecology.

## License

Content in this repository is licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) unless otherwise noted.
