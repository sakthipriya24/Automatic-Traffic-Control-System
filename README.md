# Automatic-Traffic-Control-System
Python based Project

Nowadays, traffic is highly increased. High traffic occurs mostly in junctions and in urban areas. Traffic Management System uses traffic signals and timer based system for directing traffic at each lane of an intersections of the road.

The Abstract of this project:
  1) To display the green signal automatically to the lane which is considered based on 
        a) To take a vehicle count in every lane after it attains a certain standard count. 
        b) The timestamp stored in a database.
        
main.py
  1) It is an executable file. 
  2) It fetches and display the video stream about the traffic.
  
(A standard line would be given which is denoted for counting the vehicles which crosses it.)

trackableobject.py
  1) It tracks the vehicle present in the video stream of the traffic.
  
centroidtracker.py
  1) It gives an unique ID number to the vehicles after tracking process has done.
  
directioncounter.py
  1) It counts the vehicle in the lane after crossing the standard line.
  
SQL Database:
  It store the timestamp and updated after the normal count exceeds the standard count.
