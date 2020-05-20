# Multidimensional Associations Between Cognition and Connectome Organization in Temporal Lobe Epilepsy

## `./databases`
| **Filename**                   | **Class**       | **Description**                                                                                    |
|--------------------------------|-----------------|----------------------------------------------------------------------------------------------------|
| Destrieux+VolBrain_162_LUT.csv | Lookup table    | ROI labels created by merging the dextrieux (cortical) and volbrain (subcortical) parcellations.   |
| FreeSurferColorLUT.txt         | Lookup table    | Original freesurfer lookup table for Dextrieux parcellation.                                       |
| data_nm_by_ROI.csv             | Database        | Contains the mean and standard deviation of each ROI by cognitive class.                           |
| data_nm_network-metrics.csv    | Database        | Network metrics by subject and ROI. (L=path length, k=degree centrality, C=cluster coefficient).   |
| data_sm_subject-metrics.csv    | Database        | Subject metrics by subject.                                                                        |
| rcca-XYmatrices.RData          | RData workspace | sm=subject metrics (matrix); nm=network metrics (data frame).                                      |
| rcca_stats.RData               | RData workspace | res.stats=result of 10,000 permutations of the main CCA model                                      |
| tle_default.txt                | Lookup table    | Lookup table used by mrtrix to change the ROI numbering from freesurfer to a continuous numbering. |