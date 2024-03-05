# Web Conference Multiparty

## Members: Dimitris Tzovanis, Elpida Stasinou

Thish is a multiparty version of the previous program. 
This program has many dependencies and aspects to develop, and is vastly different from the previous one.
We used the socket, kurento, webrtc, minimist, express and npm libraries, as well as the docker program to open the media server.
Because of these dependencies it is important that the steps are done correctly. 
Also any older version of kurento, socket, express, minimst will not work, so the following commands will replace the newer versions.


### Features
- Real-time Video and Audio Calls: High-quality, low-latency video and audio calls.
- Chat Functionality: Send and receive messages in real-time during the conference.
- Cross-Platform: Works on all major browsers and is responsive to fit any device.
- Multi-Participant Support: Join or host meetings with multiple participants.

### Dependencies

- Download Node
- Download Docker  
- Open docker
- From cmd go to the project folder directory run the following
  - npm init -y
  - npm install -S express@ socket.io@ kurento-client@ minimist@
  - docker run -d -p 8888:8888 kurento/kurento-media-server
- run nodeserver.js (in cmd)
- Open in chrome: http://localhost:3000/ in as many windows as you want, since there is no limitation on the number of users
