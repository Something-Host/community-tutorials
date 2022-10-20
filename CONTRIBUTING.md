# Contributing Guide & Terms

## Terms of Contribution 

We define any content uploaded ('Contributions') in this repo, which is then uploaded to Something.Host ('Us', 'Our', 'Site', 'Tutorials Page') by you, the contributors ('You', 'Contributors'). All Your Contributions are subject to our [Terms of Service](https://something.host/en/legal/terms-of-service) and the following Guidelines: 
1. All Contributions must be written primirally in the English (en) AND Greek (el) language. Any other languages must be a proper translation of the English version. Refrain from using automated services like Google Translate or Microsoft Translator as those typically provide incorrect grammar or vocabulary. 
2. All Contributions must not contain any foul language, swearing or unprofessional language. 
3. Contributions that link 3rd party services may not contain any affiliate or other tracking information other than "Something.Host" or "SomethingHost" and must contain proper footnotes if otherwise. 
4. Contributions that have any asset media, must be uploaded in this GitHub repo and not use any 3rd party services like Imgur.
5. We deserve the right to reject any Contributions, edits or suggestions under Our own discretion.
6. Contributions to this repository are not to be reposted to other websites, unless permission has been explicity granted by Us. (Copyright 2022 Something.Host)

## How to Contribute

We recognize contributions in the following forms:
- Documentation pages, Tutorial pages and Guides for our community
- Improvements or bug/typo reports in the form of issues requests
- Requests and suggestions in the form of special issues 

### Contributing Documentation Pages

We use the software Wiki.js for the publication of any documents and pages. Wiki.js ('Current Software', 'Tutorial Pages') supports markdown and HTML pages. To allow easier editing and faster approval of articles, we only support markdown documents. 

1. Firstly create a new fork of this repo. 

2. To create a new page, go under the `pages` folder, choose the language and then find the category you would like. If the category does not exist, you may create one. Categories must be ONE WORD. Example "vps" or "dns". 
Create a new file with the name of the final path for the page and add the `.md` extension at the end of it. 
Example if we want the path to be `/pages/en/communications/super-awesome-guide` we will go into the **pages** folder, create the **communications** folder and name the file **super-awesome-guide.md**

Inside this file, copy paste this template and edit as required: 
```md
---
title: 
description: 
published: 1
date: 
tags: 
editor: markdown
dateCreated: 
---

# Header
Your content here
```
To explain the file, we will need to define the page information. Begin with `---` and enter the following details: 
- **title**: The title of the page (up to 255 characters, can use spaces and special characters) [displays in SEO/EMBED and top of page]
- **description**: A short description of the page (up to 255 characters, can use spaces and special characters) [displays in SEO/EMBED and below the title]
- **published**: Boolean in the form of a number for if we want the page to be available. Please use `1`
- **date**: ISO datetimestamp for the last edit of the page (example `2022-01-01T00:00:00.000Z`)
- **tags**: An array of the page tags, split by a comma (example: `tag1, tag2, tag3`)
- **editor**: The editor engine we want to use for editing this page. Please use `markdown`
- **dateCreated**: ISO datetimestamp for when the page was created (example `2022-01-01T00:00:00.000Z`)  
Close the information section with another `---` in a new line. 

Below the info section, you can input your content in markdown format!

3. Create a pull request. Explain in detail the purpose of the document and why it is useful. 
4. Turn on alerts for the pull request. One of the mainteners will add any comments or approve and merge the PR. 

⚠️ We do not have a public editor available currently. You can read the supported markdown language here: https://docs.requarks.io/editors/markdown

#### Assets

If you have any assets such as images, videos or other media that need to be displayed in a page, please insert it in the `/assets/` folder with the following name scheme: 
`<path/to/page/ASSET_<LANGUAGE>_<INC_NUMBER>.<suffix>` example: **/assets/pages/en/communications/super-awesome-guide/ASSET_01.png** or **/assets/pages/en/communications/super-awesome-guide/ASSET_45.png**

⚠️ All pages and assets must follow the naming restrictions as specified here: https://docs.requarks.io/guide/assets#naming-restrictions

### Contributing for Improvements or report bug/typos 

Create an issue and select "Improvements or Report Bug/Typo", follow the instructions in the template. 

### Requesting a suggestion 

Create an issue and select "Suggestions", follow the instructions in the template. 

## Rewards 

We offer rewards for contributing. For each Contributed page, we offer a certain amount of Something.Host credit. We also offer a small amount of credits for multiple typo or bug reports of our pages. Please create a ticket on our support area to claim your reward. In the future this process will be automated. 