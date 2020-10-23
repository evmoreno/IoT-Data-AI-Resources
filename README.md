# Explore Edge workloads

Deploy Azure GPU enabled VM
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


# Concepts
- IoT Hub - https://docs.microsoft.com/en-us/azure/iot-hub/about-iot-hub
- IoT Edge Runtime - https://docs.microsoft.com/en-us/azure/iot-edge/iot-edge-runtime
- IoT Edge Modules - https://docs.microsoft.com/en-us/azure/iot-edge/iot-edge-modules
- IoT Edge Module communication - https://docs.microsoft.com/en-us/azure/iot-edge/iot-edge-runtime#module-communication
- IoT Edge on Kubernetes - https://docs.microsoft.com/en-us/azure/iot-edge/how-to-install-iot-edge-kubernetes#
- Container Host interactions - https://docs.microsoft.com/en-us/azure/iot-edge/how-to-use-create-options
    Storage - https://docs.microsoft.com/en-us/azure/iot-edge/how-to-access-host-storage-from-module
    Network - https://docs.microsoft.com/en-us/azure/iot-edge/how-to-use-create-options#map-host-port-to-module-port

# Learn Content
- AI Edge Engineer - https://docs.microsoft.com/en-us/learn/paths/ai-edge-engineer/
- Introduction to IoT - https://docs.microsoft.com/en-gb/learn/paths/introduction-to-azure-iot/
- Securely connect IoT Devices- https://docs.microsoft.com/en-gb/learn/paths/securely-connect-iot-devices/
- Build intelligent edge with IoT Edge - https://docs.microsoft.com/en-gb/learn/paths/build-intelligent-edge-with-azure-iot-edge/
- Develop IoT Solutions with IoT Central - https://docs.microsoft.com/en-gb/learn/paths/develop-iot-solutions-with-azure-iot-central/

# IoT Workshops
- Internet of Things - https://github.com/Microsoft/MCW-Internet-of-Things
- IoT Smart City - https://github.com/Microsoft/MCW-IoT-and-the-Smart-City
- MlOps - https://github.com/microsoft/MCW-ML-Ops
- Predictive Maintenance for Field Devices - https://github.com/microsoft/MCW-Predictive-Maintenance-for-remote-field-devices
- Securing IoT End to End - https://github.com/microsoft/MCW-Securing-the-IoT-end-to-end

# Analytics & AI Workshops
- Machine Learning - https://github.com/microsoft/MCW-Machine-Learning
- Synapse & AI - https://github.com/microsoft/MCW-Azure-Synapse-Analytics-and-AI
- Big Data & Visualisation - https://github.com/Microsoft/MCW-Big-Data-and-Visualization
- Cognitive Services & Deep Learning - https://github.com/Microsoft/MCW-Cognitive-Services-and-Deep-Learning
- CosmosDB Real-time analytics - https://github.com/Microsoft/MCW-Cosmos-DB-Real-Time-Advanced-Analytics
- Innovate with Data & AI - https://github.com/microsoft/MCW-Innovate-and-modernize-apps-with-Data-and-AI
- Intelligent Analytics - https://github.com/Microsoft/MCW-Intelligent-Analytics
- Analytics and SQL 2019 - https://github.com/microsoft/MCW-Modernizing-Data-Analytics-with-SQL-Server-2019

# Data Workshops
- Migrate to Azure SQL - https://github.com/microsoft/MCW-Migrating-SQL-databases-to-Azure
- Migrating Oracle to Azure SQL, PostgreSQL -  https://github.com/Microsoft/MCW-Migrating-Oracle-to-Azure-SQL-and-PostgreSQL
- Check out #Project15 - https://github.com/microsoft/project15

#intelligentedge #edgeAI #IoTedge #AzureStack




