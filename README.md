
The script are available in R and Python languages and were compiled by the HELCOM Secretariat between 2015 and 2018.
The aims of the scripts are to cleaning the AIS data (pre-processing) as well as to generate maps and statistics of the traffic in the Baltic Sea Region.

The scripts available are: 
- Script 1. Pre_processing_AIS.R: the first one is to pre-process decoded AIS data using divisions. The mother file of data (yearly file of a given year) is divided in small divisions and each of these divisions are preprocessed and statistics (called reports) are generated for each divisions (number of duplicated signals, wrong IMO numbers, etc.). The script is finally merging the cleaned AIS data into monthly files.
- Script 2. Merging statistics.R: the second one aims to merge the statistics produced by the first script for a given year. It gives monthly statistics as well as yearly statistics
- Script 3. Shiplist from AIS monthly files: the third script will produce shiplist for a certain year based on the AIS monthly files for the script #1. 
- Script 4. Generate_events.R: this fourth script will generate events: it will produce the events such as the trips between ports, the calls in ports, the entrance and the exit of the Baltic Sea. For this script, a shape file is needed with the ports polygons.
- Script 5. Produce lines id.R: this script aims to generate the trips between the ports used in in the next script to produce the density maps. A shape file is also needed for this script, it contains the ports polygons (same as for the Script 4).


The underlying AIS data processing work has been co-financed by EU projects Baltic Scope (2015-2017 EASME/EMFF/2014/1.2.1.5) and Baltic Lines (2016-2019, Interreg Baltic Sea Region). For more information, please check the HELCOM Maritime Assessment on Maritime Activities published in 2018 at  ... . The methodology is available in the annexes.

License?
