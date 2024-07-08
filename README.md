# Unvelling-Network-Malicious-flows

+ Pedro Fernandes - Department of Computer Engineering; Limerick Institute of Technology; Limerick, Ireland; Pedro.Fernandes@tus.ie ; Mathematics Department; Polytechnic Institute of Leiria; Leiria, Portugal; pedro.a.fernandes@ipleiria.pt

+ Séamus Ó Ciardhuáin - Department of Computer Engineering; Limerick Institute of Technology; Limerick, Ireland; seamus.ociardhuain@tus.ie

+ Mário Antunes - Computer Science and Communication Research Centre (CIIC), School of Technology and Management, Polytechnic of Leiria; Leiria; Portugal; mario.antunes@ipleiria.pt INESC TEC, CRACS; Porto; Portugal

# Benford's law-based method 

This paper introduces a novel method for identifying and analyzing anomalies within computer networks. It integrates Benford’s Law into the analysis process and incorporates a range of distance functions, namely the Mean Absolute Deviation (MAD), the Kolmogorov-Smirnov test (KS), and the Kullback-Leibler divergence (KL), which serve as dispersion measures for quantifying the extent of anomalies detected in network flows. 

Several scripts are presented, including a built-in Matlab script (Extract first digits, Tables MAD, KS, and KL Divergence). The procedure starts by extracting the first digits from a database containing malicious and benign flows. 
Subsequently, the obtained values are stored in a database format to .xls format. The first digit is extracted from this database, and the hypothesis tests (Pearson, Median Absolute Deviation, Kolmogorov-Smirnov test and Kullback-Leibler divergence) are applied. 

This procedure will allow the classifications. This entire classification procedure can be carried out by calculating the P-value obtained from the distance between the empirical frequency of occurrence of the digits from Benford's law and the relative frequencies of the digits extracted from the set of flows. 

# Dataset containing malicious and benign flows

This dataset was obtained from the UNB (University of New Brunswick) website and can be consulted (https://www.unb.ca/cic/datasets/ids-2017.html).

Important note: 
This dataset only contains network flows.
The final dataset is labelled correctly and consists of 19000 manipulated flows labelled 1 and 10000 benign flows labelled 0. 
If you wish to test the model with the dataset used, please send an e-mail to Pedro.Fernandes@tus.ie 

| Week date | Type of activity | Flows extracted | 
| ---- | ---- | ---- | 
| Monday| Only benign flows | 2000 | 
| Tuesday| Benign flows | 2000 |  
| Tuesday| Malicious flows | 4000 |  
| Wednesday| Benign flows | 2000 |  
| Wednesday| Malicious flows | 10000 |  
| Thursday| Benign flows | 2000 |
| Thursday | Malicious flows | 4000 |   
| Friday | Benign flows | 2000 |
| Friday| Malicious flows | 1000 |
| Total | 10000 | 19000 |

