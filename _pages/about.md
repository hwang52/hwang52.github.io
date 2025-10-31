---
permalink: /
title: "Huan Wang"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Short Bio
---
Huan Wang (Chinese 王欢) is a second-year Ph.D. student in the School of Computing and Information Technology at the University of Wollongong, advised by Prof. [Jun Shen](https://scholars.uow.edu.au/jun-shen) and Prof. [Jun Yan](https://scholars.uow.edu.au/jun-yan). 
Previously, I received my master at Xidian University in 2023, advised by Prof. [Lijuan Wang](https://web.xidian.edu.cn/ljwang/index.html).

My research focuses on Federated Learning and Visual Anomaly Detection.

(**Recent News**): Recently, I will soon be going to Singapore Management University (SMU) for a 12-month full-time research visit, advised by Prof. [Guansong Pang](https://sites.google.com/site/gspangsite).

Selected Publications
======
- FedDifRC: Unlocking the Potential of Text-to-Image Diffusion Models in Heterogeneous Federated Learning \\
  **Huan Wang**, Haoran Li, Huaming Chen, Jun Yan, Jiahua Shi, Jun Shen \\
  IEEE/CVF International Conference on Computer Vision (ICCV), CCF-A, 2025. \\
  [[Paper](https://openaccess.thecvf.com/content/ICCV2025/html/Wang_FedDifRC_Unlocking_the_Potential_of_Text-to-Image_Diffusion_Models_in_Heterogeneous_ICCV_2025_paper.html)] [[Code](https://github.com/hwang52/FedDifRC)]
- FedSC: Federated Learning with Semantic-Aware Collaboration \\
  **Huan Wang**, Haoran Li, Huaming Chen, Jun Yan, Jiahua Shi, Jun Shen \\
  Proceedings of the 31st ACM SIGKDD Conference on Knowledge Discovery and Data Mining, CCF-A, 2025. \\
  [[Paper](https://ieeexplore.ieee.org/abstract/document/11169609/)] [[Code](https://github.com/hwang52/FedSKC)]
- FedSKC: Federated Learning with Non-IID Data via Structural Knowledge Collaboration \\
  **Huan Wang**, Haoran Li, Huaming Chen, Jun Yan, Lijuan Wang, Jiahua Shi, Shiping Chen, Jun Shen \\
  IEEE International Conference on Web Services, CCF-B, 2025. \\
  [[Paper](https://dl.acm.org/doi/abs/10.1145/3711896.3736957)] [[Code](https://github.com/hwang52/FedSC)]
- FedKG: Model-optimized Federated Learning for Local Client Training with Non-IID Data \\
  **Huan Wang**, Lijuan Wang \\
  IEEE International Conference on Multimedia and Expo, CCF-B, 2022. \\
  [[Paper](https://ieeexplore.ieee.org/abstract/document/9816323/)] [[Code](https://github.com/hwang52)]
  
Getting started
======
1. Register a GitHub account if you don't have one and confirm your e-mail (required!)
1. Fork [this template](https://github.com/academicpages/academicpages.github.io) by clicking the "Use this template" button in the top right. 
1. Go to the repository's settings (rightmost item in the tabs that start with "Code", should be below "Unwatch"). Rename the repository "[your GitHub username].github.io", which will also be your website's URL.
1. Set site-wide configuration and create content & metadata (see below -- also see [this set of diffs](https://archive.is/3TPas) showing what files were changed to set up [an example site](https://getorg-testacct.github.io) for a user with the username "getorg-testacct")
1. Upload any files (like PDFs, .zip files, etc.) to the files/ directory. They will appear at https://[your GitHub username].github.io/files/example.pdf.  
1. Check status by going to the repository settings, in the "GitHub pages" section

Site-wide configuration
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

Create content & metadata
------
For site content, there is one Markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a Markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each Markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

The repository includes [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual Markdown files that will be properly formatted for the Academic Pages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the Markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and Markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a Markdown file for a talk
![Editing a Markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring Academic Pages can be found in [the guide](https://academicpages.github.io/markdown/), the [growing wiki](https://github.com/academicpages/academicpages.github.io/wiki), and you can always [ask a question on GitHub](https://github.com/academicpages/academicpages.github.io/discussions). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
