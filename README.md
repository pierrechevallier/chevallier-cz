# Chevallier Dev website

Update website for personal projects and portfolio.

## Technical details

This website is using [Material for Mkdocs](https://squidfunk.github.io/mkdocs-material/) to be then published on GitHub pages.
I have 2 domain names this website is linked to: [chevallier.cz](https://chevallier.cz) and [chevallier.dev](https://chevallier.dev), both are redirecting towards the .dev domain

### Developmnent

Just for me for the moment, but overall:

Create a virtual environment with python and activate it

```bash
python -m venv .
source .venv/bin/activate
```

Install the packages and necessary tools.
It relies on uv, so it's better to use it if your laptop permits it.

```bash
```

### Running the development website

```bash
mkdocs serve
```

### Deployment

It's all handled with the GitHub Actions in the `.github/workflows/deploy-site.yaml` file.

## Content

### Blog

The blog is a way for me to write about topics that I like, mostly technologies and likely judo

### Judo

Self-explanatory, it's about judo...
