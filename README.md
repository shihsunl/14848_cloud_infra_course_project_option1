# 14848_cloud_infra_course_project_option1

## Demo Video
- https://github.com/shihsunl/14848_cloud_infra_course_project_option1/blob/master/demo_video_url.txt

## System architecture
![System architecture](screenshot/system_architecture.png)

-------

## GCP Kubernetes
### Workloads
- Please follow the instructions in each service repo to apply developments
![workloads](screenshot/workloads.png)

### Service
- Please follow the instructions in each service repo to create services
![service](screenshot/service.png)

## Services
### Service Website
- Deploy Service Website to Google Cloud Platform Kubernetes Cluster
https://github.com/shihsunl/14848_cloud_infra_proj_driver
![website](screenshot/website.png)

- I've used Reverse Proxy to make different url paths redirect to different services. For instance, when you use `34.135.47.138/spark`, it will redirect to `http://spark-service` which is the spark service with port 8080. You can check `https://github.com/shihsunl/14848_cloud_infra_proj_spark/blob/master/resource-manifests/service-spark.yaml` for more detail.
![reverse_proxy-1](screenshot/reverse_proxy1.png)
![reverse_proxy-2](screenshot/reverse_proxy2.png)

### Jupyter
- Deploy Jupyter to Google Cloud Platform Kubernetes Cluster
https://github.com/shihsunl/14848_cloud_infra_proj_jupyter
![jupyter](screenshot/jupyter.png)

### Spark
- Deploy Spark to Google Cloud Platform Kubernetes Cluster
https://github.com/shihsunl/14848_cloud_infra_proj_spark
![spark](screenshot/spark.png)

### SonarQube
- Deploy SonarQube to Google Cloud Platform Kubernetes Cluster
https://github.com/shihsunl/14848_cloud_infra_proj_sonarqube_sonarscanner
![sonarqube](screenshot/sonarqube.png)

### SonarScanner
- Deploy SonarScanner to Google Cloud Platform Kubernetes Cluster
https://github.com/shihsunl/14848_cloud_infra_proj_sonarqube_sonarscanner
![sonarscanner](screenshot/sonarscanner.png)

### Hadoop
- Deploy Hadoop to Google Cloud Platform Kubernetes Cluster
https://github.com/shihsunl/14848_cloud_infra_proj_hadoop
![hadoop](screenshot/hadoop.png)
