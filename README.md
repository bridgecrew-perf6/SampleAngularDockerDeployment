# Sample
This is a sample on how to deploy Angular on any server, including AWS EC2.

## Steps

Clone this repo
npm run build

To build the docker image run the command below:
sudo docker build -t angular_server .

To run the docker image run the commnd below:
sudo docker run -p 8888:80 angular_server

Navigate to:
http://[YOUR_IP_ADDRESS]:8888/
