This program takes the direct output file of CH3Shift and calculates the RMSD of a desired peak to the CH3Shift predicted values. 

I.E.
You pick a peak with carbon and hydrogen chemical shift of 12 and 0.56
```
type in coordinates: 12 0.56
#Output
ILE 166 HD1 0.28
ILE 37 HD1 1.72
ILE 82 HD1 1.87
ILE 54 HD1 1.99
ILE 183 HD1 2.03
ILE 91 HD1 2.12
```
You may also add adjustments if there is a reference issue. I personally take a correctly predicted peak, and use that as reference (0.605 is the experimental proton peak shift and 0.512 is the predicted, so I shift all the proton values by 0.605-0.512). 

As you can see above, only the top 5 values are displayed. You may change this option to show top10, top 20, etc. 
