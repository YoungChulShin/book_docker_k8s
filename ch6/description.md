### PD 생성
~~~
gcloud compute disks create --size=10GB --zone=asia-east2-a {name}
~~~

### PD, PV, PVC
- PV을 생성하기 위해서는 PD가 있어야 한다
- PVC를 요청하기 위해서는 PV이 있어야 한다