Code and data necessary to reproduce figures presented in our paper 
"Two-Streams Revisited: General Equations, Exact Coefficients, and Optimized Closures" (Ho, and Pincus 2024).
The figures and code to reproduce them are in the Jupyter Notebook `Two-stream_revisited_code.ipynb` 
which includes 3D interactive versions of Figures 6, 7, 10
We also provided code to further explore the dataset of coupling coefficients `twostreams_revisited_data.npz`.

Identical Zenodo record: https://zenodo.org/records/11561970.

The latest push is for the post-review (final) version of the paper, with a slight code change to accomodate `PythonicDISORT > 0.9.1`.

You may contact me, Dion, through dh3065@columbia.edu if you have any questions.

## Requirements
* Python 3.8+
* `PythonicDISORT >= 0.8.0` (A minor code change will be required for `PythonicDISORT <= 0.9.1`)
* `numpy >= 1.8.0`
* `scipy >= 1.8.0`
* `matplotlib >= 3.6.0`
* `jupyter > 1.0.0`
* `notebook > 6.5.2`
* `autograd >= 1.5`
* `plotly >= 5.22.0`
