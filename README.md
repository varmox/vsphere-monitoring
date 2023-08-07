# vsphere-monitoring

after docker containers have been started. Run the initial setup of influxDB via influx webinterface, listening of :8086 of your influxdb container ip.



sudo docker network create --driver ipvlan --subnet 172.29.30.0/23 --opt parent=ens192 --opt ipvlan_mode=l3 ipvlan0
