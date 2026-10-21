<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:13294b,100:1f6feb&height=190&section=header&text=Antonio%20Manuel%20N%C3%BA%C3%B1ez&fontColor=ffffff&fontSize=40&fontAlignY=38&desc=Sistemas%20%C2%B7%20Redes%20%C2%B7%20Ciberseguridad&descAlignY=58&descSize=16" width="100%" alt="Antonio Manuel Núñez" />

<p align="center">
  <a href="https://www.linkedin.com/in/antonio-manuel-nu%C3%B1ez-campallo/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:anunezcampallo@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  <img src="https://img.shields.io/badge/Sevilla-España-1f6feb?style=for-the-badge&logo=googlemaps&logoColor=white" alt="Sevilla, España" />
  <img src="https://img.shields.io/badge/Disponible-prácticas%20%2F%20media%20jornada-2ea043?style=for-the-badge" alt="Disponible" />
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=18&pause=1200&color=58A6FF&center=true&vCenter=true&width=520&lines=Honeypots+y+detecci%C3%B3n+de+amenazas;Homelab+con+Proxmox+VE+%2B+Tailscale;Automatizo+lo+que+hago+dos+veces" alt="Typing SVG" />
</p>

Técnico de sistemas y redes en Sevilla. Estudio ASIR y el Máster en Ciberseguridad e IA de Evolve, y el resto del tiempo lo paso montando y rompiendo cosas en mi homelab.

Me interesa sobre todo la parte defensiva: saber qué pasa en una red, detectar lo que no debería estar ahí y automatizar lo repetitivo para no tener que hacerlo a mano dos veces.

> **Busco** prácticas o un puesto a media jornada / por proyecto en sistemas, redes o ciberseguridad, compatible con los estudios.

### Ahora mismo

- Desarrollando **PHANTOM**, un entorno de honeypots con detección de amenazas apoyada en IA (aún privado).
- Cursando el Máster en Ciberseguridad e IA (Evolve) junto con ASIR.

---

### Proyectos

<p align="center">
  <a href="https://github.com/antonio101105/Honeypot"><img src="https://github-readme-stats.vercel.app/api/pin/?username=antonio101105&repo=Honeypot&theme=tokyonight&hide_border=true&bg_color=0d1117" alt="Honeypot" /></a>
  <a href="https://github.com/antonio101105/Panel-de-control-para-Windows"><img src="https://github-readme-stats.vercel.app/api/pin/?username=antonio101105&repo=Panel-de-control-para-Windows&theme=tokyonight&hide_border=true&bg_color=0d1117" alt="Panel de control para Windows" /></a>
  <a href="https://github.com/antonio101105/bash"><img src="https://github-readme-stats.vercel.app/api/pin/?username=antonio101105&repo=bash&theme=tokyonight&hide_border=true&bg_color=0d1117" alt="bash" /></a>
  <a href="https://github.com/antonio101105/Pomodoro-Ultimate"><img src="https://github-readme-stats.vercel.app/api/pin/?username=antonio101105&repo=Pomodoro-Ultimate&theme=tokyonight&hide_border=true&bg_color=0d1117" alt="Pomodoro Ultimate" /></a>
</p>

También están mis [apuntes de ASIR](https://github.com/antonio101105/ASIR), por si le sirven a alguien.

---

### Homelab

Lo uso para practicar lo que luego me piden en clase o en el trabajo.

```mermaid
flowchart TB
    subgraph Casa
        PVE["Proxmox VE<br/>VMs + LXC"]
        PC["Portátil de trabajo"]
    end
    subgraph Nube
        OCI["Oracle Cloud ARM"]
        VPS["VPS<br/>Nginx Proxy Manager"]
    end
    TS(("Tailscale"))
    PVE --- TS
    PC --- TS
    OCI --- TS
    VPS --- TS
    VPS --> Internet((Internet))
```

- **Proxmox VE** como servidor central (máquinas virtuales y contenedores LXC)
- **Oracle Cloud** (ARM) para servicios expuestos
- **Tailscale** para unir todo sin abrir puertos
- VPS propios para despliegues web, con Nginx Proxy Manager

---

### Con qué trabajo

<p align="center">
  <img src="https://skillicons.dev/icons?i=linux,windows,bash,powershell,python,cpp,mysql,nginx,wordpress&theme=dark" alt="Tecnologías" />
</p>

- **Sistemas:** Windows Server, Active Directory y GPOs, Linux, Proxmox VE
- **Redes:** routers y switches Cisco, firewalls, VPN
- **Scripting:** Python, Bash, PowerShell. También C++ y SQL
- **Web:** WordPress, Moodle, Drupal
- **Hardware:** montaje, mantenimiento y diagnóstico

### Certificaciones

<p>
  <img src="https://img.shields.io/badge/Cisco-CCST%20Cybersecurity-1BA0D7?style=flat-square&logo=cisco&logoColor=white" alt="CCST Cybersecurity" />
  <img src="https://img.shields.io/badge/Cisco-Junior%20Cybersecurity%20Analyst-1BA0D7?style=flat-square&logo=cisco&logoColor=white" alt="Junior Cybersecurity Analyst" />
  <img src="https://img.shields.io/badge/NDG-Linux%20Essentials-FCC624?style=flat-square&logo=linux&logoColor=black" alt="Linux Essentials" />
  <img src="https://img.shields.io/badge/Python%20Institute-C%2B%2B%20%26%20Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="C++ y Python" />
</p>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1f6feb,50:13294b,100:0d1117&height=110&section=footer" width="100%" alt="" />
