READ ME
 
ATLAS OF LEARNING MODEL PART -I (Term Base only )

TECHNOLOGIES USED:
A] Operating System : Windows 10 
B] Web Application 
1. Frontend- HTML,CSS,Bootstrap 4,Javascript,jQuery,D3.js  
2. Backend- Python(Django), SQLite3 database 
C] Software Used: 
1. Anaconda Navigator 
2. Visual Studio Code Editor 
3. SQLite3 Studio 

1. Python notebook:

Jupyter notebook has been used for performing YAKE, Glossary extractor and wikipedia parsing
01_YAKE_Extractor : YAKE is a Keyword Extraction Pipeline used for text pre-processing and  feature extraction.YAKE is used for extracting the keywords for Physics domain.It is applied on Halliday.The extracted words are stored in csv named PhysicsKeywords  

01_WIKIPEDIA GLOSSARY EXTRACTOR: It is also known as Terminology Extraction.The aim of glossary extraction is to automatically extract relevant terms from a given document or text. Glossary extractor is used for extracting keywords from the Physics and Chemistry domain. All the words available in the wikipedia glossary page of Chemistry and Physics are extracted.We have used a glossary extractor for these two domains as both these domains consists of chemical reactions which resulted in inaccurate keyword extraction while using YAKE.Hence a glossary extractor is preferred for Biology and chemistry domain.

02_URL EXTRACTION API FROM WIKIPEDIA: This Wikipedia API  is used for extracting the Wikipedia page of the keywords.This API will first check if the wikipedia page for a given keyword is available or not by giving an output as True or False.If the wikipedia page is available, the wikipedia link for the same is extracted 
 
03_URL to Simple Wikipedia Parsing : Parsing, syntax analysis, or syntactic analysis is the process of analyzing a string of symbols, either in natural language, computer languages or data structures, conforming to the rules of a formal grammar.Wikipedia parsing parses through the wikipedia page of every keyword stored in the csv file and extracts all the hyperlinks present in its wikipedia page.These extracted hyperlinks are considered as the context_words for the respective keywords 

You will find outputs extracted from the respective notebooks of the respective domain inside Physics-Notebooks-Output, Chemistry-Notebooks-Output, Biology-Notebooks-Output.

2. Term Base SQLite 
Inside Term base Sqlite you will find choice.csv and question.csv which is used in Sqlite3 data base of Dep-Map Application


The above extracted term base is used as input in the Dep-Map-Application for developing the Atlas of Learning Model.
for Dep-Map-Application Code reference visit url :https://github.com/Smita1102/Dep_Map_Application 









