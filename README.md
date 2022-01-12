## Objective 
Build efficient Machine Learning based data filteration pipeline for LHCb, CERN.

## Detailed Description:
At LHCb, one of the major detectors in Large Hadron Collider(LHC) study about the cause of Matter and Anti-Matter asymmetry.  
On 2022, the going to restart after major upgrades. The opposite moving particles collide each other within four detectors at every 25ns cycle corresponds to 40MHz.  
The amount of data generated at every event is so huge in volume, to filter out data generated to the storage tapes, it require an advanced and more sophisticated Trigger System is required.  
I work in building a Machine Learning based track classifier and deploy it in the Track Reconstruction Algorithm Sequence.

## Challenges : 
* Train the models on Huge Volume of Data
* Computational Limitations
* Imbalance Data Modeling
* Multi-language scripting (Eg: Python,C++)

## Work Pipeline (Simplified)

Input Data --> Split the data(70% Training & 30% Testing) --> Train the Machine Learning Model --> Fine Tune the Model Parameters --> Test Model --> 


:::mermaid
graph TD;
    A-->V-->C;
:::