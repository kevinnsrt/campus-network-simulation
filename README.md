# Campus Network and Guest Access Simulation - Cisco Packet Tracer

## Deskripsi
Simulasi jaringan kampus menggunakan Cisco Packet Tracer, mencakup:
- VLAN & Trunk
- DHCP dinamis per VLAN
- NAT Overload untuk akses internet
- ACL untuk memfilter akses antar jaringan
- Wireless guest network yang diisolasi dari jaringan internal
- Routing antar router (RIP v2)
- DNS & Web server
- Physical Configuration
- Structured Cable

## Topologi
<img width="1261" height="557" alt="image" src="https://github.com/user-attachments/assets/889298fe-1f52-4c1e-977f-75157261dfc2" />

## Daftar IP & VLAN
| VLAN | Nama Divisi | Network         | Gateway       |
|------|-------------|------------------|----------------|
| 10   | HR          | 192.168.10.0/24 | 192.168.10.1 |
| 20   | Finance     | 192.168.20.0/24 | 192.168.20.1 |
| 30   | IT          | 192.168.30.0/24 | 192.168.30.1 |
|      | Guest       | 192.168.50.0/24 | 192.168.50.1 |

## Fitur Tambahan
- Access Control List (ACL) mencegah tamu mengakses jaringan internal
- NAT Overload via router internal ke router server (ISP simulation)
- Wireless router untuk akses tamu
- DNS dan web server internal
- Physical View

## Cara Menjalankan
1. Buka file `.pkt` dengan Cisco Packet Tracer
2. Jalankan simulasi dan test koneksi (ping ke server, akses DNS/web)
3. (Opsional) Coba matikan ACL untuk melihat perbedaan

## Physical View
<img width="963" height="671" alt="image" src="https://github.com/user-attachments/assets/10a15360-da97-4a41-ad14-df5cd63ddf9d" />
<img width="704" height="568" alt="Screenshot 2025-07-31 114324" src="https://github.com/user-attachments/assets/1d5b3387-0427-4be0-a6ca-1e3b914dc149" />
<img width="763" height="681" alt="image" src="https://github.com/user-attachments/assets/b46a4f46-4036-43dc-ba44-a4a3bbd4d269" />
<img width="810" height="682" alt="image" src="https://github.com/user-attachments/assets/d3f5e069-8a3b-4ad5-815b-1e896dc7421f" />

## Penulis
- Kevin Sirait - TI USU 23
