# QUADRIS-project-Pre-crash-near-crash-database
Pre-crash/near-crash database used/developed in the [QUADRIS](https://www.vinnova.se/en/p/improved-quantitative-driver-behavior-models-and-safety-assessment-methods-for-adas-and-ad-quadris/?_t_tags=language%3Asv%2Csiteid%3A6a0eda26-a5be-4f47-a778-b9393a63f812%2Clanguage%3Aen&_t_hit.id=Vinnova_Models_Pages_ProjectPage/_81cfc747-ea2c-4296-afd3-7faa396882bc_en&_t_hit.pos=6) (Improved quantitative driver behavior models and safety assessment methods for ADAS and AD) project.

Main file:
"Combined_incidents.csv"
- Contains information of rear-end emergent incidents (crashes and near-crashes) combined from the two datasets, [SHRP2 NDS](https://insight.shrp2nds.us/) and [CISS](https://www.nhtsa.gov/crash-data-systems/crash-investigation-sampling-system).
See "How does the lead vehicle behave in a rear-end crash?" for the definitions of a_1, a_2, tau_s, tau_1, tau_2.

"Synthetic_scenarios.csv"
- Contains information of synthetic rear-end crash scenarios.
d_init: the initial following distance, m.
v_f_init: the following vehicle's initial speed, m/s.
v_l_init: the lead vehicle's initial speed, m/s.
