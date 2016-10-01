
![<img src="https://raw.githubusercontent.com/ucb-stat159/stat159-fall-2016/master/projects/proj01/images/stat159-logo.png">](https://raw.githubusercontent.com/ucb-stat159/stat159-fall-2016/master/projects/proj01/images/stat159-logo.png)
# Stat 159 Project 1

## Abstract
In this project, I will summary the main things we learn in the course so far and my personal experience of study. Topics include but are not limited to the use of Makefile, Git, Github, pandoc and Markdown. The project will contain four parts: the abstract part, introduction part, discussion part and conclusion part. With these parts combined, we will be able to explore some foudation knowledge and basics of reproducible data science research and workflow.  

![<img src="http://www.phdcomics.com/comics/archive/phd053104s.gif">](http://www.phdcomics.com/comics/archive/phd053104s.gif)

This is a typical data analysis cycle which contains getting raw unstructured datasets, data cleaning and processment, exploratory data analysis, modeling and tuning parameters, visualization of results, report and presentation. 

In order to acheive this level of data analysis, we need to cooperate with other people and learn how to do reproducible research that allow other people to reproduce the work and work on the subject. In the later sections of the project, I will introduce some basics of reproducible research cycle.


## Introduction

Reproducible Research

* Definition: is the concept that data analysis, or scientific researches, are published with their data and software code so that others may verify the findings and build upon them

* Types of Reproducible Research
	* Computational Reproduibility: detailed information is provided about code, software and implementation details
	* Empirical Reproducibility: when detailed information is provided about non-computational empirical scientific experiments and observations.
	* Statistical Reproducibility: when detailed information is provided about the choice of statistical tests, model parameters, threshold values and sampling procedures

* Useful tools for reproducible research
	* Literate computing, authoring, and publishing. These tools enable writing and publishing self-contained documents that include narrative and code used to generate both text and graphical results. These tools include Markdown, pandocs, Latex and IPython Notebook.
	* Version Control: These tools enable you to keep a record of file changes over time, so we can access specific versions of record. The most common tools used for version control is git combined with online services like Github and Bitbucket.
	* Automation: Several Unix tools are useful for streamlined automation and documentation of the research process,including editing files, compling documents and recording workflow. Common tools are GNU make and shell programs. 


In this project, I will introduce the definition and applications of some of the most common tools mentioned above, including Makefile, Git, Github, pandoc, and Markdown, and my own experience of using them.

## Discussion

Tools for reproducible research and their roles


* Makefile
	* Definition: GNU Make, commonly known as make, is a Unix tool that is part of the GNU Project. Make is a "tool which controls the generation of executables and other non-source files of a program from the program's source files."
	* Role in the workflow: is part of the Automation tool of reproducible research, and it only executes the thing that are changed and hence is able to track timestamps.

![<img src="https://raw.githubusercontent.com/ucb-stat159/stat159-fall-2016/master/projects/proj01/images/git-logo.png">](https://raw.githubusercontent.com/ucb-stat159/stat159-fall-2016/master/projects/proj01/images/git-logo.png)

* Git
	* Definition: Git is a free open source distributed version control system used to handle variety of projects with speed and efficiency.
	* Role in the workflow: is part of the Versino control tool of reproducible research, and it keeps track of changes over time, allows to track progress, access earlier versions, and collaborate with others.

![<img src="https://raw.githubusercontent.com/ucb-stat159/stat159-fall-2016/master/projects/proj01/images/github-logo.png">](https://raw.githubusercontent.com/ucb-stat159/stat159-fall-2016/master/projects/proj01/images/github-logo.png)


* Github
	* Definition: GitHub is a web-based Git repository hosting service, which offers the distributed version control and source code management functionality of Git and also its own features. It provides access control and several collaboration features such as bug tracking, feature requests, task management, and wikis for every project.
	* Role in the workflow: is part of the Versino control tool of reproducible research, and it is a web-based Git repository which functions similar as Git in version control of projects.

![<img src="https://raw.githubusercontent.com/ucb-stat159/stat159-fall-2016/master/projects/proj01/images/pandoc-logo.png">](https://raw.githubusercontent.com/ucb-stat159/stat159-fall-2016/master/projects/proj01/images/pandoc-logo.png)

* pandoc
	* Definition: Pandoc is a free and open-source software document converter, which is often used as a writing tool for publishing workflows and convert versions between Markdown, LaTex and html.
	* Role in the workflow: is part of the Literate computing, authoring, and publishing tool of reproducible research, and it is usually used for converting files to different versions such as Markdown, Latex, and html, and publishing workflows.

![<img src="https://raw.githubusercontent.com/ucb-stat159/stat159-fall-2016/master/projects/proj01/images/markdown-logo.png">](https://raw.githubusercontent.com/ucb-stat159/stat159-fall-2016/master/projects/proj01/images/markdown-logo.png)

* Markdown
	* Definition: Markdown is a common way to write content for the web, which uses plain text formatting so that it can be converted to html or other formats.
	* Role in the workflow: is part of the Literate computing, authoring, and publishing tool of reproducible research, and serves as a converter to different formats.

Personal Experience of learning

Through the courses so far, I have learned the foundation tools for reproducible research such as version control tools and automation tools. The project is a great opportunity to review the concepts learned in lecture and use them in practice, which I found really engaging! Since the techniques used for the project are all covered in lectures and labs, it isn't tricky and definitely doable and useful. The hardest part for me personally is the Makefile and pandocs part since I am not really familiar with its syntax and use, while Git and Markdown are relatively easier for me since I have worked with them before and am more familiar with the subjects. I worked individually for this project and it takes me about seven to eight hours including reviewing concepts and finding resources. Overall, the project serves as a great chance to review the concepts I learned so far and I find it really interesting.


## Conclusion

In this project, I summarized the main workflow of a reproducible research which is important for modern data analysis. In the introduction and discussion sections, I introduced multiple useful tools for reproducible research in aspects of version control, literature computing, authoring and publishing and automation, and specified the concepts and applicaitons of Makefile, Git, Github, pandoc, and Markdown. Through this project, we can review the core concepts of tools of reproducible research and their applications.


### References
_Lecture slides of Stat 159_

_http://ropensci.github.io/reproducibility-guide/sections/introduction/_

_http://pandoc.org/_

_https://en.wikipedia.org/wiki/GitHub_

