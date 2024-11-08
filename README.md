# COMBINI Website

This repository contains the source code for the COMBINI project website. The site is built using Jekyll and the Petridish theme.

## Quick Start for Content Updates

### Adding/Updating Pages

1. Pages are located in the `pages/` directory
2. Each page needs a YAML front matter block with:
   ```yaml
   ---
   title: Page Title
   description: Brief description
   background: assets/theme/images/background.jpg
   permalink: /page-url/
   ---
   ```

### Adding Team Members

1. Edit `_data/team.yml` to add/modify team members
2. Required fields:
   ```yaml
   - name: Full Name
     role: Role Title
     description: Brief bio
     image: assets/theme/images/team/photo.jpg
   ```
3. Optional fields: orcid, researchgate, googlescholar, twitter, mastodon, github, email

### Adding Publications

1. Update `pages/publications.md`
2. Use the following format for citations:
   ```markdown
   1. Author Names. Title. *Journal Name*. Year;Volume(Issue). doi:[DOI](https://doi.org/XXX)
   ```

### Adding Software/Tools

1. Edit `pages/software.md`
2. Use sections for:
   - Current Tools
   - Planned Releases
   - Features & Status
   - Usage Instructions

### Adding Images

1. Place images in `assets/theme/images/`
2. For team photos: `assets/theme/images/team/`
3. Recommended image sizes:
   - Background images: 1920x1080px
   - Team photos: 400x400px square
   - Logo: 200px height

## Site Configuration

### Navigation Menu

Edit `_data/navigation.yml` to modify the top navigation menu.

### Footer Content

Edit `_data/footer.yml` to update:
- Footer columns and content
- Institution links
- License information

### Site Settings

Main configuration is in `_config.yml`:
- Site title
- Base URL
- Social media links
- Theme settings

## Development

### Local Setup

1. Install Ruby and Bundler
2. Run:
   ```bash
   bundle install
   bundle exec jekyll serve
   ```
3. Visit http://localhost:4000/combinisite/

### Theme Documentation

This site uses the Petridish theme. For detailed theme documentation, visit:
https://github.com/peterdesmet/petridish

## Need Help?

For questions about website updates, please contact:
- Technical issues: drshika 2 @ illinios . edu
- Content updates: [PI contact]