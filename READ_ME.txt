# Energy-intensive-adaptation
This github repository contains addition materials of the paper "Energy-intensive adaptation partially offsets climate-driven labour productivity losses but at rising welfare costs"

The WITCH model is an open-source model currently based on GAMS. It can be downloaded here : (https://github.com/witch-team/witchmodel)

The released repository "AD_WITCH_OUTPUT" contains the WITCH model output files of the different scenarios considered in the study. These are:
- results_ssp2_bau.gdx : the baseline run of the SSP2 scenario without climate impacts on labour and energy-adaptation response
- results_labour_only.gdx : the impact scenario, in which climate change impacts on labour are implemented, without enabling the energy-adaptation response feedback.
- results_ada_HIGH/MED/LOW.gdx : the impact-adaptation scenario, with both climate impacts and energy-adaptation response feedback simoultaneously implemented, under HIGH, MED, LOW adaptation assumptions.
- results_comparison.gdx : the merged file with all the key output variables of interest considered in our study. 

The realised repository "EMPIRICAL_CALI" contains the relevant info, codes, input and output data for the regressions on labour-temperature-energy feedbacks used for the WITCH model calibration. 







