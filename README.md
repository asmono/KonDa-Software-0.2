# Hello and Thank You,
## Here is something you need to know about the KonDa Software.

The KonDa software is made for increase time eficiency, Arrival data usage, and optimize the on going research. Arrival data is the earthquake data type which obtained from BMKG and ISC institution and also another geology and/or geophysics institution. The KonDa software converting the Arrival data from institutions format to be input data for LOTOS (Local Tomography Software).

KonDa version released based on public user. I hope anyone able to use this KonDa software for their Seismic Tomography research instead changing the data format manually.

KonDa version is made and still developed by Dwi asmono (asmonodwi@outlook.com). Next update plan is Paradigm programming transformation (procedural to OOP (object oriented Programming)), Provide it's GUI (graphical user interface), and executable software.

# KonDa Software 0.2 New Updates:
This new updates bring simple file position and increase data quality.
## 1. KonDa Software with new file organization.
Folder file provided 3 different folder these are #01institution_data, #02temporary_table, and #03output_data.
The first folder allow us to identify the data arrival format from certain institution. The second folder used to store temporary file such as table output which is resulted during data preparation. The third folder consist 4 file, dataARRVSTApilihan.txt is data arrival which is before converted to input data format for LOTOS so we can analyze any data picked to checking the data output. The log.txt is the record of our data conversion, then the other are data input for LOTOS.
## 2. Changes on ISC phase columns used.
The last version (0.1) we are using REPPHASE column in the ISC data, and 
We have found the lack phase of some data arrival in the REPPHASE columns in the ISC data arrival. Then as the alternative we check another column phase (ISCPHASE), and we found the complete phase with no lack phase of ISC data arrival. 

# How to Use:
"KonDa Software 0.2.ipynb" is based on Jupyeter-Notebook so you can run this program with no installation but Anaconda. The data input example for this program is "format data input_dataArrival_BMKG.txt" and "format data input_dataArrival_ISC.txt" both of them have different data format and put in the first folder. After you run the program you will get rays.dat and sta.dat for LOTOS data input, log.dat consist the record of the cpnversion proces and the another file used for evalute the conversion result.

Dwi asmono is waiting for any information if any trouble happen when using this KonDa Software or any idea or advice about this KonDa Software.

## Best Regards,
# Dwi Asmono
Fresh Graduate of Physics (Geophysics) Bachelor

Dwi Asmono :LinkedIn  [+62 823 7313 9191] :Mobile Phone & WhatsApp  @dwiasmono_ :Instagram & Twitter

Email: asmonodwi@outlook.com; | Website: http://asmono.space/
