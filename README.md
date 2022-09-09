# Guida all'avvio dell'applicativo routing SDN
#1) Avviare mininet tramite file python, file geant_topology.py preso dalla [repo](https://github.com/gabrispa/controllerML/tree/main/TrafficGenerator)
#2) Avviare RYU controller su un altro terminale comando "sudo ryu-manager —observe-links topology_discover.py flow_installation.py monitor.py delay.py"
#3) Aspettare la convergenza della rete e il riempimento del file net_info.csv che si trova nella cartella principale
#4) Avviare RL_threading.py (lui comincia a stampare ok)
#5) I percorsi saranno disponibili (dopo il primo ok) nel file paths.json dentro la cartella RoutingGeant

#Nota: host 24 e 10 sono connessi allo stesso switch e inviano a due host diversi (vedi traffic_matrix) senza alcun problema.
