---
permalink: /
title: "About"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Welcome to my website! I am a third year PhD student in Decision Sciences at Fuqua School of Business, Duke University. I am very fortunate to be advised by [Prof. alexandre belloni](https://faculty.fuqua.duke.edu/~abn5/belloni-index.html?_ga=2.245151173.1198594769.1596235423-1333425513.1594055969). Previously, I obtained my master in [Statistics](http://www.bu.edu/stat/) at Boston University. During the time at BU, it is my pleasure to be advised by [Prof. Daniel Sussman](http://math.bu.edu/people/sussman/) and [Prof. Konstantinos Spiliopoulos](http://math.bu.edu/people/kspiliop/) to explore graph matching in network and system risk. Prior to my master, I received my Bachlor degrees in International Trade and Computer Science in [Guangdong University of Foreign Studies](https://iie-en.gdufs.edu.cn). Before going to college, I spent three amazing years at Guiyang No.1 high school. 

Research Interests
======
My research interest lies in empirical process, methodology and applications on network analysis and causal inference. In particular, I am interested in the convergence rate of error measures for machine learning algortihms by using tools in empirical process. 

I am currently working on developing methodology for estimating treatment effect by matching method under network interference with [Prof. alexandre belloni](https://faculty.fuqua.duke.edu/~abn5/belloni-index.html?_ga=2.245151173.1198594769.1596235423-1333425513.1594055969) and [Prof. Alexander Volfovsky](https://volfovsky.github.io). Meanwhile, I am trying to obtain estimator for the causal effect of name order on election ballot with clustered data with [Prof. Alessandro Arlotto](http://people.duke.edu/~aa249/?_ga=2.206868819.1198594769.1596235423-1333425513.1594055969).

What's new 
======
* 11/08/2020: Presentation "Uniform Regret bound for Quantile Regression Tree Process in Online learning" in INFORMS.

* Fall 2020: Teaching EGRMGMT 580 “Decision Models". 

* 08/06/2020: Presentation "Uniform Regret bound for Quantile Regression Tree Process in Online learning" in session "Modern Machine Learning" in JSM. 

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

I have also created [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the academicpages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a markdown file for a talk
![Editing a markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring academicpages can be found in [the guide](https://academicpages.github.io/markdown/). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
