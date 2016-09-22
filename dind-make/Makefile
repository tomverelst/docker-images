default: build

.PHONY: build
build:
	docker build -t tomverelst/dind-make .

.PHONY: test
test:
	docker run --rm \
	-v Makefile:/Makefile \
	tomverelst/dind-make \
	echo

.PHONY: echo
echo:
	@echo "Hello"
