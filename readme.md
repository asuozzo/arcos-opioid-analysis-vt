## Vermont ARCOS Opioid Data Analysis
This repo contains the analysis behind the *Seven Days* story "[Data Dive: As Opioid Crisis Ramped Up, Pills Flowed Into Vermont by the Millions](https://www.sevendaysvt.com/OffMessage/archives/2019/07/19/data-dive-as-opioid-crisis-ramped-up-pills-flowed-into-vermont-by-the-millions)", published July 19, 2019. To view it, open `analysis.ipynb`.


The dataset comes from the *Washington Post*'s cleaned version of opioid transactions from 2006 to 2012 from the ARCOS database, a DEA system designed to monitor sales and purchases of controlled substances. [Downloads are available here](https://www.washingtonpost.com/graphics/2019/investigations/dea-pain-pill-database/). They've compiled some [caveats and information about the dataset here](https://www.washingtonpost.com/national/2019/07/18/how-download-use-dea-pain-pills-database/). You can find additional information on data entry and field definitions in [this 1997 ARCOS handbook](https://www.deadiversion.usdoj.gov/arcos/handbook/full.pdf), which also includes some very helpful pointers on loading files onto magnetic diskettes.

To run this analysis yourself, clone the repo and install the Python 3 virtual environment using [Pipenv](https://docs.pipenv.org/en/latest/) — just run `pipenv install`, then `pipenv run jupyter lab` to get the notebook up and running.

Note that the main data file, `arcos-vt-statewide-itemized.tsv`, is 153 MB and 336,128 rows long, so loading it in may be a little slow.

Got questions about this analysis? Found an interesting detail? [Drop me a line](mailto:andrea@sevendaysvt.com)!