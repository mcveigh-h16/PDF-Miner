# PDF-Miner
Extracts text from PDF and parses into dataframe

PC based jupyter notebook, to extract lines of text from pdf file by page number, convert it into a format for taxonomy update and merge mycobank data. Output saved to excel. Data rows are modified at several steps to created desired output. Final output saved as excel. Opportunity for improvement by dropping some of the extra columns. 

Rank assignment rules
Organism Name -mycotina=subphylum, -mycetes=class, -ales=order, -aceae=family
If text contains 'incertae sedis' this is appened to the organism name

Merge in Mycobank data from RESP API. Incorporates previously captured data from API and file downloads with the parsed data from the pdf. See 
