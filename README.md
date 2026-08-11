# Fray García

**Cloud security y blue team, desde una base ofensiva.** Administrador de sistemas en Lanzarote.

Vengo del lado ofensivo — Active Directory, explotación web, escalada — y ahora trabajo el defensivo y la nube. No es un cambio de tema: saber cómo se ejecuta un ataque es lo que permite decidir qué merece la pena detectar. La escalada de privilegios en IAM de AWS y el abuso de ACL en Active Directory son el mismo problema, un grafo de permisos que nadie ha mirado entero, sobre distinto sustrato.

Escribo lo que investigo en **[fraydgarcia.github.io](https://fraydgarcia.github.io/)**.

---

## Investigación

Análisis propios, con formato de informe. Cada uno lleva una sección de limitaciones que dice qué **no** demuestra el trabajo.

**[La passkey sincronizada no vive en el TPM](https://fraydgarcia.github.io/research/la-passkey-sincronizada-no-vive-en-el-tpm/)**
Tres reglas Sigma para detectar el robo de passkeys de Chrome descrito por Unit 42, y la telemetría que hay que habilitar antes para que lleguen a disparar. Dos de los tres ataques no dejan rastro con una instalación de Sysmon por defecto.

**[El plazo de CISA pasó de 21 días a 3](https://fraydgarcia.github.io/research/el-plazo-de-cisa-paso-de-21-dias-a-3/)**
El catálogo KEV completo, 1.660 entradas, mes a mes: cómo un estándar estable durante cuatro años se desplomó en 2026, y qué implica para un equipo pequeño.

**[Un 5.3 que también es un 9.8](https://fraydgarcia.github.io/research/cve-2026-56164-un-53-que-tambien-es-un-98/)**
Por qué la puntuación base del CVSS no dice lo peligrosa que es una vulnerabilidad en *tu* red, con CVE-2026-56164 como caso.

**[Qué recibe realmente una PYME turística expuesta a Internet](https://fraydgarcia.github.io/research/que-recibe-realmente-una-pyme-turistica/)**
Casi dos meses de honeypot multiservicio midiendo el ruido de fondo de Internet, mapeado a MITRE ATT&CK.

---

## Trabajo

| Proyecto | Qué es |
|---|---|
| **[tfg-honeypot-turismo](https://github.com/fraydgarcia/tfg-honeypot-turismo)** | Honeypot instrumentado para que cada interacción dejara señal: Cowrie para sesiones y comandos, Suricata para red, Elastic para correlación. Proyecto de fin de ciclo, cerrado. |
| **[htb-writeups](https://github.com/fraydgarcia/htb-writeups)** | Writeups de Hack The Box con formato de informe: superficie, acceso, escalada y evidencia, explicando qué señal justifica cada movimiento. Sin auto-exploits y sin flags. |
| **[nmapparser](https://github.com/fraydgarcia/nmapparser)** | Utilidad en Python para parsear y correlacionar resultados de Nmap a lo largo de un reconocimiento extenso. |

---

## Ahora mismo

Preparando **AWS Certified Cloud Practitioner** y el path **CDSA** de Hack The Box — manejo de incidentes, SIEM, caza de amenazas y forense. En paralelo, escribiendo detecciones sobre telemetría de Windows y Sysmon, y trabajando rutas de escalada en IAM sobre cuenta propia de AWS.

El CPTS queda en pausa mientras dure este foco.

---

## Herramientas

| Área | |
|---|---|
| Detección y análisis | Sigma · YARA · Sysmon · Windows Event Logs · Splunk · Elastic · Suricata · Wireshark |
| Cloud | AWS (IAM, VPC, S3, CloudTrail) · Oracle Cloud · Docker |
| Ofensiva | Nmap · Burp Suite · Metasploit · BloodHound · NetExec · ffuf |
| Sistemas | Windows Server · Linux · Active Directory · Zabbix · Grafana |
| Lenguajes | Python · Bash · PowerShell |

---

## Experiencia

**Administrador de Sistemas de TI** · ROSA GROUP · Feb 2026 – Actualidad · Lanzarote
Infraestructura IT de un grupo hotelero. Despliegue de monitorización Zabbix vía Docker sobre más de 50 endpoints y hardening de Windows y Linux siguiendo guías CIS.

**Administrador de Sistemas de TI (formación dual)** · Gobierno de Canarias · Ene 2025 – Mar 2025 · Lanzarote
Gestión de Active Directory —usuarios, GPO, identidades— e identificación de configuraciones débiles desde perspectiva ofensiva. Automatización con Bash y virtualización QEMU/KVM.

---

## Formación

**Técnico Superior en ASIR** · CIFP Zonzamas · Sep 2024 – Jun 2026
Nota media 9,80. Mención honorífica en Seguridad y Alta Disponibilidad.

### Certificaciones

| Certificación | Estado |
|---|---|
| AWS Certified Cloud Practitioner (CLF-C02) | En preparación |
| CDSA — Certified Defensive Security Analyst (HTB) | En preparación |
| CPTS — Certified Penetration Testing Specialist (HTB) | En pausa |

### Cursos y credenciales

| Curso | Emisor | Año |
|---|---|---|
| Junior Cybersecurity Analyst | Cisco Networking Academy | 2025 |
| Cyber Threat Management | Cisco Networking Academy | 2025 |
| Network Defense · Endpoint Security | Cisco Networking Academy | 2024 |
| Introduction to Cybersecurity · Networking Basics | Cisco Networking Academy | 2024 |
| Certified Fundamentals in Cybersecurity | Fortinet | 2025 |
| Cybersecurity Fundamentals | IBM | 2025 |
| Introduction to Amazon VPC (laboratorio) | AWS | 2025 |

---

## Contacto

[Web](https://fraydgarcia.github.io/) · [LinkedIn](https://linkedin.com/in/fraineltomas) · [Hack The Box](https://app.hackthebox.com/users/2163518) · [Correo](mailto:fraydgarcia@proton.me)
