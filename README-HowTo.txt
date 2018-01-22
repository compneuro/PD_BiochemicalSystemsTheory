A Systems Model of Parkinson’s Disease Using Biochemical Systems Theory

This is the README for model published in the following paper:

Sasidharakurup H, Melethadathil N, Nair B, Diwakar S. "A Systems Model of Parkinson's Disease 
Using Biochemical Systems Theory", OMICS:A Journal of Integrative Biology 2017 21 8,454 -464.
Available at: http://online.liebertpub.com/doi/full/10.1089/omi.2017.0056

Major pathways involving in Parkinson's disease (PD) such as alphasynuclein aggregation, dopamine 
synthesis, lewy body formation, tau phosphorylation, parkin, and apoptosis were modeled 
using stochastic differential equations. Pathways were modeled and simulated using the 
biochemical pathway visualization program CellDesigner, a modeling tool for gene-regulatory 
and biochemical networks that support graphical notation and listing of symbols. The model allows 
a qualitative analysis of PD and a key signalling pathways for evaluating PD treatment conditions 
relating pathophysiology to molecular concentration changes recorded in experiments.

Last updated 10-January-2018
Developed by : Hemalatha Sasidharakurup & Shyam Diwakar    
Computational Neuroscience & Neurophysiology Lab, School of Biotechnology, Amrita Vishwa Vidyapeetham, India.
Email: shyam@amrita.edu, hemalathas@am.amrita.edu
www.amrita.edu/compneuro 


How to run the code
===================

1. Download the given code and save the file in a folder.

2. Load the file in CellDesigner (http://www.celldesigner.org/).

3. To reconstruct our graphs, copy and paste each pathway reactions into a new window in CellDesigner.

4. Set the initial values for each reactant as given in the following table.

--------------------------------------------
| Protein/gene name | Concentration values |
|-------------------|----------------------|
| Dopamine          | 700 ng/g             |
| a-synuclein       | 1294.9 pg/ml         |
| Parkin            | 20123 pg/ml          |
| DJ-1              | 0.84 mg/ml           |
| ROS               | 12.7 pmol/mg         |
| L-dopa            | 340 pg/ml            |
--------------------------------------------

5. Go to Simulations, select ControlPanel and click "execute" button to run the simulation.   
   A graph will be produced for each pathway.

6. One may have to rearrange the species in CellDesigner by dragging it manually, to have the look and feel of the pathway as shown in the paper.





























