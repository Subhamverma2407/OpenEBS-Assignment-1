# OpenEBS-Assignment-1

## Steps to Run the app

1. Clone the repo with ```git clone https://github.com/Subhamverma2407/OpenEBS-Assignment-1.git```.
2. Then goto that directory.
3. Run all the yaml files through this command.  
	```kubectl apply -f pods.yaml```  
	```kubectl apply -f deploy.yaml```  
	```kubectl apply -f services.yaml```
4. Now run the docker through this command  
	```docker run -e username="YOUR_USERNAME" -p 127.0.0.1:80:80 subhamverma2407/username:first```
5. Now Open the browser on the link provided after running the command in step 4.
