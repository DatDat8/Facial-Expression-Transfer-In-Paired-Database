# Facial-Expression-Transfer-In-Paired-Database
The project gives different hypotheses and  approaches to test their abilities to transfer emotional  expression among 7 domains with common categories from  JAFFE dataset (Anxious (AN), Distress (DI), Fear (FE), Happy  (HA), Neutral (NE), Sad (SA) and Surprise (SU)). There are 4  methods used including both conventional measures (unpaired  neural style transfer with CycleGAN, multi-domain style  transfer with StarGAN) and the proposed ones (domain  reconstruction with multiple decoders &amp; encoders and bottle  neck exchange using PCA (Principal Component Analysis)  rearrangement and exchange). While the formers show poor  performance ineffectiveness by giving the original shape of  images, the latter succeeds in generating images for other  domains when given an input expression. Eventually, to improve  the optimality regarding the number of used encoders and  decoders, PCA-based method is more prioritized. By using PCA  to sort the features vector according to their variance in a set of  paired images and exchange the emotional segment to the target  domain, the exchanged segment acts as navigation component to  orient to the target emotional type.

The explaination in detail of the code is included in CodeProject_DatTienNguyen.ipynb - the accumulated version of all the other codes.

For more information of the project's report, please enter this drive link : https://drive.google.com/file/d/1AeB3IODto-N_M7VojXOL1o15oza4Zh8L/view?usp=sharing

The dataset is taken from https://zenodo.org/record/3451524#.Ya83VtCZOF4 

Best wishes!
