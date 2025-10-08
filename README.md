# QUADRIS-project-Pre-crash-near-crash-database
Pre-crash/near-crash database used/developed in the [QUADRIS](https://www.vinnova.se/en/p/improved-quantitative-driver-behavior-models-and-safety-assessment-methods-for-adas-and-ad-quadris/?_t_tags=language%3Asv%2Csiteid%3A6a0eda26-a5be-4f47-a778-b9393a63f812%2Clanguage%3Aen&_t_hit.id=Vinnova_Models_Pages_ProjectPage/_81cfc747-ea2c-4296-afd3-7faa396882bc_en&_t_hit.pos=6) (Improved quantitative driver behavior models and safety assessment methods for ADAS and AD) project.

Main file:
"rear-end crash/Combined_incidents.csv"
- Contains information of rear-end emergent incidents (crashes and near-crashes) combined from the two datasets, [SHRP2 NDS](https://insight.shrp2nds.us/) and [CISS](https://www.nhtsa.gov/crash-data-systems/crash-investigation-sampling-system).
- See [Modeling Lead-Vehicle Kinematics for Rear-End Crash Scenario Generation](https://ieeexplore.ieee.org/document/10474582) for the definitions of a_1, a_2, tau_s, tau_1, tau_2.

"rear-end crash/Synthetic_crash_scenarios.csv"
- Contains information of 5,000 synthetic rear-end crash scenarios.
- Created based on [Model-Based Generation of Representative Rear-End Crash Scenarios Across the Full Severity Range Using Pre-Crash Data](https://ieeexplore.ieee.org/document/11028135).
- t: time, s.
d: the following distance, m.
v_f: the following vehicle's speed, m/s.
v_l: the lead vehicle's speed, m/s.

"rear-end crash/Synthetic_crash_scenarios_8k.csv"
- Newly created, including 8,000 scenarios.
