# Yong Chen Lab | Department of Biological and Biomedical Sciences | Rowan University | Onboarding Material

**We are currently recruiting new students! Contact Dr. Chen directly at chenyong@rowan.edu for more information.**
Students who wish to join the lab full time should have prior programming/coding experience. We work mostly in Python and R, but occasionally use C++. Students are welcome to rotate in the lab to learn these skills. 


This repository is designed to help onboard new students in the lab or to provide foundational skills for rotating students. All materials are publily available. Please remember! You can't learn programming overnight! Be patient with yourself. Try to work through the problems you encounter. You have to struggle with the issues yourself so you learn how to resolve them yourself! If you get stuck on something for more than two days, ask for help! 

## Common abbreviations/terms
- OS: Operating System
- sc: single-cell
- GO: gene ontology
- ATAC-seq: assay used to detect "open" regions of chromatin
- RNA-seq: assay used to detect gene expression
- Hi-C: assay used to detect interactions between chromatin regions
- WMB: whole mouse brain
- MM: Multiple myeloma (cancer of bone and plasma)
- GWAS: Genome wide association studies 

### Linux OS 
1. MIT offers a gameified way to learn basic Linux commands! Linux can have "point-and-click", but you need to be able to use the command line as well. Play through [MIT Terminus](https://web.mit.edu/mprat/Public/web/Terminus/Web/main.html) to learn how to navigate Linux OS. 
2. After, you can work through the more advanced tutorial at [LinuxCommand.org](https://linuxcommand.org/index.php). This tutorial will define commonly used words when discussing Linux systems. (e.g. terminal, shell script, root, user, etc.). One important command is awk. The tutorial information on using awk and "regular expressions" is available [here](https://linuxcommand.org/lc3_adv_awk.php).

### Python 
1. Basic tutorials. There are a TON of "learn Python" courses/websites online. If you are entirely new to programming/coding, we recommend this course by [Codeacademy](https://www.codecademy.com/learn/learn-python-3). If you have prior experience or learned a different language, there is a simplified version availale through [w3schools](https://www.w3schools.com/python/python_intro.asp) which will allow you to skip topics you are familiar with. If you prefer textbook style rather than a course, you can start with [this](https://learnpythontherightway.com/#read), Chapters 1-20. 
2. After completing the basic tutorials, there are a few libraries that are important for our work. Work through the tutorials on [file handling](https://www.w3schools.com/python/python_file_handling.asp), the [pandas](https://www.w3schools.com/python/pandas/default.asp) module, and the [sciPy](https://www.w3schools.com/python/scipy/scipy_intro.php) library. 
3. Visualizing data. Making nice figures is a learned skill! In Python, the matplotlib and seaborn libraries are the choice for visualization. Work through the [matplotlib tutorial](https://www.w3schools.com/python/matplotlib_intro.asp) and the [seaborn tutorial](https://seaborn.pydata.org/tutorial/introduction.html) 
4. Practice skills with a bioinformatics question. At this point, you can attempt the [scanpy tutorial](https://scanpy.readthedocs.io/en/stable/tutorials/index.html) with real biological data to practice your skills.
5. Practice reading scripts. We work collaboratively in the lab, so you will need to be able to read code written by others in addition to writing your own. Please see [ReadAPythonScript.txt](./PythonSupplementals/ReadAPythonScript.txt).
6. If you only need to learn Python, you can skip the R tutorials. 

### R 
1. Basic tutorials. There are a TON of "learn R" courses/websites online. If you are entirely new to programming/coding, we recommend this course by [Codeacademy](https://www.codecademy.com/learn/learn-r). If you have prior experience, you can use the tutorial by [w3schools](https://www.w3schools.com/R/) which will allow you to skip topics you are familiar with. If you prefer textbook style rather than a course, you can start with [this](https://bookdown.org/yih_huynh/Guide-to-R-Book/intro.html), Chapters 2 & 3. 
2. Tidyverse/tidyr is the equivalent to pandas in Python. A tutorial for tidyverse can be found [here](https://bookdown.org/yih_huynh/Guide-to-R-Book/tidyverse.html), Chapters 4-7.
3. ggplot2 is the equivalent to matplotlib + seaborn in Python. A tutorial for plotting in R can be found [here](https://bookdown.org/yih_huynh/Guide-to-R-Book/introduction-to-graphing.html), Chapters 8-12.
4. Seurat is the equivalent of scanpy in Python. It is time to practice your skills with a bioinformatics question. At this point, you can attempt the [Seurat tutorial](https://satijalab.org/seurat/articles/pbmc3k_tutorial.html) with real biological data! 
5. Practice reading scripts. We work collaboratively in the lab, so you will need to be able to read code written by others in addition to writing your own. Please see [ReadARScript.txt](./RSupplementals/ReadARScript.txt)

### Psuedocode 
Pseudocode is VERY useful for laying out the logic of a large project. Yong's first PhD student developed a pseudocode lesson as part of her PhD training. Under the [Pseudocode](./Pseudocode) folder, there are two documents. 
- [1S](./Pseudocode/1S.pdf): The Good Pseudocode Checklist - Helpful to learn what the requirements of good pseudocode are
- [2S](./Pseudocode/2S.pdf): Practice Correcting Pseudocode - Practice correcting pseudocode with the good pseudocode checklist. Also provides biological background information.


An answer key is provided in the [AnswerKeys](./Pseudocode/AnswerKey) folder. 


### Write your "first" bioinformatics program
Okay. Maybe it isn't your first bioinformatics program, but it's the first assignment for the lab. 
