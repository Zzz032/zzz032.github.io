# Hosting and Formatting Resume on GitHub Pages

## Purpose

This README outlines the practical steps for hosting and formatting a resume on GitHub Pages, demonstrating these processes in line with the principles of current Technical Writing as outlined by Andrew Etter in his book *Modern Technical Writing*.
![resume](GIF/resume.gif)

## Prerequisites

1. A [resume](https://github.com/Zzz032/zzz032.github.io/blob/main/index.md) formatted in Markdown 
2. A GitHub account, such like that [my account](https://github.com/Zzz032).
3. Familiarity with Markdown. and this is the [Markdown Tutorial](https://www.markdowntutorial.com/).


## Contents
- [Hosting and Formatting Resume on GitHub Pages](#hosting-and-formatting-resume-on-github-pages)
  - [Purpose](#purpose)
  - [Prerequisites](#prerequisites)
  - [Contents](#contents)
  - [Instructions](#instructions)
    - [1. Create a GitHub Repository](#1-create-a-github-repository)
    - [2. Add Resume to the Repository](#2-add-resume-to-the-repository)
    - [3. Enable GitHub Pages](#3-enable-github-pages)
  - [Jekyll](#jekyll)
  - [More Resources](#more-resources)
  - [Authors and Acknowledgements](#authors-and-acknowledgements)
  - [FAQs](#faqs)


## Instructions

### 1. Create a GitHub Repository

**Relating to Etter's Principles**: Utilize lightweight tools and distributed version control systems, as Etter recommends.

1. Sign into GitHub and click the '+' icon at the top right to select 'New Repository'.
2. Name my repository `username.github.io`, replacing `username` with my GitHub username.
3. Set the repository to Public and initialize it with a README.


### 2. Add Resume to the Repository

1. Clone my new repository to my local machine using Git.
2. Add my Markdown-formatted resume (`index.md`) to the repository.
3. Commit and push the changes back to GitHub.

### 3. Enable GitHub Pages

1. In my repository settings, find the "Pages" section.
2. Select my main branch as the source.
3. Save, and my resume is now live at `https://username.github.io`.


## Jekyll

1. go to [website](https://pages.github.com/themes/) choose one theme
   
2. in the theme there will be a usage of this theme
   
3. copy this usage to the `_config.yml` file
   
4. and try to run your github page website 


## More Resources

- [Markdown Tutorial](https://www.markdowntutorial.com/)
- [GitHub Pages Documentation](https://docs.github.com/en/pages)
- [Jekyll Themes for GitHub Pages](https://jekyllthemes.io/github-pages-themes)
- [Etter's *Modern Technical Writing*](https://www.amazon.com/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS)

## Authors and Acknowledgements

- **Author:** Yuelang Zhang
- **Acknowledgements:** Thanks to peers and mentors for guidance and feedback.

## FAQs

**Why use Markdown for a resume?**
Markdown is preferred for its simplicity, portability, and version control friendliness—key advantages highlighted by Etter for technical documents.

**Why isn't my resume appearing on GitHub Pages?**
Ensure the repository is named correctly (`username.github.io`), and GitHub Pages is enabled in my repository settings. It may take a few minutes for changes to go live.
