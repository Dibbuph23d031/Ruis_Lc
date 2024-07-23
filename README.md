Add the data

cmsrel CMSSW_13_2_4

cd CMSSW_13_2_4/src

cmsenv

git clone --branch CMSSW_13X_2023data git@github.com:your-username/LambdaC.git

for me git clone --branch CMSSW_13X_2023data git@github.com:Dibbuph23d031/LambdaC.git

scram b -j4

cd dfinder

To run the data and MC

cmsRun forest_miniAOD_112X_DATA_wDfinder.py 

cmsRun forest_miniAOD_112X_MC_wDfinder.py 

