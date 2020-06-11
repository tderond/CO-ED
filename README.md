# CO-ED (Co-Occurrence of Enzyme Domains)

This repository accompanies a manuscript by Tristan de Rond, Julia E. Asay and Bradley S. Moore

The notebooks were written in Python v3.6.10, Jupyter notebook v6.0.3, pandas v1.0.3, networkx v2.4, requests 2.23, json v2.0.9
The workflow depends on PfamScan (pfam_scan.pl), which in turn depends on HMMER v3 (http://hmmer.org/) and Pfam-A (https://pfam.xfam.org/)

Annotation tables are based on data from MIBiG (http://mibig.secondarymetabolites.org), BRENDA (http://www.brenda-enzymes.org), and Uniprot (http://www.uniprot.org)

If you extract the files in uniprot_annotated_enzyme_tables.zip, you can run the majority of the "main" Jupyter notebook (up until the "all of uniprot" section) as-is.
The "preparing_data" notebook may be used if you want to want to generate the most up-to-date tables of annotated enzymes, or if you wish to run CO-ED on all proteins in uniprot. You will need to download some files from the latest releases of MIBiG, BRENDA and Uniprot as described in the "preparing_data" notebook.
