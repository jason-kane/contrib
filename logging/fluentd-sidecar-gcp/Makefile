.PHONY:	build push

TAG = 1.4

build:
	docker build -t gcr.io/google_containers/fluentd-sidecar-gcp:$(TAG) .

push:
	gcloud docker push gcr.io/google_containers/fluentd-sidecar-gcp:$(TAG)
