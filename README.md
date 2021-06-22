# Understanding How In-Visualization Provenance Can Support Trade-off Analysis

<img src="visprom.png"/>

## Abstract
In domains such as agronomy or manufacturing, experts need to consider trade-offs when making decisions that involve several, often competing, objectives. Such analysis is complex and may be conducted over long periods of time, making it hard to revisit. In this paper, we consider the use of analytic provenance mechanisms to aid experts recall and keep track of trade-off analysis. We implemented VisProm, a web-based trade-off analysis system, that incorporates in-visualization provenance views, designed specifically to help experts keep track of trade-offs and their objectives. We used VisProm as a technology probe to understand user needs and explore the potential role of provenance in this context. Through observation sessions with three groups of experts analyzing their own data, we make the following contributions. We first, identify eight high-level tasks that experts engaged in during trade-off analysis, such as locating and characterizing interest zones in the trade-off space, and show how these tasks can be supported by provenance visualization. Second, we refine findings from past work, by identifying specific provenance purposes related to trade-off analysis, like tracking these interest zones. And finally, we identify new opportunities for analytical provenance specific to trade-off analysis, for example related to monitoring the coverage of the trade-off space, and tracking alternative trade-off scenarios.

## Analysis Data & Analysis Notebook 
We collected video recordings of three case studies (324 minutes). Two different authors of this paper independently coded each video using discrete events, then met to discuss annotation codes and resolved conflicts. Our **concordance rate** for the identified provenance events was 71%, and was lower for the high level provenance goals.

The coding went through 3 passes / iterations (1,2,FINAL colored differently in the excel) and in the codebook these are ordered left to right (FINAL codes at the rightmost columns). 

We provide:
* Our Analysis Data corpus (all iterations of our data and coding) are available in <a href="AnalysisDataCorpus.xlsx">Excel</a> (with concordance) format or <a href="AnalysisDataCorpus.csv">CSV</a>.
* The Jupyter notebook we used for our analysis which can be downloaded from <a href="AnalysisNotebook_and_Data.zip"> here</a> (includes the analysis data).   

## Participants Quotes
We transcribed example quotes from our study participants that are representative of the observations and findings described in each result section of our paper. 

These can be found here: <a href="visprom_selected_quotes.xlsx">Excel</a> or <a href="visprom_selected_quotes.csv">CSV</a> format.

## Video
The video demo of VisProm can be found <a href="https://www.lri.fr/~anab/visprom.mp4">here.</a> 

## Contributors
M. Chakhchoukh, Univ. Paris Saclay, France. E-mail: mehdi.chakhchoukh@universite-paris-saclay.fr<br/>
N. Boukhelifa, INRAE, Univ. Paris Saclay, France. E-mail: nadia.boukhelifa@inrae.fr<br/>
A. Bezerianos, Univ. Paris Saclay, France. E-mail: anab@lri.fr
