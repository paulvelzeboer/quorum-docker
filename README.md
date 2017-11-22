# quorum-docker
Quorum Blockchain Dockerized 

## Getting Started

cd quorum-docker
docker build -t quorum .

## Using Quorum Docker Image
	docker run -ti --name quoruminstance paulvelzeboer/quorum-docker bash

## Initialize 7 Nodes, start/stop

	root@CONTAINER:/# cd /quorum-examples/examples/7nodes/
	root@CONTAINER:/quorum-examples/examples/7nodes# ./init.sh   #need update!
	root@CONTAINER:/quorum-examples/examples/7nodes# ./start.sh  #need update!
	root@CONTAINER:/quorum-examples/examples/7nodes# ./stop.sh


### 7 Nodes
Rererence : https://github.com/jpmorganchase/quorum-examples/tree/master/examples/7nodes

### Permissions
Rererence : https://github.com/jpmorganchase/quorum-examples/tree/master/examples/permissions




