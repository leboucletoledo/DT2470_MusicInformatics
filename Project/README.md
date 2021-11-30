[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/14ZJ5GBKoUG1tx2BmgdoQznXMxAdt6NXp)


# DT2470 - Comparison between Onset Detection approaches

Final Project for Music Informatics course.

## Description

A IPYNB notebook that performs a comparison of different Onset Detection techniques, including Spectral-Based and Complex Domain Novelty Functions and two different frameworks for Peak Detection.

This notebook also makes use of Madmom's tools for Onset Detection, using an implementation of its RNN Onset Processor for the task. It also uses its Evaluation tools for obtaining metrics in order to assess the results.

## Getting Started

### Dependencies

In order to run locally, the following packages are needed on your Python environment:

* scipy
* pydub
* matplotlib
* numpy
* madmom
* pandas
* tqdm

If running on Google Colab, Runtime will need to be restarted at least once to run pydub and madmom.

### Installing

The notebook performs the comparison on the ODB dataset. The original files can be separately accessed here: https://grfia.dlsi.ua.es/cm/worklines/pertusa/onset/ODB/. A .zip file containing the data can be found in my Github page for ease of access here: https://github.com/leboucletoledo/DT2470_MusicInformatics/blob/master/Project/Data/ODB.zip.

On section 0.3 of the notebook, you will need to input where are the audio and annotation files located. In case of running on Google Colab, then you should upload a copy of the dataset and make changes as noted in sectino 0.2.

## References

>[1] Böck, S., Korzeniowski, F., Schlüter, J., Krebs, F., & Widmer, G. (2016). *Madmom: A new Python Audio and Music Signal Processing Library*. Proceedings of the 24th ACM International Conference on Multimedia. doi:10.1145/2964284.2973795

>[2] Böck, S., Krebs, F., & Schedl, M. (2012, October). *Evaluating the Online Capabilities of Onset Detection Methods*. In ISMIR (pp. 49-54).

>[3] Müller, M. (2016). *Fundamentals of Music Processing: Audio, analysis, algorithms, applications*. SPRINGER.

>[4] Nieto, O., & Bello, J. P. (2016, August). Systematic exploration of computational music structure research. In ISMIR (pp. 547-553).

>[5] Pattern Recognition and Artificial Intelligence Group, Universidad de Alicante. (2009). ODB (onset detection database). Retrieved 2021, from https://grfia.dlsi.ua.es/cm/projects/prosemus/database.php.

>[6] International Audio Laboratories Erlangen(n.d.). Chapter 6: Tempo and Beat Tracking. Retrieved 2021, from https://www.audiolabs-erlangen.de/resources/MIR/FMP/C6/C6.html
