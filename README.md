# Install
This has been tested on CMSSW_7_6_3  

git clone https://github.com/jbsauvan/Jet2TauFakes.git HTT-utilities/Jet2TauFakes  
scram b -j4   

# Tests
cd HTT-utilities/Jet2TauFakes/test   
root   
 .x loadLibrary.C   
 .L test2.C   
 test2()   


