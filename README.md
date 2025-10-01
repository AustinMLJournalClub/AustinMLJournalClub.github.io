# Austin ML Journal Club

[![Website](https://img.shields.io/badge/website-live-blue)](https://austinmljournalclub.github.io/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Follow-0077B5)](https://www.linkedin.com/company/austin-ml-journal-club)

Welcome to the Austin ML Journal Club blog repository. We are a community of ML/AI practitioners who meet monthly to deeply engage with cutting-edge research through rigorous discussion and critical analysis.

## About

The Austin ML Journal Club brings together ML/AI practitioners to explore cutting-edge research through focused discussion and collaborative learning. We meet monthly(ish) to dive deep into papers that are shaping our rapidly evolving field. We aim to nurture deep conversations and practitioner insights that reveal how the sausages get made.

Our blog posts capture the insights, debates, and practical perspectives that emerge when practitioners move beyond surface-level summaries to examine how methods actually work in practice.

## What You'll Find Here

- **Paper Discussions**: In-depth analyses and critiques of ML/AI research papers
- **Critical Perspectives**: Honest assessments of methodologies, claims, and practical implications
- **Community Insights**: Diverse viewpoints from practitioners across industry and academia

## How to Join

Follow our [LinkedIn page](https://www.linkedin.com/company/austin-ml-journal-club) for meeting announcements and registration details. Registration opens before each session and closes 48 hours prior to the meeting.

## Contributing

### Suggesting Papers

Have a paper you'd like us to discuss? You can:
- Open an issue in this repository
- Contact the organizer directly
- Bring it up during our meetings

We look for content that is impactful, thought-provoking, or offers practical insights into how machine learning works in practice.

### Writing Blog Posts

Blog posts are written collaboratively by meeting participants and summarize our discussions. If you've presented or attended a session:

1. Fork this repository
2. Create a new post directory in `posts/YYYYMMDD/`
3. Add your `index.qmd` file with the discussion summary
4. Include any figures in the same directory
5. Submit a pull request

See our [Quarto guidelines](quarto.md) for detailed blogging tips.

## Technical Details

This blog is built with:
- **[Quarto](https://quarto.org/)** - Publishing system for technical content
- **GitHub Pages** - Hosting
- **GitHub Actions** - Automated deployment

### Local Development

To preview the site locally:

```bash
# Install Quarto (see https://quarto.org/docs/get-started/)

# Preview the site
quarto preview

# Render the site
quarto render
```

### Repository Structure

```
.
├── posts/          # Blog posts (one directory per post)
├── docs/           # Rendered site (auto-generated)
├── _quarto.yml     # Site configuration
├── index.qmd       # Homepage
├── about.qmd       # About page
├── reading_list.qmd # Reading list
└── styles.css      # Custom styles
```

## Community Standards

We operate under the **Chatham House Rule** - participants are free to use information shared during meetings, but cannot reveal the source or identity of speakers. This creates a safe space for open intellectual exchange.

We maintain a welcoming environment for practitioners at all experience levels - from industry engineers to academic researchers to passionate learners.

## Organizer

[Hongsup Shin](https://www.linkedin.com/in/hongsupshin/) organizes the Austin ML Journal Club, managing meeting coordination, paper selection, and blog maintenance. He is a Principal AI Engineer at Arm with a background in computational neuroscience and behavioral ecology.

## License

Content in this repository is licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) unless otherwise noted.

---

**Questions?** Open an issue or reach out via our [LinkedIn page](https://www.linkedin.com/company/austin-ml-journal-club).
