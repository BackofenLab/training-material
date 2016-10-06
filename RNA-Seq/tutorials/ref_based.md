Reference based RNA-seq data analysis
=====================================

:grey_question: ***Questions***

- *Major question that would be addressed in this tutorial (mostly general biological questions)*
- *Second question*
- *Third question*
- *...*

:dart: ***Objectives***

- *First objective of this tutorial (It is a single sentence describing what a learner will be able to do once they have sat through the lesson. The objectives must be technical, but also theoretical, objectives. You can check [SWC lessons](http://swcarpentry.github.io/instructor-training/19-lessons/) to help you writing learning objectives.)*
- *Second objective*
- *Third objective*
- *...*

:heavy_check_mark: ***Requirements***

- *Galaxy introduction*
- *Second requirement*
- *Third requirement*
- *...*

:hourglass: ***Time estimation*** *1d/3h/6h*

[:book: **Associated slide deck**](http://bgruening.github.io/training-material/RNA-Seq/slides/ref_based.html)

# Introduction

General introduction about the topic and then an introduction of the tutorial (the questions and the objectives). It is nice also to have a scheme to sum up the pipeline used during the tutorial. The idea is to give to trainees insight into the content of the tutorial and the (theoretical and technical) key concepts they will learn.

# Part 1

Introduction about this part. Start with a fresh history.

## Inspecting the FASTQ files

We want to inspect our FASTQ file to get multiple information like the read length and the quality. Furthermore we want to trim low quality bases from the 3' end.

:pencil2: ***Hands on!***

1. Import the FASTQ file pair `GSM461177_untreat_paired_subset_1.fastq` and `2` from [Zenodo](http://dx.doi.org/10.5281/zenodo.61771). > sads

  > :bulb: **Importing data via links**
  > * Copy the link location.
  > * Open the Galaxy Upload Manager.
  > * Select **Paste/Fetch Data**.
  > * Paste the link into the text field.
  > * Press **Start**.
  
2. Both files contain the first 100.000 paired-end reads of one untreated sample. It's recommended to rename the datasets according to the samples. As default, Galaxy takes the link as the name.
3. **FastQC ⚙**: Run this tool on one of the two FASTQ files to control the quality of the reads. We can now inspect the results. What is the read length? 
4. **Trim Galore ⚙**: Trim Galore allows us to trim the low quality bases from the 3' ends. Try this on both paired-end reads. You might have to set the datatype to `fastqsanger`.

  > :bulb: **Datatype selection**
  > * Click on the pencil button of the dataset to edit the attributes.
  > * Choose `fastqsanger` as the datatype.
  > * Save.

5. **FastQC ⚙**: Rerun this tool to inspect the differences. 

## Subpart 2

Short introduction about this subpart.

:pencil2: ***Hands on!***

1. First step
2. Second step
3. Third step

Some blabla

:pencil2: ***Hands on!***

1. First step
2. Second step
3. Third step

# Part 2

Short introduction about this subpart.

:pencil2: ***Hands on!***

1. First step
2. Second step
3. Third step

## Subpart 2

Short introduction about this subpart.

:pencil2: ***Hands on!***

1. First step
2. Second step
3. Third step

Some blabla

:pencil2: ***Hands on!***

1. First step
2. Second step
3. Third step

# Conclusion

Conclusion about the technical key points. And then relation between the technics and the biological question to end with a global view.

:grey_exclamation: ***Key Points***

- *Simple sentence to sum up the first key point of the tutorial (Take home message)*
- *Second key point*
- *Third key point*
- *...*

# :clap: Thank you
