# MisinformED - Static Landing Page  

## **Overview**

MisinformED is a **static landing page** built with **Hugo** and deployed using **GitHub Pages**. This project is based on the *hugo-bootstrap-theme* and serves as a demo for an educational misinformation tracking platform.  

## **Branches**

- `main` - Primary source branch  
- `gh-pages` - Deployment branch for GitHub Pages  

## **Project Structure**  

### **Top-Level Folders**

- **`assets/`** - Contains SCSS stylesheets for custom theming  
- **`content/`** - Markdown (`.md`) files for site text and blog posts  
- **`layouts/`** - Custom HTML templates for page rendering  
- **`static/`** - Stores images, logos, and other static assets  
- **`themes/`** - Includes the `hugo-bootstrap-theme` submodule, which this site is based on  
- **`.github/workflows/`** - GitHub Actions workflow for automatic deployment  

### **Key Files**

- **`config.toml`** - The Hugo configuration file  
- **`LICENSE`** - Licensing information  
- **`README.md`** - This document  
- **`.gitignore`** - Defines ignored files for version control  
- **`.gitmodules`** - Configures theme submodules  
- **`publish_to_gh_pages.sh`** - Utility script to manually deploy the site  
- **`USER-STORIES.md`** - Documents use cases and user goals for the project  

## **Running the Project Locally**  

To run this site locally, follow these steps:  

1. Clone the repo
2. Run `cd hugo-mock-landing-page`
3. Install hugo (> v99 should be good)
4. Run `hugo server`
