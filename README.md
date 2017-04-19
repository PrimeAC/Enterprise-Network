# Enterprise-Network
Project using Netkit that emulates an enterprise network.


Command to start Lisbon and Porto, and router in SEDE, to test their connection:

lstart -p routerP routerL routerS switch1P switch1L pc_conta1P pc_conta2P pc_conta1L pc_conta2L pc_visit1L pc_visit2L pc_visit1P pc_visit2P

Command to start only vm's from the sede:
lstart -p dns_emailS dns_httpS ficheirosS monitorS pc_contabilistaS pc_diretorS pc_r_hS proxy_httpS routerS switch_adminS switch_privadaS switch_publicaS

Command to start only vm's from the Porto:
lstart -p pc_contabilista1P pc_contabilista2P routerP switchP

Command to start only vm's from the Lisboa:
lstart -p pc_contabilista1L pc_contabilista2L routerL switchL

Command to start only vm's from the External LAN:
lstart -p pc_clienteE pc_contabilista2P dns_http_emailE routerE

Command to start only vm's from the ISP:
lstart -p dnsISP routerISP routerS routerP routerL routerE

