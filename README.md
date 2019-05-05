# logging

sudo sysctl -w vm.max_map_count=262144

tunnel to elastic

ssh -i "linux2.pem" -L 9200:172.31.46.92:9200 ubuntu@ec2-3-93-25-13.compute-1.amazonaws.com

tunnel to kibana

ssh -i "linux2.pem" -L 5601:172.31.46.92:5601 ubuntu@ec2-3-93-25-13.compute-1.amazonaws.com