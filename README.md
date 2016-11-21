# cpdn_um_stash_translator

The purpose of this code is to read a UM STASH file (currently configured with a stash_lookup.csv specific to UM4.5).  
_This code can be used with different UM versions by updating the dignostic definitions in this csv file as appropriate._

The main program STASH_converter.py is run with a commandline input of the STASH file to read.  

Usage :  --display       outputs csv to screen as well as file
         --stashfile=         specify stashc file to translate

Output:  \<stashfile\>.csv 

The output file presents all the STASH items spatial domains, temporal sampling, output frequeny and output file in a more human readable format.
The output includes the STASH item description, units and CMOR name (when known). 
