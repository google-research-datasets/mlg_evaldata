# Evaluation data patches used in geocoding experiments.
Reference: https://arxiv.org/abs/2008.09236

## Data format
There is one patch file for each evaluation dataset used in our experiments.
The format of each file contents is tab-separated values:
1. toponym
2. latitude in dataset , longitude in dataset
3. unified latitude using WikiData , unified longitude using WikiData

There may be more than one examples for each toponym in the respective datasets
hence the unique rows in the patch files would be less than total evaluation
examples.

#2 (i.e. latitude in dataset , longitude in dataset) is provided only for
reference to connect back to the original datasets. For evaluation itself we use
#1 and #3 only.

## License
The patches are based on open-sourced evaluation datasets that use GNU General Public License v3.0. So these patches are also released under the same license.
