# BioEntCls (Tutorial is Not Completed Yet)
A token classifier tutorial that helps you to understand how to fine-tune a token classifying problem including some beautiful techniches on how to deal with data shapeing/labeling issues and optimiziation.

This tutorial would be about fine-tunning a model to classify biomadical terms entities from input text. Model used in this tutorial is DistilBERT base model (uncased) and the dataset used is BioMed_general_NER from this linke bellow:
https://huggingface.co/datasets/knowledgator/biomed_NER

## About The Dataset:
**BioMed_general_NER**
This dataset consists of manually annotated biomedical abstracts from PubMed, drug descriptions from FDA and abstracts from patents.

### Classes
Here's a description for each of the labels:

* **CHEMICALS** - Represents substances with distinct molecular composition, often involved in various biological or industrial processes.

* **CLINICAL DRUG** - Refers to pharmaceutical substances developed for medical use, aimed at preventing, treating, or managing diseases.

* **BODY SUBSTANCE** - Denotes materials or substances within the human body, including fluids, tissues, and other biological components.

* **ANATOMICAL STRUCTURE** - Describes specific parts or structures within an organism's body, often related to anatomy and physiology.

* **CELLS AND THEIR COMPONENTS** - Encompasses the basic structural and functional units of living organisms, along with their constituent elements.

* **GENE AND GENE PRODUCTS** - Involves genetic information and the resultant products, such as proteins, that play a crucial role in biological processes.

* **INTELLECTUAL PROPERTY** - Pertains to legal rights associated with creations of the mind, including inventions, literary and artistic works, and trademarks.

* **LANGUAGE** - Relates to linguistic elements, including words, phrases, and language constructs, often in the context of communication or analysis.

* **REGULATION OR LAW** - Represents rules, guidelines, or legal frameworks established by authorities to govern behavior, practices, or procedures.

* **GEOGRAPHICAL AREAS** - Refers to specific regions, locations, or places on the Earth's surface, often associated with particular characteristics or significance.

* **ORGANISM** - Denotes a living being, typically a plant, animal, or microorganism, as a distinct biological entity.

* **GROUP** - Encompasses collections of individuals with shared characteristics, interests, or affiliations.

* **PERSON** - Represents an individual human being, often considered as a distinct entity with personal attributes.

* **ORGANIZATION** - Refers to structured entities, institutions, or companies formed for specific purposes or activities.

* **PRODUCT** - Encompasses tangible or intangible items resulting from a process, often associated with manufacturing or creation.

* **LOCATION** - Describes a specific place or position, whether physical or abstract, with potential relevance to various contexts.

* **PHENOTYPE** - Represents the observable characteristics or traits of an organism, resulting from the interaction of its genotype with the environment.

* **DISORDER** - Denotes abnormal conditions or disruptions in the normal functioning of a biological organism, often associated with diseases or medical conditions.

* **SIGNALING MOLECULES** - Involves molecules that transmit signals within and between cells, playing a crucial role in various physiological processes.

* **EVENT** - Describes occurrences or happenings at a specific time and place, often with significance or impact.

* **MEDICAL PROCEDURE** - Involves specific actions or interventions conducted for medical purposes, such as surgeries, diagnostic tests, or therapeutic treatments.

* **ACTIVITY** - Encompasses actions, behaviors, or processes undertaken by individuals, groups, or entities.

* **FUNCTION** - Describes the purpose or role of a biological or mechanical entity, focusing on its intended or inherent activities.

* **MONEY** - Represents currency or financial assets used as a medium of exchange, often in the context of economic transactions.
  
