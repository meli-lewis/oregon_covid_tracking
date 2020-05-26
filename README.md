# Oregon COVID Tracking

To start, this is a simple analysis notebook and some data sets.

## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install the packages in the [requirements file](requirements.txt).

```bash
pip install -r requirements.txt
```

## The data

I think it's especially important to know how many people have been tested (not just how many tests have been conducted, as people can be tested more than once) on the county level. I pulled some weekly numbers from the Multnomah County Health Department dashboard, but it's only for Clackamas, Multnomah, Washington and Yamhill counties. If you already have more granular and/or complete data, let me know! Otherwise, I'll do more research and, if necessary, file records requests.

### In this repo

### `data/input/`

Local files corresponding to data I retrieved from other sources. You can see more information on this by viewing the notebook in your browser.

I'll add better descriptions here soon.

### `data/output/`

Data after normalization, merging and modest calculation.

I'll add better descriptions here soon too.

## Contributing
Pull requests are welcome for any errors in the analysis code or documentation.

## License
This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.
