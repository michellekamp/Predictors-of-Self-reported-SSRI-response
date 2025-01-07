# Predictors-of-Self-reported-SSRI-response
This repository contains the code related to the project exploring sociodemographic, clinical, and genetic predictors of selective serotonin reuptake inhibitor (SSRI) response in individuals with Major Depressive Disorder (MDD). The study focuses on participants from the Mental Health Questionnaire (MHQ2) of the UK Biobank (UKB) who have reported using at least one SSRI (citalopram, fluoxetine, paroxetine, or sertraline) to manage their depressive symptoms.

# Project Overview
Our analysis aims to identify predictors that can influence the effectiveness of SSRI treatment in managing the cardinal symptoms of MDD. This project specifically investigates:

- **Sociodemographic factors**: Are sociodemographic variables associated with SSRI non-reponse?
- **Clinical factors**: Are MDD symptoms and clinical characteristics assciated with SSRI non-response?
- **Genetic factors**: Are genetic factors, specifically CYP2C19 metabolizer status and polygenic scores (five psychiatric conditions and two antidepressant response phenotypes) associated with SSRI non-response? 

# Data Source
The dataset used in this analysis is derived from UKB, particularly focusing on those individuals who have participated in the Mental Health Questionnaire (MHQ2) and have a history of SSRI usage.

## Sociodemographic variables: 
Variables include age, sex, ethnicity, educational attainment, household income, and neighborhood deprivation. Variables collected at baseline UKB assessment. 

## Clinical variables: 
Particpant's symptoms and clinical characteristics during worst episode of depression are obtained from Composite International Diagnostic Interview (CIDI)-related questions.

## Genetic variables: 
### CYP2C19 
Genotypes and metabolizer status were obtained from UKB return 3388 as described by McInnes et al.

### Polygenic scores (PGS) 
PGS were calculated for five psychiatric conditions  and two antidepressant response outcomes using GWAS summary statistics from the Psychiatric Genomics Consortium. PGS were calculated using the MegaPRS method within the GenoPred Pipeline (https://opain.github.io/GenoPred/) 
