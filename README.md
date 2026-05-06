# Konfigurasi-LAN
Konfigurasi Jaringan LAN (Local Area Network) menggunakan 1 router dan 4 switch dengan beberapa subnet (192.168.1.0 - 192.168.2.0) untuk pembelajaran dasar networking.

## Topologi Jaringan

Setiap switch terhubung ke router dan memiliki subnet berbeda:

## Topologi Jaringan

Setiap switch terhubung ke router dan memiliki subnet berbeda:

| Switch | Network        | Gateway        |
|--------|--------------|---------------|
| SW1    | 192.168.1.0  | 192.168.1.1   |
| SW2    | 192.168.2.0  | 192.168.2.1   |
| SW3    | 192.168.3.0  | 192.168.3.1   |
| SW4    | 192.168.4.0  | 192.168.4.1   |

## 🔌 Konfigurasi Router

Router menggunakan 4 interface (atau sub-interface jika pakai VLAN)
