This project contains code for the pangenome analysis of objective 2. 

Accessory gene analysis for 139 isolates pipeline:  
- Loading required libraries 
- Loading gene absence presence output from panaroo (generated through CompareM2 (https://github.com/cmkobel/CompareM2))
- Load in metadata
- Convert the presence absence to binary - link to metadata
- Calculate the core and accessory genome size 
- Save the accessory output
- Do data checks to see if any isolates are missing
- PCoA analysis with graphs 
- Significant genes extracted 

Accessory gene analysis for farm 84 isolates pipeline:  
- Single out the isolates to keep from the original 139
- New accessory dataframe 
- Do data checks to see if any isolates are missing
- Load in metadata and link to the farm 84 accessory dataframe
- PCoA analysis with graphs 
- Significant genes extracted 
- Alpha diversity (Shannon and Simpson)
- Beta diversity (PERMANOVA and PERMdisp)
