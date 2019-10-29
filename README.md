# Custome-Image-with-Dockerfile
# Custome-Image-with-Dockerfile

docker login

docker image build -t custome1 .

docker tag custome1 munnaeeebd/custome1

docker push munnaeeebd/custome1



# something.yaml
spec:
      containers:
      - name: munnaeeebd-custome1
        image: munnaeeebd/custome1
