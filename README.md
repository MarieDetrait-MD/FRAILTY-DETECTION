# FRAILTY-DETECTION

QualiFHIR: Optimizing Care Pathways for Frail and Geriatric Patients Using FHIR

Marie Detrait1, Arnaud Charlier1, Frédérik Lienard1, Laurent Dumont1, Véronique Latteur2, Christophe Dumont2, Christophe Thoreau3, Aline Li Causi3, Stéfanie Diolosa3, Anna-Lieta Stagno3, Nicolas Depasse1, Didier Goies4, Christelle Verhaege5, Guillaume Delbecque5, Pierre Jacmin1
 
1 Department of Technology and Information Systems, Grand Hôpital de Charleroi, Les Viviers, N°1 rue du campus des viviers, 6060 Charleroi, Belgium

2 Geriatric Departement, Grand Hôpital de Charleroi, Les Viviers, N°1 rue du campus des viviers, 6060 Charleroi, Belgium

3 Social Services Department, Grand Hôpital de Charleroi, Les Viviers, N°1 rue du campus des viviers, 6060 Charleroi, Belgium

4 Department of Technology and Information Systems, Clinique Notre Dame de Grâce, N° 212 Chaussée de Nivelles, 6041 Gosselies, Belgium

5 Department of Technology and Information systems, CH Mouscron, Mouscron, Belgium

 

Introduction

The QualiFHIR project, initiated by the Grand Hôpital de Charleroi, aims to enhance the management of care for geriatric patients by implementing an infrastructure based on the FHIR (Fast Healthcare Interoperability Resources) standard. This FHIR infrastructure enables the secure sharing of medical information among the partner hospitals of the project (Clinique Notre Dame de Grâce de Gosselies and CH de Mouscron) and supports the implementation of clinical decision support algorithms for detecting geriatric frailty.

FHIR Infrastructure

The established infrastructure is based on creating an interoperable data platform compatible with FHIR standards. Medical and socio-economic data are captured through questionnaires integrated into the Electronic Health Record (EHR) and processed using the standardized Snomed CT terminology. A FHIR repository has been developed for each hospital to store this data, facilitating its sharing among the project's partner hospitals. This infrastructure also serves as the foundation for training AI models. The project also includes a Large Model of Language (MISTRAL AI, LE CHAT, 2024) component to handle unstructured data.

Results

The developed algorithms, particularly XGBoost and an artificial neural network (ANN), have shown promising performance in detecting geriatric frailty. The XGBoost model achieved a ROC-AUC score of 0.875 and an accuracy of 0.92, while the ANN reached a ROC-AUC of 0.97 with an accuracy of 0.96. A LIME model was developed to correctly interpret the ANN. These initial results on a small cohort of patients (n=160) are encouraging as they indicate a reliable predictive capability.


Conclusion

The QualiFHIR FHIR infrastructure demonstrates how a standardized and secure data architecture can support data exchange between hospitals and enable the implementation of clinical decision support tools using AI models. These models have significant potential to improve the specific care of geriatric patients. The future of this project lies first in developing a dedicated application for geriatricians with the most effective model for each area on a larger patient cohort, then in the development of this infrastructure to other clinical contexts.

Files 
Réseau de neurones et XGboost pour détecter la fragilité gériatrique : FICHIER QUALIFHIR PATIENTS  FRAGILITE APPRENTISSAGE AUTOM.ipynb
LLM, Mistral AI, LE chat, 2024. Pipeline d'extraction : FHIR TEST Geriatrie.ipynb
Serveur terminologique du Minsitère : Qualifhir.ipynb

