---
permalink: /
title: "Lichen Li (李莅琛)"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Welcome to my homepage!

I am Lichen Li, a senior undergraduate at [Yuanpei College](https://yuanpei.pku.edu.cn/en/aboutyuanpei/collegeprofile/index.htm), [Peking University](https://english.pku.edu.cn), majoring in Data Science and Big Data Technology with a minor in Philosophy.
My research is driven by a philosophical curiosity rooted in epistemology，about how AI systems integrate perception and language to gain knowledge. I focus on **Multimodal AI, AI Reasoning and embodied AI**, with a interest in building efficient and interpretable systems. 
My long-term goal is to develop AI technologies that not only advance technical capabilities but also enhance access to quality knowledge and promote equity for underserved communities.

I am currently looking for Ph.D. opportunities starting in Fall 2026.


Research Experience
======
**Reward Hacking Monitoring in Reasoning LLMs** | *University of California, Los Angeles (Remote)*
*Research Assistant | Advisors: Prof. Cho-Jui Hsieh & Prof. Tianyi Zhou (UMD)*
*Jul 2025 - Present*
* Leading a project to address the **"dual validity deficit"** in existing monitors, which often rely on ineffective synthetic trajectories or indirect definitions.
* Proposed a novel framework to induce, amplify, and trace **genuine, in-the-wild hacking behaviors** during both inference and training phases.
* Developing a robust monitor to improve the reliability of reasoning systems, aiming to mitigate the risk of misleading users and deepening informational inequality. (Planned submission to ACL 2026).

**Efficient Multimodal LLMs (Visual Token Pruning)** | *Peking University*
*Research Assistant | Advisor: Prof. Shanghang Zhang*
*Mar 2025 - Jun 2025*
* Co-developed **CDPruner**, a training-free, model-agnostic method that reformulates token pruning as **conditional diversity maximization**.
* Addressed the NP-hard subset selection problem by applying **Determinantal Point Processes (DPP)** with a greedy approximation algorithm and Cholesky decomposition, reducing complexity to polynomial time.
* Engineered a modular framework to unify **heterogeneous codebases**, enabling rigorous benchmarking across diverse baselines.
* **Publication:** *Beyond Attention or Similarity: Maximizing Conditional Diversity for Token Pruning in MLLMs*, **NeurIPS 2025**.

**Vertical Federated Learning under Privacy Constraints** | *Johns Hopkins University (Remote)*
*Research Assistant | Advisor: Prof. Yinzhi Cao*
*Jun 2024 - Aug 2024*
* Led a project adapting optimization techniques from Horizontal to Vertical Federated Learning (VFL).
* Developed a server-side transformation layer to enhance model performance under **Differential Privacy (DP)** constraints.
* Refined open-source VFL frameworks to improve stability and training efficiency.

**Parameter-Efficient Fine-Tuning (PEFT) for Vision Transformers** | *Peking University*
*Research Assistant | Advisor: Prof. Shanghang Zhang*
*Mar 2024 - Jun 2024*
* Conducted a comprehensive comparative study of representative PEFT methods, including **VPT, AdaptFormer, LoRA, and SSF**.
* Analyzed the theoretical foundations and empirically evaluated the applicability of these methods across various scenarios, motivated by the need for cost-effective model adaptation.

Education
======
**Peking University** | Beijing, China
*B.S. in Data Science and Big Data Technology, Minor in Philosophy*
*Sep 2021 - Jun 2026 (Expected)*
* Honors: Peking University Merit Student (2025)

Hobbies & Interests
======
* Reading, Photography, Running, Cycling, Singing.



A data-driven personal website
======
Like many other Jekyll-based GitHub Pages templates, Academic Pages makes you separate the website's content from its form. The content & metadata of your website are in structured Markdown files, while various other files constitute the theme, specifying how to transform that content & metadata into HTML pages. You keep these various Markdown (.md), YAML (.yml), HTML, and CSS files in a public GitHub repository. Each time you commit and push an update to the repository, the [GitHub pages](https://pages.github.com/) service creates static HTML pages based on these files, which are hosted on GitHub's servers free of charge.

Many of the features of dynamic content management systems (like Wordpress) can be achieved in this fashion, using a fraction of the computational resources and with far less vulnerability to hacking and DDoSing. You can also modify the theme to your heart's content without touching the content of your site. If you get to a point where you've broken something in Jekyll/HTML/CSS beyond repair, your Markdown files describing your talks, publications, etc. are safe. You can rollback the changes or even delete the repository and start over - just be sure to save the Markdown files! You can also write scripts that process the structured data on the site, such as [this one](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb) that analyzes metadata in pages about talks to display [a map of every location you've given a talk](https://academicpages.github.io/talkmap.html).

For those users that need more advanced functionality, the template also supports the following popular tools:
- [MathJax](https://www.mathjax.org/) for mathematical equations
- [Mermaid](https://mermaid.js.org/) for diagraming
- [Plotly](https://plotly.com/javascript/) for plotting

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
