# DDoS

Script DDoS Panel Sederhana dengan Multiple Bypass<br>(Cloudflare UAM,CAPTCHA,BFM,NOSEC / DDoS Guard / Google Shield / V Shield / Amazon / dll..)

## Metode

```sh
  [Layer 7]
 - cfb     | Bypass CF attack
 - pxcfb   | Bypass CF attack dengan proxy
 - cfreq   | Bypass CF UAM, CAPTCHA, BFM (request)
 - cfsoc   | Bypass CF UAM, CAPTCHA, BFM (socket)
 - pxsky   | Bypass Google Project Shield, Vshield, DDoS Guard Free, CF NoSec Dengan Proxy 
 - sky     | Metode Sky tanpa proxy 
 - http2   | HTTP 2.0 Request Attack 
 = pxhttp2 | HTTP 2.0 Request Attack With Proxy
 - spoof   | Attack Socket Spoof HTTP  
 - pxspoof | Attack Socket Spoof HTTP Dengan Proxy
 - get     | Attack Get Request
 - post    | Attack Post Request 
 - head    | Attack Head Request
 - soc     | Attack Socket
 - pxraw   | Attack Request Proxy
 - pxsoc   | Attack Socket Proxy
 
  [Layer 4]
  -udp     | UDP Attack
  -tcp     | TCP Attack
  
  [Tools]
 - Dns     | Pencarian DNS Klasik
 - Geoip   | Pencarian Alamat IP Geo
 - Subnet  | Pencarian Alamat IP Subnet
```


## Penggunaan di Linux

**Kloning Repository Ini**
```bash
git clone https://github.com/Yoga913/DDoS.git
```
**Installasi Modul:**
```
- python3 setup.py
```

## Contoh
```sh
Gunakan Panel DDoS: python3 main.py
Gunakan baris perintah: python3 main.py <method> <target> <thread> 
<time>
└──────────> python3 main.py cfb https://example.com 100 30
```

## Catatan

Demikian Script Ini Dibuat Untuk Tujuan Pendidikan Dan Penelitian,
Selebihnya Saya Tidak Ber Tanggung jawab Jika Dialahgunaan Ataupun Merugika Orang lain.

