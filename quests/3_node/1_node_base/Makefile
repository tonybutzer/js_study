cat:
	cat Makefile


Im=node-base

build:
	docker build -t ${Im} .


bash:
	docker run -it ${Im} bash


test1:
	docker run -it -v `pwd`/test:/test  -u 1000 ${Im} bash


publish:
	(cd ~/opt/js_study; ./gitpush.sh)
