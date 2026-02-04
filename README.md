# 820 - Team 09
Members: Liyang Peng, Yiheng Chen, Kush Vyas, Hanchao Tang

This project uses Project FeederWatch (PFW) data to understand how backyard sites and human feeding practices shape the ecological “context” in which bird observations are collected. In citizen-science programs like PFW, sites are not interchangeable: a residential yard with many feeders and frequent human activity is fundamentally different from a quiet woodland-edge site. If we can summarize sites into a small set of interpretable “types,” we can (i) improve ecological interpretation, (ii) compare participation fairly across regions, and (iii) guide recruitment or outreach to reduce bias.
We use two linked datasets (connected by loc_id):
PFW_count_site_data_public_2021.csv (site/environment + feeding/disturbance features), with 254,355 rows and 62 columns.
FW_2021_public.csv (checklist/observation records with time, effort, location, species, and counts), with 100,000 rows and 22 columns in our working extract.
