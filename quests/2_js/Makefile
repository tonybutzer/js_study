cat:
	cat Makefile

publish:
	(cd ../../; ./gitpush.sh)


web:
	docker run -it -v `pwd`:/var/www -p 80:8080 connormanning/http-server
