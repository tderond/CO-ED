# CO-ED (Co-Occurrence of Enzyme Domains)

This repository accompanies a manuscript by Tristan de Rond, Julia E. Asay and Bradley S. Moore

Our work on CO-ED was supported by National Institutes of Health (NIH/NIGMS) award F32GM129960 


The notebooks were written using Python v3.6.10, Jupyter notebook v6.0.3, pandas v1.0.3, networkx v2.4, requests 2.23, json v2.0.9
2020-09-04: IF YOU USE PANDAS v1.1.1, PLEASE NOTE THIS BUG AND WORKAROUND: https://github.com/tderond/CO-ED/issues/1#issuecomment-687508636

The workflow depends on PfamScan (http://ftp.ebi.ac.uk/pub/databases/Pfam/Tools/), which in turn depends on HMMER v3 (http://hmmer.org/) and Pfam-A (https://pfam.xfam.org/)


Annotation tables are based on data from MIBiG (http://mibig.secondarymetabolites.org), BRENDA (http://www.brenda-enzymes.org), and Uniprot (http://www.uniprot.org)


If you extract the files in uniprot_annotated_enzyme_tables.zip, you can run the majority of the `main` Jupyter notebook (up until the "all of uniprot" section) as-is.
The `preparing_data` notebook may be used if you want to want to generate the most up-to-date tables of annotated enzymes, or if you wish to run CO-ED on all proteins in uniprot. You will need to download some files from the latest releases of MIBiG, BRENDA and Uniprot as described in the `preparing_data` notebook.

References:
- Kautsar SA, et al. (2020) MIBiG 2.0: a repository for biosynthetic gene clusters of known function. Nucleic Acids Res 48(D1):D454–D458.
- Jeske L, Placzek S, Schomburg I, Chang A, Schomburg D (2019) BRENDA in 2019: a European ELIXIR core data resource. Nucleic Acids Res 47(D1):D542–D549.
- The UniProt Consortium (2018) UniProt: the universal protein knowledgebase. Nucleic Acids Res 46(5):2699.
- Eddy SR (2011) Accelerated profile HMM searches. PLoS Comput Biol 7(10):e1002195.
- El-Gebali S, et al. (2019) The Pfam protein families database in 2019. Nucleic Acids Res 47(D1):D427–D432.
