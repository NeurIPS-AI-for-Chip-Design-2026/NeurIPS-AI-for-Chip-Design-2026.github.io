# NeurIPS 2026 Workshop on AI for Chip Design

This repository contains the source code for the official website of the **NeurIPS 2026 Workshop on AI for Chip Design**.

**URL:** https://NeurIPS-AI-for-Chip-Design-2026.github.io/

## About the Workshop

The workshop brings together researchers and practitioners from machine learning, electronic design automation (EDA), computer architecture, and semiconductor design to discuss recent advances in AI-driven chip design.

Our goal is to foster collaboration across these communities and highlight emerging methods, open challenges, and real-world applications of AI for semiconductor design.

## Website

The website is built with **Quarto** and deployed using **GitHub Pages**.

### Local development

Clone the repository and start a live preview:

```bash
git clone https://github.com/NeurIPS-AI-for-Chip-Design-2026/NeurIPS-AI-for-Chip-Design-2026.github.io.git
cd NeurIPS-AI-for-Chip-Design-2026.github.io

quarto preview
```

### Deployment

After committing changes:

```bash
git push
quarto publish gh-pages
```

The updated website will be published automatically to GitHub Pages.

## Repository Structure

```
.
├── _quarto.yml
├── index.qmd
├── styles.css
├── pages/
├── images/
└── files/
```

## Organizers

* Dario Garcia-Gasulla — Barcelona Supercomputing Center (BSC)
* Gokcen Kestor — Barcelona Supercomputing Center (BSC)
* Emanuele Parisi — Barcelona Supercomputing Center (BSC)
* Zhiyao Xie — Hong Kong University of Science and Technology (HKUST)
* Luca Benini — ETH Zürich & Università di Bologna
* Leigh Anne Clevenger — Silicon Integration Initiative (Si2)
* Cong (Callie) Hao — Georgia Institute of Technology

## Contact

Reach out to: neurips-ai-chip-design-2026@bsc.es

## License

Unless otherwise stated, the website content is © the workshop organizers.

The website source code may be reused under the MIT License. Third-party logos, images, and trademarks remain the property of their respective owners.

