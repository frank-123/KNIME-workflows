# Analysis of Top Scientists in area of CRISPR-Cas (gene editing)

CRISPR-Cas is a technology for gene editing.

This folder consists of two KNIME workflows:
* The *author mining* workflow analyzes the the scientific literature to find *Top Scientists* for this scientic area. 
* The *webcrawling* workflow performs a web crawling to find interesting conferences for this technologies and to tag these conferences with the *Top Scientist* found with the *author mining* workflow so that one is able to identify the most important conferences.
* The *disambiguation* workflow helps to disambiguate author names.
 
Both workflows were designed under KNIME version 2.11.x and use the text processing as well as the Selenium (web crawling) plugin for KNIME.

