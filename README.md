# Description
The electron Impact Excitation of Ions from Organics (EIEIO) annotation tool is an untargeted liquid chromatography-EIEIO tandem mass spectrometry (LC-EIEIO-MS/MS) data processing tool for in-depth analysis of lipid structure. This tool can accurately annotate the sum composition, _sn_-position, and C=C position of multiclass lipids such as lysophosphatidylcholine (LPC), phosphatidylcholine (PC), phosphatidylethanolamine (PE), sphingomyelin (SM), ceramide (Cer), diacylglycerol (DG), and triacylglycerol (TG). By summarizing the fragmentation principles of many lipid isomers in the positive ion EIEIO spectra, three index libraries were generated to realize the annotation of lipid structure. 
## Details of annotation tool
There are six sequential steps in the annotation tool: 1) extracting MS information, 2) classifying lipids, 3) aligning sum composition, 4) determining sn-positions, 5) locating C=C positions, and 6) ascertaining annotation levels. More details about this tool can be found in our article. 
# User guide 
This tool supports the mzML file format of the LC-MS raw data and only need to run the _summary.py_ to get the final output file after downloading this folder.
