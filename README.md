# Custome-Image-with-Dockerfile
# Custome-Image-with-Dockerfile

docker login

docker image build -t cent2 .

docker tag custome1 munnaeeebd/custome1

docker push munnaeeebd/custome1



# something.yaml
spec:
      containers:
      - name: munnaeeebd-cent
        image: munnaeeebd/cent2
