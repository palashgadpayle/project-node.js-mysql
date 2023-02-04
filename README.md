# project-nodejs-mysql
# I follow this docs for following project --> https://varsubham.medium.com/nodejs-mysql-docker-compose-ad156cd0c885
# when some error occure i follow this docs --> https://sebhastian.com/npm-err-missing-script-start/

#note this error solve you kill the process of application of node by using ps -9 <process id> now return docker-compose up --build 

#[ERROR: for ubuntu_web_1  Cannot start service web: driver failed programming external connectivity on endpoint ubuntu_web_1 #(79ea4a8129a1de8f729eb8f6ac9a074592b6e243d130c73e11389b178116d15d): Error starting userland proxy: listen tcp4 0.0.0.0:5000: bind: address already in use
#ERROR: for web  Cannot start service web: driver failed programming external connectivity on endpoint ubuntu_web_1 #(79ea4a8129a1de8f729eb8f6ac9a074592b6e243d130c73e11389b178116d15d): Error starting userland proxy: listen tcp4 0.0.0.0:5000: bind: address already in use
#ERROR: Encountered errors while bringing up the project.]

 #if you see the below type of error then use ps -a you see the docker-compose process is running then kill -9 <process id> now run this command node index.js  
  
#[throw er; // Unhandled 'error' event
      ^

#Error: listen EADDRINUSE: address already in use :::5000]
