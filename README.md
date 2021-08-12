# Creating-Rmarkdown-courses-to-teach-bioinformatic-analysis-pipelines


=======

# **What's the problem?**

It can be difficult for bioinformaticians to learn data processing and analyzing for different methodologies. There are often many different tools, and it is not always straightforward to determine which is the most effectively tailored to the model at hand. Despite bioinformatics being increasingly essential across the biological sciences, programming is often not adequately taught in undergraduate and graduate biology programs. Therefore, scientists in this field learn aspects of bioinformatics in a piecemeal manner, and may miss important lessons that will improve their workflow, analysis, and overall research.

# **How are we solving the problem?**

Using the existing infrastructure of LearnR, we set out to create courses to teach standard reproducible bioinformatic pipelines. Our intent is that these courses are interactive and computationally light, thus allowing users to fully understand the necessary biology and bioinformatics as they develop their skills and expand their knowledge base. The structure we used gives users the option to assess their own background understanding, and move through the courses at their own pace - they can access the provided additional resources when they need. The courses also break the pipeline into small steps while providing interactive exercises with feedback, so users do not get lost and are able to apply what they learn to their own work. 

As a proof of concept, we created a course to teach single cell RNA sequencing analysis using the Seurat package in R. 

# **What is Seurat?**

RNA sequencing (RNA-seq) is a genomic approach for the detection and quantitative analysis of messenger RNA molecules in a biological sample and is useful for studying cellular responses. Single cell RNA sequencing (scRNA-seq) permits comparison of the transcriptomes of individual cells thus allowing for transcriptional comparisons and providing information about heterogeneity within cell populations. 

Seurat is an R package designed for quality control, analysis, and exploration of scRNA-seq data.

https://genomemedicine.biomedcentral.com/articles/10.1186/s13073-017-0467-4

# **How to use this course:**
Download the repo, load main file (Seurat_learnR_scRNA_seq) into R, click Run Document, follow instructions

# **User Experience**

One feature of the course is that students can decide how much background information they need to fully understand the information being presented.

![Background Info](https://github.com/STRIDES-Codes/Creating-Rmarkdown-courses-to-teach-bioinformatic-analysis-pipelines/blob/main/Screenshots/BackgroundInfoDropdown.png)

Additionally, there are built in assessment exercises that provide feedback to ensure that students understand what is being taught.

![Interactivity](https://github.com/STRIDES-Codes/Creating-Rmarkdown-courses-to-teach-bioinformatic-analysis-pipelines/blob/main/Screenshots/MC_Interactivity.png)

Students will be provided an opportunity to test their newly acquired knowledge with a dataset and questions. 

![Labels Exercise](https://github.com/STRIDES-Codes/Creating-Rmarkdown-courses-to-teach-bioinformatic-analysis-pipelines/blob/main/Screenshots/AddLabels_Exercise.png)

# **What's next?**

We will continue improving the functionality of this course in response to feedback from students. Next we will add courses following this interactive format.

# **Team Members: 

Binod Regmi
Matt Moss
Tasmine Clement
Shani Gelles
Yi-Han Hu
Md A Rahman
