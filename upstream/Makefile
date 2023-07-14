TAG=3

build:
	docker build -t kubeicon-upstream:${TAG} .

load: build
	kind load docker-image kubeicon-upstream:${TAG}