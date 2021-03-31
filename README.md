## Judgement Wall - 2015  
#### by [Travis Bennett](https://travisbennett.com)  
___  
\
&nbsp;  
![Image of Judgement Wall](https://github.com/jerknose/judgementWall/blob/master/public/judgement1.gif?raw=true)  

This project was originally built for an in-person event at the Peninsula Museum of Art.  
  
This project is a commentary on the surreal nature of full-color 3d scanning techniques and how creepy they looked.  
  
During the event, people would be scanned with a 3d scanner. Those scans were then placed on the Judgement Wall for all to see.  
  
When someone walked in front of the Judgement Wall, our digital patrons would turn and watch.  
  
Scanning done with Occipital Structure Sensor. People tracking using Microsoft Kinect v1. Visuals built in three.js and node.js.  
\
&nbsp;  
___  
[Demo](https://reckless.technology/archive/judgement-wall/) • [More Info](https://www.travisbennett.com/all/judgement-wall)  
___  
\
&nbsp;  
## Build and run with Docker  
___  
\
&nbsp;  
Build Docker project  
  
`docker build -t jerknose/judgementwall:1.0 .`  
  
Run / deploy instance  
  
`docker run -d -p 8080:8080 --name judgementwall jerknose/judgementwall:1.0`  
\
&nbsp;  
## Local Build Instructions  
___  
\
&nbsp;  
Install Dependancies  
  
`yarn install`  
  
Run  
  
`node server.js`  
