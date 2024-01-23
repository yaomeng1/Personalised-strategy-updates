# PersonalizedStrategyUpdates


Code for paper "Personalised strategy updates dominate the evolution of collective cooperation".

The codes include the function for theoretical calculations:

- `getBCratioRateUniIni` to calculate the theoretical critical ratio C* shown in Eq. (1) in the main text, where the evolutionary game process starts from a single cooperator placed uniformly at random on the network;
- `bcrRateApprox` to calculate the theoretical approximation shown in Eq. (3) in the main text;
- `OptUpRat` to optimize the update rate for each individual to minimize the critical ratio C*  given the adjacent matrix of any network;

and the file named "fixation_probability_personalized_rate.py" for numerical simulations.

The function of each file is depicted at the beginning of each file.

All codes are written by MathWorks Matlab R2021a.

To run the code, make sure that all files are in the same folder.
