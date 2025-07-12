---
permalink: /
title: "Welcome to the Microbial Communities for Health and Sustainability Research Group!"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---


**Research Themes**

**Engineering Microbial Communities for Human Microbiome Therapies:** The gut microbiome is a highly diverse ecosystem that varies significantly between individuals. A loss of diversity and integrity in the microbiome is a key factor in microbiome-related diseases, but the underlying mechanisms are not fully understood. My research group applies chemical and biological engineering principles to better understand this complex system and develop microbial therapies poised to play a major role in the pharmaceutical and biomedical industries.

To study microbial effects, we recapitulate the gut microenvironment using gut microbiome-on-a-chip systems. These microfluidic devices simulate fluid flow, oxygenation, peristalsis, and host-microbe interactions at the microbial scale. Integrated with advanced microscopy and analytics, these systems allow us to investigate microbial community composition, structural properties, and the effects of perturbations.

Our approach provides a foundation for linking an individual’s microbiome to their health through precision medicine. We explore microbial therapies, including prebiotics, probiotics, and microbial transplants, to develop preventive and therapeutic strategies for diseases like cancer, inflammatory bowel disease, and non-alcoholic fatty liver disease, all of which are strongly linked to microbiome imbalances.


![Alt Text]({{ site.baseurl }}/images/gutmicrobiome.jpg)

The use of microfluid system allows to unqiutely capture the physics of microbial communities. For example the below study from Valiei et al. Lab on a Chip 12 (24), 5133-5137 demonstrates the formation of biofilm streamers.

![Alt Text]({{ site.baseurl }}/images/rect6323.png)

**Addressing the Emerging Issue of Antibiotic Resistance:** Antimicrobial resistance (AMR) is projected to be a major healthcare challenge in the next 50 years. While resistance mechanisms in single species are well-understood, microbial community responses to antibiotics are less predictable. Bacteria in biofilms are protected from antibiotics and engage in multispecies interactions that promote survival, while horizontal gene transfer spreads resistance.

A key research focus of our group is understanding antibiotic resistance dynamics in microbial communities. Using microfluidic devices, we control stressors and predict microbial responses. Our goal is to develop targeted antimicrobial strategies, including formulations that selectively target harmful organisms. For cases requiring complete eradication, such as implant-associated infections, we employ nanotextured surfaces to induce mechanical microbial rupture. By integrating chemical and physical approaches, we aim to enhance antimicrobial effectiveness.

The below image is from a study conducted by Valiei* & Lin* who demonstrated a new physics by which surface tension can kill bacteria on nanopillars.

![Alt Text]({{ site.baseurl }}/images/rect604.png)



**Development of Microbial Formulations for Environmental Applications and Bioprocesses:** Advances in sequencing technologies are revolutionizing microbial applications, enabling new approaches to environmental and bioprocess development. As the circular economy grows, bioprocessing and waste management efforts are critical. However, microbial identification alone is not enough; we must also understand their interactions within communities and ecosystems.

Microbial communities thrive on cooperation, which can be leveraged to improve processes like bioremediation. Traditional bioremediation design methods often rely on trial and error, leading to inefficiencies due to microbial task redundancy and competition. Many industrial bioprocesses use single-species formulations, which require extensive strain modifications.

In our lab we aim to enhance bioprocesses by engineering microbial communities. By pairing strains with complementary functions and understanding their metabolic interactions, we can optimize efficiency and predict outcomes. We  design scalable, efficient processes, considering factors like microbial interactions, timing, and process design. This approach enables the development of advanced bioprocesses and bioremediation systems


![Alt Text]({{ site.baseurl }}/images/soil.jpg)



<!-- ![Microbiome Applications](/images/images.jpeg){width=300px style="float: right;"}-->











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
