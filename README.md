# outcomes_BH23

## [DBCLS BioHackathon 2023](https://2023.biohackathon.org/)  

## [RIKEN BioResource SPARQL endpoint](https://knowledge.brc.riken.jp/sparql)

## Outcomes 
### Title: 
Exploration of model mice relevant to human phenotypes and diseases using HP-MP mapping data  
  
### Contributors: 
KUSHIDA Tatsuya (RIKEN BRC), SHIN, Jae-Moon (DBCLS), and MASUYA Hiroshi (RIKEN BRC)   
  
### Background:
RIKEN BioResource Research Center (BRC) is constructing a bioresource knowledge graph (KG). The users can explore their bioresources (e.g., RIKEN mice relevant to specific MP terms.) for the KG. 　
  
### Aims: 
Leveraging human phenotype and disease information, we aimed to expand the information on model mice expected to be used for health care and medical research.　　　 
  
### Materials and Methods:  
  - Collecting the existing HP-MP mapping data (e.g., mp hp-align equiv, Mapping commons (mh_mapping_initiative), SSSOM, uPheno, uPheno2)
  - Generating the [HP-MP RDF data](https://github.com/kushidat/outcomes_BH23/blob/main/Data/hp_mp_mapping.ttl) from the HP-MP mapping data.
  - Integrating the Bioresource KG with the HP-MP RDF data and HPO annotation data within Monarch KG ([Figure X](https://github.com/kushidat/outcomes_BH23/blob/main/Figure/FigureX.png)).
  - Executing a [SPARQL query](https://github.com/kushidat/outcomes_BH23/blob/main/QueryExample/bh23_sparal_querty_example01.txt) for the integrated bioresource KGs to explore model mice relevant to human phenotype and diseases.
  
### Outcomes:  
We obtained 1875 mice relevant to 8834 HP terms and 1846 mice applicable to 7833 OMIM and 4259 Orphanet Rare Disease Ontology (ORDO) terms ([Figure Y](https://github.com/kushidat/outcomes_BH23/blob/main/Figure/FigureY.png)). However, we could not conclude the 1846 mice were disease models because the mice just related to human phenotypes associated with diseases.  
  
### Future work:  
  - Evaluation of the effectiveness of the existing HP-MP mapping data using human curation and AI technology  (e.g., TM, LLM).
  - Detection of the novel HP-MP associations (e.g., TM, LLM).
  - Usage of mapping data between human and model organism's phenotype in addition to model mouse (e.g., The Monarch Initiative provides phenotype mapping data between human and zebrafish, worm, Xenopus, and fly).
  - Establishment of model mice identification methods that are expected to be used for health care and medical research.

  
