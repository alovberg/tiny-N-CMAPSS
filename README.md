# tiny-N-CMAPSS
A tiny version of the 2021 PHM Data Challenge dataset (a subset of the N-CMAPSS dataset). Sensor readings have been changed from double-precision to half-precision floating point and the time-series has been decimated by a factor of 100 (from 1Hz to 0.01Hz). 
The training set (train_df.pkl) consists of the 'N-CMAPSS_DS01-005.h5', 'N-CMAPSS_DS03-012.h5', 'N-CMAPSS_DS04.h5', 'N-CMAPSS_DS05.h5', 'N-CMAPSS_DS06.h5','N-CMAPSS_DS07.h5', 'N-CMAPSS_DS08a-009.h5', and 'N-CMAPSS_DS08c-008.h5' files in accordance with the competition guidelines, while the test set (test_df.pkl) is the competition test/validation set downloaded from [here](https://data.phmsociety.org/2021-phm-conference-data-challenge/).

The full N-CMAPSS dataset can be downloaded [here](https://ti.arc.nasa.gov/tech/dash/groups/pcoe/prognostic-data-repository/#turbofan-2).

To run it yourself, put the files in the same directory as the notebook or change the file path in the notebook.
