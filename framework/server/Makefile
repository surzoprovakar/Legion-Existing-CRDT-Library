# run:
#     ifeq ($(name),"server")
# 		sudo node ProdServer.js
#     else
# 		sudo node ObjectsServer.js
#     endif
# clean:
# 	@sudo fuser -k 8000/tcp

build:
	sudo node ProdServer.js
run:
	sudo node ObjectsServer.js
clean:
	sudo fuser -k 80/tcp