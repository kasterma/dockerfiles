docker/build:
	docker buildx build --platform linux/amd64 --progress string --build-arg="PYTHON_VERSION=3.10" -t kasterma/poetry:0 .

docker/push:
	docker push kasterma/poetry:0
