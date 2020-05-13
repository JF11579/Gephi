# Gephi
How to notes


#Good 10 min tutorial. https://www.youtube.com/watch?v=371n3Ye9vVo

Py code for data manipulation:  https://drive.google.com/open?id=size1VYjyubIOt5_eZoiRfeTSMEt-IGyMtZ5t

Data must be in devided into 2 files. Edges and Attributes
DAta prep:
Edges:
Edge  3 columns SOURCE  | TARGET | WEIGHT. (Py GroupBy calls this  ,re-label it, where si9ze/weight is the number 
of times each combonation occurs.  For me source is Listing agent, Target is Selling Agent, Size/weight ,
ar the number of deals those 2 did.

Attributes:
Unlimited columns.  
First columns must be ID.  this contains teh same info as the SOURCE column.
Second column is LABEL.  This contains the same infor as the ID column.
Third column is ML#
Fourth Column is COMPANY
##########
GEPHI Steps and settings:

NEW PROJECT
Load edges first . 
When loading Attributes  change box to EXISTING PROJECT

COLOR AND SIZING NODES
 Appearance Window -> Nodes-> Color Pallette -> Ranking.  This makes the most connected the darrkest.
 
To change Node Size:
Statistics window -> run Network Diameter.
    Go back to NODES -> Ranking -> drop down -> Between Centrality
Next go to Layout window -> click Adjust to size.

To color by groups , say real estate companies :Community Detection 
    Statistics tab -> run modularity
 Nodes  -> Color -> Partition  -> Drop down window -> Modularity Class.
 
Node labels  -> click on "T" or tot he right the other "T" witthe drop down and selelct Node Size 

Filter:
Statistics /Filter window.  Filter-. Toplology -> selelct Degree range and drag it on top of 
    queries .  Move slider or click on number and type # run filter , click on Filter, hit stop.
    
Export :
Preview tab at top.  If blank at t top tool bar click Graph ?
On left select Settings tab -> Show labels -> export pdf, png, ....

SAVE:
To save settings  -> File -> Save as LesMis.gephi




