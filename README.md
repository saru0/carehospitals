# carehospitals
A project to Automate dataflow of Hospitals and provide cleaned, organized data and make things better !

the project is about **Care Group of Hospitals**		
//They maintain records of Patient, doctor and hospitals
They also get daily lab results and insurance details from outside partners
Combining data from all these sources today is manual

PROBLEMS:
-->Patient records, Lab results and insurance data live in different places and don't 
line up automatically
-->New hospitals, doctors or partner files keep getting added , but there's no easy way
to bring in new data source
--reports are outdated , nobody notices until reports are wrong 

Solutions:
ADF framework ingests + csv sources via control table full/incremental
Data is cleaned and organized step by step
Every load is tracked automatically and status email is sent out
