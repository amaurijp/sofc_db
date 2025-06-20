DATABASE - Solid oxide fuel cells (sofc_db) - Version 1.0
===============================================================================

The database `sofc_db_1.csv` 
is in version 1.0 and it was obtained from the
processsing of 9,064 articles abstracts.

The features (columns in file `sofc_db_1.csv`) extracted are:

1. anode full composition (anode) / Physical Unit = None (categorical terms has no PU);
2. anode elements composition list (e_anode) / Physical Unit = None (categorical terms has no PU);
3. anode elements composition string (p_anode) / Physical Unit = None (categorical terms has no PU);
4. cathode full composition (cathode) / Physical Unit = None (categorical terms has no PU);
5. cathode elements composition list (e_cathode) / Physical Unit = None (categorical terms has no PU);
6. cathode elements composition string (p_cathode) / Physical Unit = None (categorical terms has no PU);
7. electrolyte full composition (electrolyte) / Physical Unit = None (categorical terms has no PU);
8. electrolyte elements composition list (e_electrolyte) / Physical Unit = None (categorical terms has no PU);
9. electrolyte elements composition string (p_electrolyte) / Physical Unit = None (categorical terms has no PU);
10. LLM prompt response (extraction) / Physical Unit = None (categorical terms has no PU);
11. SOFC operation temperature (tp) / Physical Unit = degrees Celcius;
12. Power density (pw) / Physical Unit = mW cm<sup>-2</sup>

Information about the scientific articles used is present in the database (article title, DOI, abstract).

-------------------------------------------------------------------------------

The database was generated using the NLP pipelines
developed by André de Araújo Caetano ([Github](https://github.com/andre-aracaetano/LLM-Solid-Oxide-Fuel-Cell))
during his undergraduate project (2024-2025) under supervision of Prof. Amauri Jardim de Paula
at Ilum School of Science / Brazilian Center for Research in Energy and Materials (CNPEM), Campinas-SP, Brazil.
