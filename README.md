# TUAN NGO's resume

This is a Resume formatted in Markdown and hosted on Github Pages using a Jekyll template

## Contents

- [Getting Started](#getting-started)
- [How to create and host a resume](#how-to-create-and-host-a-resume)

---

## Getting Started

#### Markdown:
- **Markdown** is a lightweight Markup Language that you can use to formatting components in your document.

#### Github:
- **Github** is a platform for version control and collaborations for software development using Git. It is a distributed version control and source code management functionality of **_Git_**. 
- For some of you do not know, **_Git_** is a distributed version control system for keeping track of any changes in the source code when developing software.

#### Jekyll:
- **Jekyll** is a simple static site generator.

## How to create and host a resume

1. Format your Resume using Markdown
    - Some basic Markdown properties you can use is _Headings_ (using '#' symbol), _Emphasize_ (using '*' symbol), _Italic_ (using '_' symbol) or create tables
    ``` Markdown
    ### Headings
    **emphasize**
    _italic_
    ```
    - Access this [Markdown Tutorial](https://www.markdowntutorial.com) for more basic properties of Markdown such as Links, Images, ...
    - Save your Markdown-formatted Resume as index.md (.md is a file extension for Markdown documents)

2. Place your index.md file in Github's repository
    - First, you need a **[Github account](https://github.com)**, using your student or organization emails to register a new account. Remember you will need to verify your email (Github will give you a detail instruction on how to do it)
    - Create a repository named _username_.github.io, where _username_ is your Github account's username.
    - You can use either **a terminal** or [Github Desktop application](https://desktop.github.com) to clone your _new repository_ in the folder you want to store your project on your PC. (check [this](https://docs.github.com/en/free-pro-team@latest/github/creating-cloning-and-archiving-repositories/cloning-a-repository) if you **don't know how to clone** a repository).
    - Put your Markdown-formatted Resume into the project folder, then push it to the Github repository. You can either use a terminal or the Github desktop app
    
    Terminal:

    ```bash
    git add --all
    git commit -m"initial commit"
    git push -u origin main
    ```

    Github Desktop:
    *_gif_

3. Next, you will want to choose a Jekyll template for your Github Page:
        - Go to **Settings** in your repository.
        - Inside the **Options** menu, scroll down until you see the **GitHub Pages** section.
        - Click the **Change theme** button and select your desire theme for your static page. 
            _Note_: These are the pre-built Jekyll theme that you can use. Go to the [Build Jekyll theme from scratch](#build-jekyll-theme-from-scratch) if you want to fully customize your theme.
        - Click the **Select them** button to confirm your theme.
        - After committing your Jekyll theme, there will be a new file in your repository called **_config.yml**. You can customize the chosen theme by modifying this file. Click [here](https://github.com/pages-themes/minimal/blob/master/README.md) on how to customize the **_config.yml** file of your theme.

4. Finally, go to **_username.github.io_** to view your Resume.


## Build Jekyll theme from scratch

For this project, I used a pre-build Jekyll theme called **[Minimal](https://github.com/pages-themes/minimal)**. If you want to fully create your Jekyll theme, go to [Jekyll Docs](https://jekyllrb.com/docs/).

## Author and Acknowledgments
- Tuan Ngo
- The Contributors of **Minimal** theme.

---
## FAQs
##### Why using Markdown for technical writings other than MS Word?

##### How to change my title on my static page?