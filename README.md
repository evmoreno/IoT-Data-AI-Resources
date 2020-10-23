# EdgeComputeOpenHack

Getting started with Azure Stack Edge on an Azure VM.

Create NC12v2 VM in Azure on Ubuntu 18.04 
-	Install drivers - https://cnvrg.io/how-to-setup-docker-and-nvidia-docker-2-0-on-ubuntu-18-04/
-	Install nvidia docker and ensure nvidai-smi is working inside docker for you - https://cnvrg.io/how-to-setup-docker-and-nvidia-docker-2-0-on-ubuntu-18-04/
-	Install iot edge on your VM - https://docs.microsoft.com/en-us/azure/iot-edge/how-to-install-iot-edge-linux
OR use the Azure deploy button ere this does all above from UX -  https://github.com/MSKeith/iotedge-vm-deploy

Tutorials creating and deploying solutions to Edge:
-	Azure Stack Edge docs - https://docs.microsoft.com/en-us/azure/databox-online/azure-stack-edge-j-series-configure-gpu-modules
-	Intelligent Edge GitHub repo samples includes FactoryAI - https://github.com/Azure-Samples/azure-intelligent-edge-patterns
-	Live Video Analytics  -https://docs.microsoft.com/en-gb/azure/media-services/live-video-analytics-edge/use-intel-openvino-tutorial
-	Live Video Analytics GitHub repo has sammples and some utils includes RTSP simulator  - https://github.com/Azure/live-video-analytics
-	You can also train a CustomAI vision model, export to container and deploy to IOT Edge here is an example- https://azure.github.io/Vision-AI-DevKit-Pages/docs/Tutorial-HOL_Using_the_VisionSample/

Setup CICD for IoT Edge to deploy your container solution and even setup monitoring IoT Edge modules:
-	IoT Hub and IoT Edge Module Monitoring - Expose and ingest IoT Edge Metrics into Azure Monitor Log Analytics workspace - https://github.com/veyalla/ehm  
-	IoT Edge Container Debug logs to Azure Monitor - Ingest IoT Edge container logs into Azure Monitor Analytics workspace - https://github.com/veyalla/logspout-loganalytics 
-	Use Grafana to send IoT Edge Container Debug to Azure Monitor - https://github.com/veyalla/edge-telegraf-monitor


Concepts
- IoT Hub - https://docs.microsoft.com/en-us/azure/iot-hub/about-iot-hub
- IoT Edge Runtime - https://docs.microsoft.com/en-us/azure/iot-edge/iot-edge-runtime
- IoT Edge Modules - https://docs.microsoft.com/en-us/azure/iot-edge/iot-edge-modules
- IoT Edge Module communication - https://docs.microsoft.com/en-us/azure/iot-edge/iot-edge-runtime#module-communication
- IoT Edge on Kubernetes - https://docs.microsoft.com/en-us/azure/iot-edge/how-to-install-iot-edge-kubernetes#
- Container Host interactions - https://docs.microsoft.com/en-us/azure/iot-edge/how-to-use-create-options
    Storage - https://docs.microsoft.com/en-us/azure/iot-edge/how-to-access-host-storage-from-module
    Network - https://docs.microsoft.com/en-us/azure/iot-edge/how-to-use-create-options#map-host-port-to-module-port

Learn Content
- AI Edge Engineer - https://docs.microsoft.com/en-us/learn/paths/ai-edge-engineer/
- Introduction to IoT - https://docs.microsoft.com/en-gb/learn/paths/introduction-to-azure-iot/
- Securely connect IoT Devices- https://docs.microsoft.com/en-gb/learn/paths/securely-connect-iot-devices/
- Build intelligent edge with IoT Edge - https://docs.microsoft.com/en-gb/learn/paths/build-intelligent-edge-with-azure-iot-edge/
- Develop IoT Solutions with IoT Central - https://docs.microsoft.com/en-gb/learn/paths/develop-iot-solutions-with-azure-iot-central/

Check out #Project15 - https://github.com/microsoft/project15

#intelligentedge #edgeAI #IoTedge #AzureStack




