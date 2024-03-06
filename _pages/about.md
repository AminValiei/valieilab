---
permalink: /
title: "Welcome to the Microbial Communities and Microbiome (MCML) Research Group!"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

The study of the microbial world, once shrouded in mystery, has been undergoing a transformative revolution in recent years, driven by advancements in experimental and computational approaches. Our lab actively participates in emerging areas in both landscapes. We utilize micro- and nanotechnology for in-vitro recapitulation of the cellular environment. We use cutting-edge computational approaches to analyze microbial behaviors from a combined engineering-biology perspective. We finally use in-vivo models to test our hypotheses for medical therapies and use large scale setups to test solutions for industrial applications.

**Micro- and nanodevices for investigation of microbial systems** The recent revolution of next-generation sequencing has enabled the characterization of microbial compositions with unprecedentedly high throughput. However, the large amount of data obtained through this method fails to capture the spatiotemporal attributes of microbial communities. A central emphasis of our research involves the development of micro-engineered devices, termed "microbiome-on-a-chip" or "biofilm-on-a-chip",  to faithfully emulate the microenvironment of microbial communities. These devices enable the creation of physicochemical cues at a length scale comparable to the size of microbes. Considering the rapid advancements in analytical and microscopical techniques, it is possible to monitor and investigate microbial activities at cellular and subcellular levels with unprecedented resolution. With this approach, it is possible to dissect the microbial complexity and find the functional roles of each phenotype or genotype. This uniquely enables optimizing microbial systems for myriad environmental, medical, and industrial applications that rely on microbial communities. In addition, micro- and nanosystems can be used to develop innovative functional materials. For example, microbial interactions with nanopillar patterned objects cause deactivation whihc provides a novel way to develop antimicrobial surfaces.

**Computational modeling**: In addition to experimental investigations, computational tools are crucial for comprehending microbial systems. An exceptional approach for deriving the emergent properties of complex systems (e.g., spatiotemporal community structures) from deterministic or stochastic rules governing agents (e.g., each bacteria) is agent-based modeling. Agent-based modeling is suitable for modeling microbial communities, as microbes have shown a variety of social behaviors. For example, in metabolism, microbes are known to form cross-feeding networks that help them degrade complex biochemicals. Bacteria also interact through signaling means such as quorum sensing mechanisms. In these systems, community-level behavior is obtained through the integration of individual interactions and is sometimes not easy to dissect. In fact, without computational approaches to capture these complex systems, it is difficult to generalize the results and make new predictions about community properties and functions. Thus, while progressing on the experimental front, we take advantage of powerful computational approaches to investigate and model microbial systems. Beyond agent-based modeling, we exploit recent progress in artificial intelligence, machine learning, and bioinformatic tools.  

**Hypothesis-driven discovery of microbial solutions**: Microbial communities have extensive applications in healthcare and industry. In agriculture, microbes are essential elements in nutrient cycling and plant health. Our body is also home to an extremely diverse microbial community called the human microbiome. There is strong evidence that the human microbiome plays a critical role in our health. The disruption of the microbiome, known as dysbiosis, is a precursor to various diseases, from gastrointestinal disorders to cardiovascular diseases, and even impacts brain function and human psychology. In all these systems, the performance of the microbiome is essential to the functionality of the entire system. By developing in-vitro and in-silico models, it is possible to gain a bottom-up approach to these interactions and devise new solutions (e.g., new therapeutic techniques). Ultimately, these solutions must be tested in real life. To this end, we use various in vivo models for evaluating the efficacy of microbial therapies we develop. We also test the scalability of our solutions for environmental and industrial applications in the lab by building appropriate models.









<!-- A data-driven personal website
======
Like many other Jekyll-based GitHub Pages templates, academicpages makes you separate the website's content from its form. The content & metadata of your website are in structured markdown files, while various other files constitute the theme, specifying how to transform that content & metadata into HTML pages. You keep these various markdown (.md), YAML (.yml), HTML, and CSS files in a public GitHub repository. Each time you commit and push an update to the repository, the [GitHub pages](https://pages.github.com/) service creates static HTML pages based on these files, which are hosted on GitHub's servers free of charge.

Many of the features of dynamic content management systems (like Wordpress) can be achieved in this fashion, using a fraction of the computational resources and with far less vulnerability to hacking and DDoSing. You can also modify the theme to your heart's content without touching the content of your site. If you get to a point where you've broken something in Jekyll/HTML/CSS beyond repair, your markdown files describing your talks, publications, etc. are safe. You can rollback the changes or even delete the repository and start over -- just be sure to save the markdown files! Finally, you can also write scripts that process the structured data on the site, such as [this one](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb) that analyzes metadata in pages about talks to display [a map of every location you've given a talk](https://academicpages.github.io/talkmap.html).

Getting started
======
1. Register a GitHub account if you don't have one and confirm your e-mail (required!)
1. Fork [this repository](https://github.com/academicpages/academicpages.github.io) by clicking the "fork" button in the top right. 
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
More info about configuring academicpages can be found in [the guide](https://academicpages.github.io/markdown/). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.-->
