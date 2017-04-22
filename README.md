# Enterprise-Network
Project using Netkit that emulates an enterprise network.


Command to start Lisbon and Porto, and router in SEDE, to test their connection:

lstart -p routerP routerL routerS switch1P switch1L pcConta1P pcConta2P pcConta1L pcConta2L pcVisit1L pcVisit2L pcVisit1P pcVisit2P

Command to start only vm's from the sede:
lstart -p ns1S ns2S ficheirosS monitorS pcContabilistaS pcDiretorS pcRHS proxyS routerS switchAdminS switchPrivadaS switchPublicaS

Command to start only vm's from the Porto:
lstart -p pcContabilista1P pccontabilista2P routerP switchP

Command to start only vm's from the Lisboa:
lstart -p pcContabilista1L pcContabilista2L routerL switchL

Command to start only vm's from the External LAN:
lstart -p pcClienteE pcContabilista2P nsE routerE

Command to start only vm's from the ISP:
lstart -p dnsISP routerISP routerS routerP routerL routerE

