docker login 
docker build -t react-integration .
docker tag react-integration puly91/react-integration:latest
docker push pulvy91/react-integration:latest