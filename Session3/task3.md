Q1) docker run -d   --name db1   -e POSTGRES_PASSWORD=pass1234  -v db1-volume:/var/lib/postgresql/data   --memory=500m   postgres
    docker run -d   --name db2   -e POSTGRES_PASSWORD=pass1234   -v /mnt/d/learning/Docker/data:/var/lib/postgresql/data  --memory=500m   postgres

Q2)docker run -d --name c1 alpine
  docker run -d --name c2 alpine
  
  docker attach c2
  ping c1
  

  docker network create the-network

  docker run --network the-network --name c3 alpine
  docker run --network the-network --name c4 alpine

  docker attach c3
  ping c4
  
Q4)docker inspect c1





  
