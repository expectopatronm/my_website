---
title: "Similarity Measures for Music Loop Projects in the Music Maker JAM Application"
date: 2020-04-05T17:29:26+02:00
draft: false
---
[Github link](https://github.com/expectopatronm/Similarity-Measures-for-Music-Loop-Projects-in-the-Music-Maker-JAM-Application)

The 100 XML project files describe 100 songs which are consisting of parts. Each part has 8
channels and each channel can hold one music loop. Each part and loop has some features (tags)
such as name, volume and active. The loops within the channels can be active or inactive. Only the
active loops are considered by our network for creating a song.

* Parse the XML files and extract information

* Use the data in the CSV files to replace the loop filename with the corresponding features
(label + d1-d8)

* Calculate some statistics about a music track. Statistics to be calculated should include:
* number of parts
* number of loops in parts
* most used loops
* most used Mix Packs within the XML project files
* most informative part index in a XML project file
* a jamming bonus skill is to find other/more expressive statistics

* Find a metric to compute the similarity between the projects

![K Means Clustering](/images/k_means_cluster.png)

![Cosine similarity](/images/cosine_similarity.png)