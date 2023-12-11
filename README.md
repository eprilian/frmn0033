# monitoring system
Monitoring virtual machine menggunakan Node Exporter, Prometheus dan Grafana
![image](https://github.com/eprilian/monitoring-system/assets/57064161/60d970f3-7eb4-426c-80ce-144c8d444268)

Pada project ini saya menggunkana:
- Ubuntu Server 22.04 LTS
- Docker
- Node Exporter
- Prometheus
- Grafana

![image](https://brandslogos.com/wp-content/uploads/images/large/ubuntu-logo.png)
![image](https://banner2.cleanpng.com/20180604/hyj/kisspng-docker-yaml-github-repository-compos-5b14dcb9392900.5680028715280938812341.jpg)
![image](https://miro.medium.com/v2/resize:fit:1360/1*JRuh8eeRVeg1QI9q4z4SRw.png)
![image](https://www.clipartmax.com/png/middle/450-4503037_grafana-prometheus-grafana-logo.png)

Tujuan dari final project ini adalah membuat sebuah sistem monitoring yang mampu untuk memonitoring kinerja sebuah virtual machine atau baremetal
, mula dari kinerja hardware , untilitas network serta uptimenya.

Pertama yang saya lakukan adalah menginstall Ubuntu 22.04 Server LTS, pada Software Virtualisasi seperti VirtualBox dan VMware Workstation. Setelah 
Ubuntu terpasang, selanjutnya adalah melakukan update package dari repositori dengan perintah:
# apt update && apt upgrade -y

Setelah proses update selesai, install Docker menggunakan scrip install berikut:
https://get.docker.com/

Lakukan download dengan menggunakan curl, apabila belum terinstall maka install dengan menggunakan perintah dan lanjutkan proses download script install dockernya
# apt install curl 
# curl -fsSL https://get.docker.com -o get-docker.sh

Lalu jalankan script tadi dengan perintah berikut, dan tunggu proses installasi hingga selesai
# sh ./get-docker.sh
