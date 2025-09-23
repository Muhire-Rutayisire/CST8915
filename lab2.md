### What changes did you make to the order-service and product-service to comply with the Configurations and Backing Services factors of the 12-Factor App methodology?

- I created a `.env` in both services and copied all the relevant environment variable there, hence separating the codebase from the env variables, I also moved each service codebase into into own github repo, finally due to limited VMs my subscription allows me, I launched 2 VMs one for the codebases (orderserver, productservice and front-store) and the other for rabbitmq.

### Why is it important to use environment variables instead of hard-coding configurations in your application?

- Environment variables helps to manage values that changes based on the environment, like DB connection strings might be different on the testing environment than the production environment, in this case having those values stored in a separate file allows the developer to manage them on different environment.

### Why is it important to have separate repositories for each microservice? How does this help maintain independence and scalability of each service?

- Having microservices in separate github repo makes it easy for different teams to maintain a specific service and deploy it on it's own VM and at the same time provision resources as needed independently of the other services.

### The Codebase

- [order-service](https://github.com/Muhire-Rutayisire/order-service)

- [product-service](https://github.com/Muhire-Rutayisire/product-service)

- [store-front](https://github.com/Muhire-Rutayisire/store-front)

### Demo Video

[Demo](https://youtu.be/UZLEavxWZSQ)