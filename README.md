To setup the code:
=====

```

cmsrel CMSSW_13_2_4

cd CMSSW_13_2_4/src

cmsenv

git clone --branch CMSSW_13X_2023data https://github.com/milanchestojanovic/Ruis_Lc.git

scram b -j4

cd dfinder

```
To run data:
=====

```

cmsRun forest_miniAOD_112X_DATA_wDfinder.py 

cmsRun forest_miniAOD_112X_MC_wDfinder.py 
```
