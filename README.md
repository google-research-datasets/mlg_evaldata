# Evaluation data patches for geocoding

## Data format
There is one patch file for each evaluation dataset used in our experiments.
The format of each file contents is tab-separated values:
1. toponym
2. latitude, longitude in dataset
3. unified latitude, longitude using WikiData

There may be more than one examples for each toponym in the respective datasets
hence the unique rows in the patch files would be less than total evaluation
examples.

#2 (i.e. latitude in dataset , longitude in dataset) is provided only for
reference to connect back to the original datasets. For evaluation itself we use
#1 and #3 only.

## License
The patches are released under GNU General Public License v3.0, same as the one 
used in [open-sourced evaluation datasets](https://github.com/milangritta/Geocoding-with-Map-Vector)
on which these are based on.

## Reference
The dataset is associated with the paper on
[Spatial Language Representation with Multi-Level Geocoding](https://arxiv.org/abs/2008.09236)

If you use these data fixes, please cite:
```
@misc{mlg_geocoding,
      title={Spatial Language Representation with Multi-Level Geocoding}, 
      author={Sayali Kulkarni and Shailee Jain and Mohammad Javad Hosseini and Jason Baldridge and Eugene Ie and Li Zhang},
      archivePrefix={arXiv},
      primaryClass={cs.CL}
}
```
