# monitoring system
Monitoring virtual machine menggunakan Node Exporter, Prometheus dan Grafana
![gambar](https://github.com/eprilian/frmn0033/assets/57064161/14c8404f-ad81-43c4-946a-342d9c738308)

Pada project ini saya menggunkana:
- Ubuntu Server 22.04 LTS
- Docker
- Node Exporter
- Prometheus
- Grafana

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
