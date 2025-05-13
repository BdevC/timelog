
### About the Project ###
This is a demo application to demonstrate fullstack development capabilities. 
The aplication will start as a clone of the nextjs dashboard tutorial.  once the tutorial is complete it will incorporate K8s and Kafka.

#### Progress ####
- [ ] Complete next.js dashboard tutorial
- [ ] Change as needed for time logging
- [ ] Containerize as needed
- [ ] Deploy to simple K8S if not utalized already
- [ ] Update to utalize kafka
- [ ] Set up Scalling for K8s

It is expected the application will consists of the following microservices
- Front-end: a UI to allow the user to use the application
- Authentication: Using Google and the recommended approach on Next.js
- Logger: A passthrough to MongoDB to log user data separately from the front-end

#### The following technologies are featured ####
- Kubernetes - A cluster to manage the services
- Scaffold - as an easy way to manage and develop with Kubernetes
- Kafka to manage asynchronous communication
- Docker to containerize the microservices
- Mongo to store the user data being logged
- Sign in with Google for Authentication

#### Things to know ####
- This is a work in progress
- I'm very used to Gitlab CI, but new to Github Actions
- The intention is to deploy live using [Cloudflare Tunnel](https://developers.cloudflare.com/cloudflare-one/connections/connect-networks/deployment-guides/kubernetes/)
  - The hardware that would be used for this broke and needs to be replaced.  

### Building Front-end ###
Be sure to run
```
npm install next@latest react@latest react-dom@latest
```

After cloning
