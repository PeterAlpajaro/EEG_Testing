<h1>EEG Data Processing Tests</h1>

<h2>Dataset</h2>
<p>Data taken from https://bci.med.tsinghua.edu.cn/download.html and their SSVEP BCI Dataset. Each patient group contains 10 patients with 240 trials (2 electrode types, 10 blocks, 12 targets) We are only taking the dry electrode for this to match circumstances. Time is taken from the 125th to the 624th data point to eliminate the pre-stimulus and post-stiumulus times.</p>

<h2>CCA</h2>

<p>Two notable files, first (CCA Test.ipynb) is a document running CCA on some example data from sklearn, along with a manual implementation to understand the math. The second (EEG Data Processing - CCA.ipynb) is running this test on the clinical data and determining our accuracies across frequencies. We achieved results between 20% and >90% depending on the patient, so some adaptation may be required to reach bettter scores.</p>

<h2>TODO</h2>
    <li>FBCCA</li>
    <li>MIC</li>
    <li>CBA</li>
    <li>SPoC</li>
    
