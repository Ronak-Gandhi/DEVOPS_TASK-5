# DEVOPS_TASK-5

## TASK OBJECTIVE:-

* Integrate Prometheus and Grafana and perform in following way:

`1.`  _**Deploy them as pods on top of Kubernetes by creating resources Deployment, ReplicaSet, Pods or Services**_..

`2.`  _**And make their data to be remain persistent**_.

`3.`  _**And both of them should be exposed to outside world**_.

---

### _PREREQUISITE_:-
                   * RHel-8  * Docker  * Kubernetes  * Prometheus  * Grafana
                   
---                   

* **`PROMETHEUS Dockerfile`**:-

![Screenshot (177)](https://user-images.githubusercontent.com/64469896/93336121-f6c82d80-f844-11ea-87d3-1ed734349240.png)


* _Build Dockerfile of prometheus container image_

![Screenshot (173)](https://user-images.githubusercontent.com/64469896/93336057-e021d680-f844-11ea-8b3e-772a9392a9e9.png)

![Screenshot (174)](https://user-images.githubusercontent.com/64469896/93336075-e617b780-f844-11ea-8252-8a954dedea61.png)

![Screenshot (175)](https://user-images.githubusercontent.com/64469896/93336091-eadc6b80-f844-11ea-8302-ebf30b9ab89d.png)

![Screenshot (176)](https://user-images.githubusercontent.com/64469896/93336108-f2037980-f844-11ea-9169-3bacd0339b4e.png)


---


* **`GRAFANA Dockerfile`**:-

![Screenshot (198)](https://user-images.githubusercontent.com/64469896/93517486-26f8f480-f949-11ea-83cf-b6ad6704974e.png) 


* _Build Dockerfile of grafana container image_

![Screenshot (168)](https://user-images.githubusercontent.com/64469896/93517516-311af300-f949-11ea-8403-b36ce8c9e4cb.png)

![Screenshot (169)](https://user-images.githubusercontent.com/64469896/93517519-31b38980-f949-11ea-88dd-9d02bfebb02d.png)

![Screenshot (170)](https://user-images.githubusercontent.com/64469896/93517512-2fe9c600-f949-11ea-99a2-a680095b837a.png)

![Screenshot (171)](https://user-images.githubusercontent.com/64469896/93517591-4d1e9480-f949-11ea-8e60-ae2461b5b8c2.png)


---

* _**yml file of Prometheus**_!!

![Screenshot (227)](https://user-images.githubusercontent.com/64469896/93686675-69e7d300-fad5-11ea-87d3-c728d3e92375.png)

![Screenshot (228)](https://user-images.githubusercontent.com/64469896/93686670-67857900-fad5-11ea-8043-83a8f7cafb22.png)


* _**yml file of Grafana**_!!

![Screenshot (229)](https://user-images.githubusercontent.com/64469896/93686674-694f3c80-fad5-11ea-92be-a6ba98434edc.png)

![Screenshot (230)](https://user-images.githubusercontent.com/64469896/93686683-75d39500-fad5-11ea-9980-b4ddfe196c56.png)

---

![Screenshot (216)](https://user-images.githubusercontent.com/64469896/93686742-ef6b8300-fad5-11ea-9043-22eaebdef728.png)

![Screenshot (214)](https://user-images.githubusercontent.com/64469896/93686738-ec709280-fad5-11ea-9331-eeeeb9be4fb2.png)

![Screenshot (215)](https://user-images.githubusercontent.com/64469896/93686741-eed2ec80-fad5-11ea-83fd-21adbbc88057.png)


---

## THANK YOU !!
