# Thank you for choosing ECG analysis code!

Please follow the following steps to run the code:
(Skip steps 1 and 2 if you're directly running the Jupyter notebook)
1. Click on 'Code' on the top right corner of your github window and copy the 'Clone with HTTPS' URL
2. Go to the GitBash terminal (for Windows Users) and use git clone <URL> which is git clone https://github.com/GeetikaSi/ecg_analysis.git
3. Run 'ECG Analysis-MindMics.ipynb' file.
4. Please import all necessary packages (run cell 1 of Jupyter notebook)
5. Go to '1. Processing .hea file' cell and click on 'Cell' and 'Run All Below'
6. Then run the two cells below 'Run cells to load files':

(i) : Load path of header '.hea' file in the first input box

(ii): Load path of '.mat' file in the second input box


The program gives the output of various scenarios including hearat rate detection without filtering,
with filtering, using scipy and heartpy packaging.