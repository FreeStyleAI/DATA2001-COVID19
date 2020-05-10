SA2 data:
https://www.abs.gov.au/AUSSTATS/abs@.nsf/DetailsPage/1270.0.55.001July%202016?OpenDocument#Data

# DATA2001-COVID19
This is a group project for USYD DATA2001. We are processing and analysing COVID19 data in Australia 2020.

Mainidea:
– Calculate a 'risk' or 'vulnerability score' per suburb in Greater Sydney wrt. viruses
• BasedonABSdataaboutpopulation and availability of health services
– Visualise and correlate with Covid-19 data


Goal: Practical experience with data variety, data analysis, and presentation – Technologies as covered in this course: Python, Jupyter notebooks, and SQL

– Three tasks:

1. Data import and integration
• Weprovidedcensusdata,COVID-19stats,anddataabouthealth-services
• Needstobecombined,eg.viaspatialjoin
• Feelfreetoextendwithowndatasets
• Milestone1:IntegrationofprovideddatasetstobereadyinWeek11tutes

2. Vulnerability Analysis
• Computationof'vulnerability'score;exampleformulagiven
• Whenaddingotherdatasets,feelfreetoadjustformula
• CorrelationofyourscorewithCOVID-19testsandconfirmedcases

3. Documentationand(brief)Report

The data we are using:
– ABS Data
– Census data on neighbourhoods (SA2-level areas) in Greater Sydney
such as population, land area, number of dwellings, gender and age distribution – Health Services in NSW
– Location and some states (e.g. average available hospital beds)
– COVID-19 Data
– Conductedtestsandconfirmedcasesbypostcodetocheckforcorrelationwith
– Note that SA2-level data from the ABS does not always match suburbs,
and that the health services have a GPS location, but not the neighbourhoods
– cf.tutorialthisweekonhowtoretrieveboundarydataforneighbourhoodstoo
