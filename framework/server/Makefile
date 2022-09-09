# run:
#     ifeq ($(name),"server")
# 		sudo node ProdServer.js
#     else
# 		sudo node ObjectsServer.js
#     endif
# clean:
# 	@sudo fuser -k 8000/tcp

server:
	sudo node ProdServer.js
client:
	sudo node ObjectsServer.js
clean-server:
	sudo fuser -k 80/tcp
clean-client:
	sudo fuser -k 8000/tcp