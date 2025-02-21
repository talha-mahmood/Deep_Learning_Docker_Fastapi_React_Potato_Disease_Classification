Compatibility: python 3.9
docker commands:
docker build -t my-image-name .
docker run -d -p 8000:8000 -e myenv --name my-container-name --network my-network-name my-image-name
