# LLM Workshop Website

This repository contains the source code for the Large Language Models for Linguistic Analyses Workshop website.

## Workshop Details
- **Title**: Large Language Models for Linguistic Analyses: Applications and Limitations
- **Date**: 24–25 November 2025
- **Location**: University of Cologne
- **Organized by**: CRC 1252 "Prominence in Language"

## Live Site
The website is automatically deployed to: https://sfb1252.github.io/llm-workshop/

## Local Development

### Prerequisites
- Python 3.8+
- pip

### Setup
```bash
# Install dependencies
pip install -r requirements.txt

# Serve locally
python -m mkdocs serve
```

Open http://127.0.0.1:8000/ to view the site locally.

### Build
```bash
python -m mkdocs build
```

## Project Structure
- `docs/` - Markdown source files
- `mkdocs.yml` - Site configuration
- `.github/workflows/` - GitHub Actions for deployment

## Contributing
1. Make changes to the Markdown files in `docs/`
2. Test locally with `mkdocs serve`
3. Commit and push changes
4. GitHub Actions will automatically deploy updates

## Note
Some of the coding and setup in this project was assisted by AI with human verification and oversight.

## Contact
For questions about the workshop: job.schepens@uni.koeln.de