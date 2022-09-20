# HYD-MTR
The hassle of travelling in hyderabad using the metro transport made easy. This project is developed completely in java and has real life use case. The whole project is based on Dijkstra Algorithm to determine the shortest path from any source station(Metro Station) to all the possible Metro Stations. On selecting the source amongst any of metro stations it derives the shortest path to all the other metro stations.Each metro station is valued from numbers between 1 to 55.

***TIME COMPLEXITY:***
The time complexity of Dijkstras algorithm is O(N), N is the number of vertices in the graph.

***SPACE COMPLEXITY:***
The space complexity of Dijkstras algorithm is O(N)+O(N), N is the number of vertices in the graph.

# Dijkstra's algorithm
Dijkstra's algorithm is an algorithm for finding the shortest paths between nodes in a graph, which may represent, for example, road networks. It was conceived by computer scientist Edsger W. Dijkstra in 1956 and published three years later.The algorithm exists in many variants. Dijkstra's original algorithm found the shortest path between two given nodes,[6] but a more common variant fixes a single node as the "source" node and finds shortest paths from the source to all other nodes in the graph, producing a shortest-path tree.For a given source node in the graph, the algorithm finds the shortest path between that node and every other.It can also be used for finding the shortest paths from a single node to a single destination node by stopping the algorithm once the shortest path to the destination node has been determined. For example, if the nodes of the graph represent cities and edge path costs represent driving distances between pairs of cities connected by a direct road (for simplicity, ignore red lights, stop signs, toll roads and other obstructions), Dijkstra's algorithm can be used to find the shortest route between one city and all other cities. A widely used application of shortest path algorithms is network routing protocols, most notably IS-IS (Intermediate System to Intermediate System) and OSPF (Open Shortest Path First).

# STATION CODES
        Node number                                       Station Name
        
            1                                              LBnagar
            2                                              Victoria_memorial
            2                                              Chaitanyapuri
            3                                              Dilshukhnagar
            4                                              Moosrambagh
            5                                              New Market
            6                                              Malakpet
            7                                              MG BusStation
            8                                              Osmania_medical
            9                                              GandhiBhavan
            11                                             Assembly
            12                                             Lakdikapool
            13                                             Khairtabad
            14                                             Irrummanzil
            15                                             Panjagutta
            16                                             Ameerpet
            17                                             SRnagar
            18                                             ESIhospital
            19                                             Erragadda
            20                                             Bharatnagar
            21                                             Moosapet
            22                                             DR_BRambedkar
            23                                             Kukatpally
            24                                             KPHBcolony
            25                                             JNTUcollege
            26                                             Miyapur
            27                                             Sultanbazar
            28                                             Narayanguda
            29                                             Chikkadpali
            30                                             RTCxroads
            31                                             Musheerabad
            32                                             Gandhihospital
            33                                             SecundrabadWest
            34                                             Paradeground
            35                                             Nagole
            36                                             Uppal
            37                                             stadium
            38                                             NGRI
            39                                             Habsiguda
            40                                             Tarnaka
            41                                             Mettuguda
            42                                             SecuderabadeEast
            43                                             Paradise
            44                                             Rasoolpura
            45                                             PrakashNagar
            46                                             Begumpet
            47                                             MathuraNagar
            48                                             Yusufguda
            49                                             Jubliehills
            50                                             JH-checkpost
            51                                             Peddamagudi
            52                                             Madhapur
            53                                             Dugamcheruvu
            54                                             Hitechcity
            55                                             Raidurg
