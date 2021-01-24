# Ivac2_sect
Sector Files not supported by Terminal2Solutions for IVAC2.
The following instructions are for MAC OS.

You can install Sector files in IVAC2, even if the sectors are not downloadable or not approved by Terminal2Solutions.
This can allow you to keep updating your sectors and use them to controll on IVAO network.

Please, feel free to add new sectors to this Github.

I added FCCC (FIR of BRAZZAVILLE) and FNAN (FIR of LUANDA) in the release.

To add a sector to IVAC2:
-
1 - Unpack your sector to the place of your choice

2 - Move the complete folder to /Users/%Username%/Library/Application Support/IVAO/IvAc/fir

3 - Add you sector to the file /Users/%Username%/Library/Application Support/IVAO/IvAc/data/status.xml

    example for FNAN : <fir id="FNAN" name="Luanda FIR" country="AO" avbl="true" date="20180118" rev="2018011801" version="2018011801" file="fir_fnan_2018011801.zip"/>
    
4 - Save the file status.xml and make it read only for everyone...even you

5 - That's it
