🚫🔒 Lista de bloqueo avanzada para AdGuard Home
🌐 Bloquea contenido para adultos y acceso a VPN/proxies

📋 Descripción
Lista personalizada para AdGuard Home que bloquea:

🚫 Contenido para adultos: Sitios de pornografía, apuestas y citas.

🛡️ VPN y proxies: Servicios de navegación anónima y evasión de restricciones.

⚙️ Funciona con:

AdGuard Home (configuración DNS).

Routers (pfSense, OpenWRT).

Dispositivos (control parental integrado).

🔍 Cómo usar
Añade la lista en AdGuard Home:

Ve a Configuración → Listas de bloqueo DNS.

Ingresa la URL "raw" del archivo blocklist.txt.

Refuerza con herramientas externas:

Pi-hole o DNS filtrado (ej: Cloudflare 1.1.1.2) para bloquear automáticamente malware y adultos.

📝 Ejemplo de reglas
text
! 🚫 Bloqueo de contenido para adultos y VPN/proxies  
🔒||pornhub.com^  
🔒||xvideos.com^  
🔒||bet365.com^  
🔒||expressvpn.com^  
🔒||hidemyass.com^  
🔒||*.vpn.*  
🔒||*.proxy.*  
📌 Notas:

Actualiza manualmente el archivo blocklist.txt para añadir nuevos dominios.

Combina con control parental en dispositivos para mayor seguridad.

🌟 Contribuye: Si encuentras dominios no bloqueados, ¡abre un issue o envía un pull request!

🔗
