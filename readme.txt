Instructions

1) Build the container
  sudo sh build.sh

2) Run the container and web server

 a) Run on default port 8080

  1) Use this command:
     sudo sh run.sh

  2) View the hello world page at:
     http://localhost:8080

 b) Run on a specified port

  1) Use this command:
      sudo sh run-on-port.sh [port]
     Example:
      sudo sh run-on-port.sh 80

  2) View the hello world page at:
      http://localhost:[port]
     Example:
      http://localhost:[port]



The Dockerfile being used is based on one provided by:
https://github.com/dockerfile/nginx
