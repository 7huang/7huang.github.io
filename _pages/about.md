---
permalink: /
title: "Hello！"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

嗨～欢迎光临我的世界！这里是我的个人博物馆～工作干货、生活碎片、技能树全都在这里，滑动鼠标就能解锁我的多维人生！
Welcome to my world! This is my personal museum ~ work, life fragments, skill trees are all here, slide the mouse to unlock my multi-dimensional life!

关于我
======
我出生在广西北海，后来辗转成都、西安、珠海等地。2023年我从西安交通大学毕业，获得工程学士学位。2024年开始在西安交通大学鹿又水团队担任科研助理至今。预计将于2025年8月前往澳门大学攻读MSCIRAS。
I was born in Beihai, Guangxi, and later moved through various cities including Chengdu, Xi'an, and Zhuhai. After graduating from Xi'an Jiaotong University with a Bachelor of Engineering (BEng) in 2023, I joined Professor Lu Youshui's research team at the same university as a Research Assistant in 2024, where I continue to work. I am expected to commence my MSc in Intelligent Robotics and Autonomous Systems (MSCIRAS) at the University of Macau in August 2025.

我是一名电子爱好者，在本科期间学习了许多有关电子技术的知识，擅长使用各种嵌入式芯片。在担任研究助理期间，我参与研发了铁路自动化维护装备，主要负责嵌入式软件开发、机械结构设计等工作。
I am an electronics enthusiast, and I learned a lot about electronics during my undergraduate studies, specializing in the use of various embedded chips. During my time as a research assistant, I participated in the research and development of automated railroad maintenance equipment, mainly responsible for embedded software development and mechanical structure design.

工作之余我喜欢健身、旅行、摄影，偶尔会玩电子游戏。
Beyond working, I enjoy fitness training, traveling, photography, and occasionally playing video games.

News
======
1. Register a GitHub account if you don't have one and confirm your e-mail (required!)
1. Fork [this template](https://github.com/academicpages/academicpages.github.io) by clicking the "Use this template" button in the top right. 
1. Go to the repository's settings (rightmost item in the tabs that start with "Code", should be below "Unwatch"). Rename the repository "[your GitHub username].github.io", which will also be your website's URL.
1. Set site-wide configuration and create content & metadata (see below -- also see [this set of diffs](http://archive.is/3TPas) showing what files were changed to set up [an example site](https://getorg-testacct.github.io) for a user with the username "getorg-testacct")
1. Upload any files (like PDFs, .zip files, etc.) to the files/ directory. They will appear at https://[your GitHub username].github.io/files/example.pdf.  
1. Check status by going to the repository settings, in the "GitHub pages" section

Site-wide configuration
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

Create content & metadata
------
For site content, there is one markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

The repository includes [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the Academic Pages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a markdown file for a talk
![Editing a markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring Academic Pages can be found in [the guide](https://academicpages.github.io/markdown/), the [growing wiki](https://github.com/academicpages/academicpages.github.io/wiki), and you can always [ask a question on GitHub](https://github.com/academicpages/academicpages.github.io/discussions). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
