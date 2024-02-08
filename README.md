This repository contains the implementation of a methodology for keyphrase extraction from climate change scientific reports and subsequent ontology enrichment. 

Our methodology involves four main steps: pre-processing, extraction of place names, keyphrase extraction, and ontology enrichment. We utilize climate change reports as input and evaluate keyphrase extraction using TF-IDF, Amazon Comprehend, and YAKE. The highest scoring keyphrases are leveraged for enriching the SWEET ontology, focusing on geospatial and climate change concepts.

Keyphrase extraction tools are compared based on their effectiveness in capturing relevant concepts from climate change reports. Amazon Comprehend, TF-IDF, and YAKE are evaluated, with Amazon Comprehend demonstrating the highest cosine similarity scores in aligning keyphrases with the ontology. The enriched ontology incorporates domain-specific concepts and geographical references, enhancing its comprehensiveness and relevance.

This repository contains files and notebooks related to the methodology for keyphrase extraction and ontology enrichment from climate change scientific reports. Below is a brief description of each file:

IPCC_AR6_WGII_Chapter16.txt: The raw text of Chapter 16 from the IPCC AR6 Working Group II report, which serves as the input for keyphrase extraction and ontology enrichment.

concepts_tf_idf.ipynb: Jupyter notebook containing code for keyphrase extraction using the TF-IDF approach.

Cosine_Similarity Score.ipynb: Jupyter notebook implementing cosine similarity calculations for assessing the resemblance between keyphrases and the ontology.

flow_diagram: Directory containing flow diagrams or workflow visuals illustrating the methodology implemented.

IPCC_AR6_WGII_Chapter16.csv: The processed version of Chapter 16 data in CSV format, likely used for analysis or input to some notebooks.

IPCC_AR6_WGII_Chapter16.pdf: PDF version of Chapter 16 from the IPCC AR6 Working Group II report.

Keyphrases_aws.ipynb: Jupyter notebook for keyphrase extraction using Amazon Comprehend.

KeyPhrases_aws.xlsx: Excel file containing the extracted keyphrases from Amazon Comprehend.

Keyphrases_tf-idf.xlsx: Excel file containing the extracted keyphrases using the TF-IDF approach.

Keyphrases_yake.xlsx: Excel file containing the extracted keyphrases using the YAKE approach.

locations_matching.ipynb: Jupyter notebook for matching locations extracted from text data with existing SWEET Ontology.

locations.xlsx: Excel file containing location data extracted from the text, possibly through the NER process.

NER.ipynb: Jupyter notebook for named entity recognition (NER) on the text data to identify locations.

ontology enrichment score.ipynb: Jupyter notebook for scoring ontology enrichment based on keyphrases extracted.

owlapi.xrdf: RDF file for SWEET containing ontology data or definitions.

sweet_test.owl: OWL file representing the SWEET ontology ontology.

SweetAllKatsadaki_final.rdf: RDF file containing the enriched version of the SWEET ontology.

wordclouds_20.ipynb: Jupyter notebook for generating word clouds based on keyphrases.

The ontology was enriched and presented with the help of Protégé tool.

yake.ipynb: Jupyter notebook for keyphrase extraction using the YAKE approach.

These files collectively constitute the methodology and implementation details for extracting keyphrases and enriching ontologies from climate change scientific reports.

