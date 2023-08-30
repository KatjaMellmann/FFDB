<a name="readme-top"></a>
# The Folklore Forager Database (FFDB)
## Project Description
The Forager Folklore Database (FFDB) is a forthcoming metadata database collating information regarding folktales collected from hunter-gatherer cultures. The folktales in question were originally recorded by anthropologists and others during the past 150 years. Through rigorous bibliographic, ethnographic, and narratological work, these narratives are uncovered, selected, analyzed, and classified. Metadata includes, but is not limited to, collector and informant names, the culture and an assessment of its subsistence, the time of recording, the recording language, the quality of the recording, and bibliographic references. The FFDB is designed as an empirical basis for the systematic study of narrative universals, the evolutionary origin of storytelling, and for (comparative) folklore studies. The FFDB, aside from being a metadata database, will provide a representative corpus of narratives as [TEI-P5](https://tei-c.org/guidelines/p5/)-encoded XML.

This is a work-in-progress repository. For now, it will contain only a small selection of our digitized texts.
## Text Encoding
For the encoding of the folktales as TEI XML, two aspects are important to us. Firstly, the encoding should preserve textual features like the original spelling and page beginnings. This will make the oftentimes hard to access material available in a citable format. Secondly, the encoding should introduce a rich and for the context of folktale studies relevant annotation of semantic and narratological features. Currently, we are employing a manual and semi-automatic (through WordNet synsets, wordlists, and glossaries) annotation of animal, plant, color, personal, and place names. As the texts are transcriptions of oral performances, a differentiation is required between the diegetic level of the actual narrative and interjections, framing as well as explanatory comments. Here, we distinguish between meta-commentaries at the start (anamyth), during (apartmyth), and at the end (epimyth) of a narrative. 
## Text Classification
The metadata for our narratives is enriched further by employing the _Thompson’s Motif Index_[^1]. Instead of assigning motifs to narratives ourselves, we are relying on the strenuous work done by folklore scholars in the past. We are resolving the cryptic bibliographic references in Thompson’s own work and have digitized the motif assignments made by Johannes Wilbert and Karin Simoneau[^2] and Sigrid Schmidt[^3]. This will not only preserve the research done by experts but also allow us to classify a sizeable amount of the narratives in our corpus. The result is a complex network of references that will facilitate approaches within comparative folklore studies and provide a tagged corpus for machine learning approaches towards automatic motif recognition.
## About us
### Principal Investigators
[Katja Mellmann](https://www.ae.mpg.de/en/the-institute/people/katja-mellmann.html) (Max Planck Institute for Empirical Aesthetics)

[Michelle Scalise Sugiyama](https://cas.uoregon.edu/directory/social-sciences/all/mscalise) (University of Oregon)
### Doctoral Student
[Jan Jokisch](https://www.ae.mpg.de/en/the-institute/people/jan-jokisch.html) (Max Planck Institute for Empirical Aesthetics)
### Funding
Deutsche Forschungsgemeinschaft ([463393271](https://gepris.dfg.de/gepris/projekt/463393271?language=en))

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<sub>(README last updated on August 30, 2023.)</sub>

[^1]: Thompson, Stith (1955-58): Motif-Index of Folk-Literature. 6 vls. Bloomington/London: Indiana University Press.
[^2]: Wilbert, Johannes/Simoneau, Karin (1970-1992): Folk Literature of the South American Indians. Los Angeles: UCLA Latin American Center Publications.
[^3]: Schmidt, Sigrid (2013): Catalogue of the Khoisan Folktales of Southern Africa [1989]. 2., completely rev. ed. 2 vls. Köln: Köppe.
