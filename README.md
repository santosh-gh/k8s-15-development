# Docker Build and Push to Docker Hub

    # Order Service
    docker build -t order ./app/order-service 
    docker tag order:latest e880613/order:v1
    docker push e880613/order:v1

    # Product Service
    docker build -t product ./app/product-service 
    docker tag product:latest e880613/product:v1
    docker push e880613/product:v1

    # Store Front Service
    docker build -t store-front ./app/store-front 
    docker tag store-front:latest e880613/store-front:v1
    docker push e880613/store-front:v1 