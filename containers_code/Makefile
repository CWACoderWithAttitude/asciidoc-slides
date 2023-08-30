oneBuild:
	docker build . -f Dockerfile.jdk8 -t myopenjdk:8
oneRun:
	docker run -it myopenjdk:8
oneRunMount:
	docker run -v ${PWD}/src:/src -it myopenjdk:8
