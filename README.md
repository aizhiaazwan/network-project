# Simulasi Jaringan Gedung Sekolah

## Deskripsi
Simulasi jaringan gedung sekolah 2 lantai
menggunakan Cisco Packet Tracer

## Topologi


![Topologi](Screenshot%20topologi.png)



## Ruangan
- Lantai 1: R.Tunggu, R.Server DNS, R.SMP, R.Layanan Akademik
- Lantai 2: R.SD, R.Pendiri, R.SMA/K

## Perangkat yang Digunakan
- 3 Router Cisco 1841
- 3 Switch Cisco 2960
- 2 Access Point
- 1 Server DNS
- 1 Server DHCP
- PC, Laptop, Printer

## Konfigurasi
### DHCP


![DHCP](Screenshot%20DHCP.png)


- Server DHCP untuk R.SD & R.SMA/K
- Pool: serverPool
- Range IP: 175.11.0.0
- Max User: 12

### DNS


![DNS](Screenshot%20DNS.png)


- Domain: bimbelaiueo.co.id
- Type: A Record
- IP: 11.22.11.1

## Hasil Koneksi


![PDU Successful](Screenshot%20PDU.png)


- Semua perangkat berhasil terhubung
- Koneksi antar lantai sukses
- Wireless & wired terhubung

## Tools
Cisco Packet Tracer
