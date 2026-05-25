## Number of species and reactions contained in each mechanism 
### Table 3 in the original publication (Table 2 in the corrigendum)

| Mechanism                  | Species    | Reactions   | Redundancy |
|----------------------------|:-----------:|:-------------:|:-------------|
| Table3_H2_11sp             |         11 |         30  | Same as H2_11sp        |
| Table3_H2-CO_14sp          |         14 |         42  | Same as H2-CO_14sp     |
| Table3_H2-NOx_19sp         |         19 |         92  | Same as H2-NOx_19sp    |
| Table3_H2-CO-NOx_22sp      |         22 |         108 | Same as H2-CO-NOx_22sp |
| Table3_NH3_25sp            |         25 |         166 | Same as H2-NH3_25sp    |
| Table3_H2-NH3_25sp         |         25 |         166 | Same as H2-NH3_25sp    |
| Table3_H2-CO-NH3_29sp      |         29 |         196 | Same as H2-CO-NH3_29sp | 
| Table3_H2-CH4_35sp         |         35 |         256 |                        |
| Table3_CH4_36sp            |         36 |         259 | Same as H2-CH4_36sp    |
| Table3_NG_45sp             |         45 |         335 | Same as H2-NG_45sp     |
| Table3_H2-NG_45sp          |         45 |         335 | Same as H2-NG_45sp     |
| Table3_H2-CH4-NOx_47sp     |         47 |         381 |                        |
| Table3_H2-CO-CH4-NOx_47sp  |         47 |         362 |                        |
| Table3_H2-CO-NH3-CH4_47sp  |         47 |         396 |                        |
| Table3_H2-NH3-CH4_49sp     |         49 |         426 |                        |
| Table3_CH4-NOx_49sp        |         49 |         399 |                        |
| Table3_NH3-CH4_50sp        |         50 |         427 |                        |
| Table3_H2-NH3-NG_57sp      |         57 |         477 |                        |
| Table3_H2-CO-NH3-NG_58sp   |         58 |         481 |                        |
| Table3_NG-NOx_58sp         |         58 |         485 |                        |
| Table3_H2-NG-NOx_58sp      |         58 |         485 |                        |
| Table3_H2-CO-NG-NOx_58sp   |         58 |         485 |                        |
| Table3_NH3-NG_61sp         |         61 |         519 | Same as C3MechLite     |

Note that all numbers of species and reactions are based on Cantera-format mechanisms (reference values).
CHEMKIN-Pro mechanisms show different reaction counts because LOWMX/TROEMX and LOWSP/TROESP
encode species-specific falloff behavior inside grouped reactions.

**Redundancy** indicates if the mechanism is identical to one of the 10 mechanisms proposed in the article.
