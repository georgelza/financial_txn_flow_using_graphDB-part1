.DEFAULT_GOAL := help
include ../.env

IMAGE_NAME=kafka-connect-custom
VERSION=2.1

define HELP

Available commands:

- build: Build this project

endef

export HELP
help:
	@echo "$$HELP"
.PHONY: help

build:
	docker build -t ${REPO_NAME}/${IMAGE_NAME}:${VERSION} .

