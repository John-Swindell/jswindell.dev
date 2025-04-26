# John Swindell's Portfolio Website Source

This repository contains the source code for my personal portfolio website, built using the Hugo SSG.

**Live Site:** [**https://jswindell.dev**](https://jswindell.dev)

## Overview

This site serves as my personal portfolio, showcasing my projects, experience, skills, and academic background as a Computer Science student at SNHU.

## Technology Stack

* **Static Site Generator:** [Hugo](https://gohugo.io/) (v0.147.0+ used locally during development)
* **Theme:** Based on [hugo-profile](https://github.com/gurusabarish/hugo-profile) by Gurusabarish (This repository is a fork). Modifications and content are my own.
* **Deployment:** Hosted on [Cloudflare Pages](https://pages.cloudflare.com/), automatically deployed from the `main` branch.

## Local Development

To run this site locally (requires Hugo extended version installed):

1.  Clone this repository:
    ```bash
    git clone [https://github.com/John-Swindell/jswindell.dev.git](https://github.com/John-Swindell/jswindell.dev.git)
    cd jswindell.dev
    ```
2.  Initialize the theme submodule:
    ```bash
    git submodule update --init --recursive
    ```
3.  Run the Hugo development server:
    ```bash
    hugo server -D
    ```
4.  Open `http://localhost:1313` in your browser.

## Contact

You can reach me via [LinkedIn](https://www.linkedin.com/in/john-swindell/) or email at `john@jswindell.dev`.
