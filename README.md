# Predictors-of-Self-reported-SSRI-response
This branch contains the code related to the derivation and association testing of sociodemographic, clinical and genetic factors of selective serotonin reuptake inhibitor (SSRI) response in the Mental Health Questionnaire (MHQ2) of the UK Biobank (UKB).

The flow of code should be as follows:

1. **PGS_calculation**
2. **CYP2C19_metaboliser_status_derivation**
3. **Dataset_preparation_&_processing**
4. **SSRI_response_response_status**
5. **Association testing**
   - 5a. Sociodemographic
   - 5b. Clinical
   - 5c. Genetic

## Sociodemographic variables: 
Variables include age, sex, ethnicity, educational attainment, household income, and neighborhood deprivation. Variables collected at baseline UKB assessment. 

## Clinical variables: 
Particpant's symptoms and clinical characteristics during worst episode of depression are obtained from Composite International Diagnostic Interview (CIDI)-related questions.

## Genetic variables: 
### CYP2C19_metaboliser_status
Genotypes and metabolizer status were obtained from UKB return 3388 as described by McInnes et al.

### Polygenic_scores
PGS were calculated for five psychiatric conditions and two antidepressant response outcomes using GWAS summary statistics from the Psychiatric Genomics Consortium. 
PGS were calculated using the MegaPRS method within the GenoPred Pipeline (https://opain.github.io/GenoPred/) 
