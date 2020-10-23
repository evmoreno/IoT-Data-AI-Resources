# EdgeComputeOpenHack
Create NC12v2 VM in Azure on Ubuntu 18.04 
-	Install drivers - https://cnvrg.io/how-to-setup-docker-and-nvidia-docker-2-0-on-ubuntu-18-04/
-	Install nvidia docker and ensure nvidai-smi is working inside docker for you - https://cnvrg.io/how-to-setup-docker-and-nvidia-docker-2-0-on-ubuntu-18-04/
-	Install iot edge on your VM - https://docs.microsoft.com/en-us/azure/iot-edge/how-to-install-iot-edge-linux
OR use the Azure deploy button ere this does all above from UX -  https://github.com/MSKeith/iotedge-vm-deploy

Lots of Tutorials creating and deploying solutions that you can leverage includes:
-	Azure Stack Edge docs - https://docs.microsoft.com/en-us/azure/databox-online/azure-stack-edge-j-series-configure-gpu-modules
-	Azure Stack GitHUB has some nice use cases includes FactoryAI
-	Live Video Analytics  -https://docs.microsoft.com/en-gb/azure/media-services/live-video-analytics-edge/use-intel-openvino-tutorial
-	LVA GitHub repo has lots of utils includes RTSP simulator
-	You can also train a CustomAI vision model, export to container and deploy to IOT Edge
-	Build your own container module or deploy any Docker compatible container 

You can also setup CICD for IoT Edge to deploy your container solution and even setup monitoring IoT Edge modules (lots of options) includes:
-	IoT Hub and IoT Edge Module Monitoring - Expose and ingest IoT Edge Metrics into Azure Monitor Log Analytics workspace - https://github.com/veyalla/ehm  
-	IoT Edge Container Debug logs to Azure Monitor - Ingest IoT Edge container logs into Azure Monitor Analytics workspace - https://github.com/veyalla/logspout-loganalytics 
-	Use Grafana to send IoT Edge Container Debug to Azure Monitor - https://github.com/veyalla/edge-telegraf-monitor


