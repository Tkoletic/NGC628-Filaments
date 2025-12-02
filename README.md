README file for NGC 628 filament data behind figures 3-5, Koletic et al. 2025 ApJ.
Created by Tamara Koletic (corresponding author) on December 2, 2025.

The NGC 628 filament data consists of one (1) CSV file containing the filament number, filament mass, and filament length. These filaments were identified from the projeted gas density plots of our simulated NGC 628 galax. Figures 4 and 5 use only this data but figure 3 uses observed filament data from Hacar et al. 2022 Protostars and Planets VII in addition to our NGC 628 filament data.

The CSV file contains the following columns:

DATA:  ID number    Mass      Length

Units:  N/A       log(Msun)   log(pc)

The table can be read with any machine table reader compatible for CSV. To read in the data using the pandsa python library, use the following line:

import pandas as pd
df = pd.read_csv('NGC628_filament_data_Koletic_et_al_2025.csv', delimiter=',')



