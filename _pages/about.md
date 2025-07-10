---
permalink: /
title: "Welcome to my personal academic websites"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

个人介绍
======

我是[中国科学技术大学](https://www.ustc.edu.cn/)的一名大三本科生，目前就读于人工智能英才班。

我的研究兴趣：






项目介绍
======

1.基于OpenMv的智能识别机械车 
------
队友：刘玥含、周毅涵、周创信、曾熙宇

·团队从零搭建了一个自动驾驶、智能识别机械车，负责机械车的嵌入式视觉控制系统架构设计，实现STM32主控板与OpenMV视觉计算板的通信与算法部署

·负责视觉算法设计，基于OpenMV开发物体分割与目标检测算法，提升在不同光照与背景噪声影响下的目标识别鲁棒性，并将物体分割、目标检测与参考背景定位任务集成为视觉流水线

·建立基于PID的机械臂轨迹规划算法，完成图像识别到动作执行的闭环控制，实现了彩色方块的识别、定位、抓取、存储与定向投掷

·[技术文档](https://rec.ustc.edu.cn/share/a9fdd120-361a-11f0-b218-7f128ac1897e), 密码：cj70

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
