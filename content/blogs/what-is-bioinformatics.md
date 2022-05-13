---
title: "What Is Bioinformatics"
date: 2022-04-03T23:15:00+07:00
slug: what-is-bioinformatics
category: bioinformatics
summary:
description: 
cover:
  image: "covers/what-is-bioinformatics.jpg"
  alt: "What is bioinformatics?"
  caption: 
  relative: true
showtoc: true
draft: false
---

# Introduction

So you probably have heard of the term Bioinformatics before, but did not get the chance to learn more about what it is and what it can do.

In this article, I will be giving you a brief high-level overview of this exciting field of Bioinformatics. Thus, the article will be comprehensible to those coming from biology or computer backgrounds alike.

As a biologist, I have self-taught myself data science and coding (R and Python) after several years of persistence (initially quitting a couple of times the coding concept just kind of clicked at some point in time). Learn more about how I learned coding and my strategies for breaking into data science in [Strategies for Learning Data Science](https://towardsdatascience.com/strategies-for-learning-data-science-47053b58c19f).

Before proceeding further it is worthy to note that I’ve also released two introductory videos on Bioinformatics that serves as the basis for writing this article.
- [Using Computer Code to Decipher Genetic Code — Part 1 (Bioinformatics 101)](https://www.youtube.com/watch?v=p5iZxIT16KQ)
- [Using Computer Code to Decipher Genetic Code — Part 2 (Bioinformatics 101)](https://www.youtube.com/watch?v=ua08NV58Gew)

Expanding on the two above YouTube videos, I have drawn additional cartoons to provide a simple and guided tour of this exciting field of Bioinformatics.

# Biology is Data Intensive

The first point that I would like to make before taking a dive into explaining about bioinformatics is that biology is data intensive. Let’s take a step back and look at the big picture.

Humankind have always been curious about the world around us. Worldwide expeditions by Columbus, Vespucci and Magellan has allowed the discovery of previously unknown parts of the world. Fast forward to the 20th Century, the search of extraterrestrial life as well as understanding of our planet and galaxy have led to the launching of satellites and space expeditions to outer space.

In recent years, robotics and automation of laboratory equipments has led to an exponential rise and generation of “big” OMICS data. As such, this has permitted us to understand more about life as well as how to improve the quality of life. Exactly how can such OMICS data contribute to the betterment of life? The answer lies in the utilization of machine learning to make sense of these biological data particularly by unraveling hidden patterns in the data.

**Biology** literally stands for the study of life and living organisms. The term originates from the Greek words ***bios*** and ***logia*** which means life and study, respectively. In a nutshell, biology studies the biological processes that sustains life.

In order to study life, scientists formulate ***hypothesis*** (an educated guess) for which they perform experiments to validate their hypothesis and the process of doing so leads to the generation of experimental findings which literally equates to big data.

Historically, genomics represents the first OMICS to take off as initial efforts were aimed at an ambitious project called the ***Human Genome Project*** whose goals was to unlock the secrets of life by sequencing all human genes. Although the completion of the project had produced useful information but it was not enough to single-handedly explain all of the biological secrets of life. As a result, this naturally led to the ongoing search of answers by exploring other OMICS such as proteomics, glycomics, lipidomics, etc.

Recent advancements in high-throughput technology, robotics and automation has continued to fuel the resource-hungry OMICS endeavor. The widespread attention in bioinformatics has been spawned by several attractive buzzwords such as biotechnology, personalized medicine, precision medicine and CRISPR-Cas9, just to name a few.

# What is Bioinformatics?

In defining what exactly is ***bioinformatics***, we should also consider the relevant term ***computational biology***. In the field, both terms are often used interchangeably to literally refer to the use of computers in biology. Let’s take a look at the nuances of both terms.

Firstly, ***bioinformatics*** refer to the development of computational resources, tools, software and databases that will be useful for analyzing biological data. Secondly, ***computational biology*** refers to the use of such bioinformatics tools to gain understanding of biological data. As we can see, on one spectrum we have the development of tools while on the other spectrum we have the application of such tools to analyze and make sense of biological data.

# Common Tasks in Bioinformatics

Let’s now take a look at some of the common tasks in bioinformatics. We can see in the illustration below that there are essential 4 common tasks.

- Search — As we search Google for information on topics that we would like to learn more about, the same also applies when we want to find out more about biological entities (genes, proteins, DNA, RNA, etc.), chemical entities (compounds, drugs, metabolites, etc.), biochemical pathways and diseases. Instead of Google there are specialized databases such as GenBank for gene information, ChEMBL / PubChem / ChemSpider for chemical information, UniProt and Protein Data Bank for protein information, KEGG for biochemical pathways (how genes, proteins and compounds interact amongst one another to regulate the biological processes that sustains life).
- Compare — We make comparisons on just about everything in our life. For example, in deciding which graphics card to buy we may consider the price, the tech specs (number of CUDA cores) as well as other factors (brand recognition, form factor, etc.). In bioinformatics, genes or proteins are compared with one another in order to figure out how similar or different they are. If they are similar, how so? (the similarity is usually determined from the common “motifs” that the similar genes or proteins have in their composition of DNA (for genes) and amino acids (for proteins).
- Integrate and Curate — In the data science life cycle, we are aware that data collection and cleaning accounts for 80% of the time that we will be spending on to go from raw data to curated data. Before embarking on data analysis and machine learning model building, an essential first step is to decide upon the hypothesis or research direction that we will take. What research questions (hypothesis) will we address? Keeping this in mind, we choose subsets of data from the full database that would help us address the hypothesis. Then we clean the data in order to mend them for subsequent data analysis. As the saying goes, “garbage in, garbage out”, thus we will need to ensure the integrity of the data so as to increase the reliability of the resulting analysis and model.
- Model — This is probably the fun part of them all, models! Models can come in many shape and form. A structural model is literally a 2D or 3D model of biological or chemical entities that are comprised of virtual atoms that are connected to one another via chemical bonds. For example in a 2D chemical structure, atoms (e.g. carbon, hydrogen, oxygen, nitrogen, phosphorus, sulfur, etc.) are connected to one another via chemical bonds. Another example is the 3D protein structure which is comprised of amino acids that are attached to one another via peptide bonds. This long stretch of amino acids is known as a peptide and it folds three-dimensionally to form unique “folds” that serves a structural and functional role. In fact, the recent AlphaFold 2 developed by DeepMind has set record-breaking accomplishment by being able to predict structural models of proteins directly from the protein’s amino acid sequence (i.e. the the amino acid composition of the protein of interest).