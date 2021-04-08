# Consumption_Tracker
Scala/Java code that read data streams about customers usage of internet and matches it with some criteria to write output files that contains target customer for campain.

run this jar (Consumption_Tracker.jar) with the command below
scala Consumption_Tracker.jar "Data directory path" "Segment data directory path" "Rules data directory path" "Output directory path"
to simulate the data stream use the other jar "DataGen.jar" with those commands
1-	Generate the rules 
 java -jar DataGen.jar RULES "Rules data directory path"
2-	Generate the segment
 java -jar DataGen.jar SEGMENT "Segment data directory path"
3-	Generate the streaming data
 java -jar DataGen.jar DATA "Data directory path"
