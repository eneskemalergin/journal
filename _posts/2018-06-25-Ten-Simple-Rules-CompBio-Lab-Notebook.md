---
layout: post
tags: bioinformatics ten-simple-rules
date: 2018-06-25 23:00
thumbnail: http://collections.plos.org/indirect/4523f4b57993900d63d1bdacc7209db70188e3657fd2b8ca4fbfae1f59abeef143854?v=1494605129917
title: Ten Simple Rules for a Computational Biologist's Laboratory Notebook
published: true
---

I will be starting my journal blog with this short article which is one of the many great short articles under Ten Simple Rules series from PLOS journals. I might add the highlights and notes from those articles since they are very concise and informative. This particular article however will be great start for this blog because what I am trying to do here is kind of under the couple of the rules.

**Author:** Santiago Schnell

**Citation:** Schnell S (2015) Ten Simple Rules for a Computational Biologist’s Laboratory Notebook. PLoS Comput Biol 11(9): e1004385. [https://doi.org/10.1371/journal.pcbi.1004385](https://doi.org/10.1371/journal.pcbi.1004385)


Even though we are computational scientists, the need of keeping a lab notebook is still valid for us. Lab notebook is not just a way to record experimental protocols, and their results, but it is an organizational tool and memory aid.

*Rule 1 - Learn Lab's Notebook Policy*
---

- Lab notebook is for record keeping, research management, protecting intellectual  property, and preventing fraud.  
- Most leading research institutions have their policies, ask your lab for the lab notebook policy. **(For my case I know that we record our progress in LabGuru.)**

> In our lab we use LabGuru, alongside with LabGuru, I document pretty much everything in jupyter notebooks, and keep them in private github repositories.

*Rule 2 - Select the Right Platform for Your Lab Notebook*
---

- Bound or stitched notebook, loose-leaf or three-ring binder notebook, or computer-based electronic notebook. **(I try to keep an electronic notebook.)**
- Electronic notebook has advantage that allows you to search easily, copy-paste figures.  
- Some laboratories are writing lab notebooks using Microsoft Word, saving as "Web Page", and automatically transfer the entries into WordPress.com blog. **(This sounds fun to do, but WordPress is old and much flexibility there. There are better alternatives like blogs powered by GitHub and articles written in markdown, like this one.)**
- Microsoft OneNote is another option of electronic notebook. **(OneNote is one tool that I am using to keep recording pretty much everything both academic and personal.)**
- Best option is electronic notebook, if write a lot of code and collect large datasets. **(I feel like for Bioinformatician electronic notebook is a must option.)**

> As I mentioned in the Rule 1, I am using couple of platforms, such as, LabGuru to store PDF copies and experiment reports, GitHub to store the versions and changes of the codes as well as the Jupyter Notebook or Rmd experiments, finally OneNote to keep meeting notes, plans, and other types of notes to take during the day.

*Rule 3 - Make Habit of Keeping Notebook Close to You*
---

- Critical thoughts are hard to keep, having notebook around all the time will give opportunity to record them too. **(Well..., this is important to make a habit)**

> One great advantage of OneNote is that it is available in my phone so the notebook is almost always with me. If my phone is not with me my laptop is with me for sure.

*Rule 4 - Record all Scientific Activities in Your Lab Notebook*
---

- Should record:  
  - every experiment,
  - every result,
  - every research meeting,
  - notes from talks/seminars/conferences,  
  - thoughts related to research problems in talks/seminars/conferences,
- Each lab notebook entry should be written immediately after the activity or work was performed.  

> This is probably the most tricky rule to keep.

*Rule 5 - Have a Same Metadata for Each Entry*
---

- Each entry should contain the date it was made, and subject of the entry.
- Titles should be short, sharp, informative, as you will use them to build table of contents for Lab Notebook. **(Making concise titles is important)**
- If using electronic lab notebook, the data and time stamps will be entered for each new subject.
- Each entry should have a brief description: **(description is also important and hard to come up)**
  - It should be short summary of your thought process that explains why this entry is important for your scientific work.  
  - It could be supported with references published in the literature, ideas learned from a research talk, or a previous model developed by your lab.
  - Never erase or destroy an entry, mistakes or errors are an important part of the scientific process too. If have a mistake don't erase it simply strikethrough and add new info next to it.

> Same metadata, or having a consise non-changing format for the entries are important for indexing. It's really hard for me to remember the format, that's why I always have a templates file in GitHub to keep my metadata templates, if I need to remind myself what was the template, template is in GitHub to check.

*Rule 6 - Keep a Record of How Every Result Was Produced*
---

- Reproducibility is gold standard of science and must be applied in every project.  
- Need to keep a record of how each result is produced in experiments, models, statistical analyses.  
- Every possible step that has little/big affect on the results should be included in steps.
- Raw data should be stored for each figure too. **(Need to find a way to link all raw data)**
- If results are obtained from mathematical model or algorithm, you need to include the equations and name and version of the algorithm or computer program, as well as the initial conditions and parameters used in the model.  
- You should also record each intermediate data, because they might reveal discrepancies with your final results. They can also help track any inconsistencies in your analysis or algorithms.
- Electronic lab notebook can be very efficient for recording data for computational approaches

> Keeping the record of all kinds of information about the experiment is easy however keeping the raw datas for each figure is will be hard, I am still looking for a way to link the raw data in figures. It needs to be private (at least until publication), fast, accessible, and preferable free.

*Rule 7 - Use Version Control for Models, Algorithms, and Computer Code*
---

- Version control systems helps you record all the versions of your frequently updated models/codes.
- Bitbucket, Git, Subversion, and Mercurial are among the most widely used version-control systems.  **(I use Git with GitHub, but for clusters Git could be used)**
- Standardized name system is important to identify the changes.
- In electronic lab notebooks can add links to each version of their scripts or programs.

> This rule is the only rule that I am doing it for many years. I've started using Git/GitHub to store versions of code and algorithms in 2013.

*Rule 8 - Make your Lab Notebook that can Serve as a Legal Record of Your Work*
---

- You can use lab notebooks to prove your ownership for ideas and results.
- From the legal point of view, you keep a lab notebook to reflect your own scientific integrity and to give others the opportunity to corroborate the results of your research.
- In electronic lab notebook, you can make it public and make more transparent to the scientific community, which will give opportunity for other scientists to learn about your research and won't do the same mistakes you do,

*Rule 9 - Create a Table of Contents for Your Lab Notebook*
---

- The idea of creating Table of Contents  is to create an index that will help people find content in your lab notebook.
- Format of table of contents should be agreed upon in your laboratory.

> This could be done by adding a contents page to OneNote, or README for GitHub and Jupyter Notebooks.

*Rule 10 - Protect Your Lab Notebook*
---

- Your lab notebook belongs to your institution, so you need to protect against compromise especially you work with confidential information.

> Everything I store, if it's related to my work in the lab. I am keeping them private repositories or in my private OneNote notebooks.


---

These are the rules to follow to keep a computational biology lab notebook. I can say that I am very good for now, however as I mentioned in little comments, I still need to improve my stystem.
