# GoogLeNet_Drug
Performance comparisons of AlexNet and GoogLeNet in cell growth inhibition IC50 prediction based on genomic and drug features

# Code description
- GoogLeNet_Drug.ipynb : the files predict drug responsiveness.
- GoogLeNet_construct_code.ipynb : the files describe construct of our model
- GoogLeNet.h5 : the file is the GoogLeNet model.
- Mutation_position_example.xlsx: the file contained the genomics information (mutation statuses) for the cancer cell lines.
- Drug_chemical_descriptors.xlsx: the file contained the drug chemical properties generated by PaDEL, and the columns were converted to binary digits. To make the list easier to see, we've transversed it. The original row should be set to be drug. (수정)
- Padel_Descriptors_detatiled_information.xls : This file contains a detailed description of each column used as drug features.
- GDSC_CCLE_druglist_smile_added.xlsx : This file describes the SMILE strings of the drugs used in the GDSC and CCLE datasets.


# Contact
### If you have any questions, please contact below.
- Ms. Yeeun Lee (soirlechat@gachon.ac.kr)
- Prof. Seungyoon Nam (nams@gachon.ac.kr)
