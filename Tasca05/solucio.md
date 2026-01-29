# T05: Instal·lació del domini

### En primer lloc anirem a la configuració de xarxa i canviarem el DNS.

<img width="841" height="677" alt="image" src="https://github.com/user-attachments/assets/e33eacf9-2bed-4580-983e-60269211ac60" />

### Seleccionem "Manual" > "IPv4" ,posem de DNS: 127.0.0.1 i prenem "Save"

<img width="503" height="625" alt="image" src="https://github.com/user-attachments/assets/a0eccc4e-7797-440b-9830-4e1f4fe3fa8e" />

### Ara instl·larem el "Rol Domain Services", anem a "Manage" i clickem a "add roles and features"

<img width="1023" height="551" alt="image" src="https://github.com/user-attachments/assets/dd4b6510-0dac-43a8-9918-a92a36d4acb6" />

### Seleccionem la opció marcada en la captura de pantalla i prenem "Next"

<img width="839" height="652" alt="image" src="https://github.com/user-attachments/assets/c2f3fb7e-9779-4d5d-b86d-ce1fbf5a4b54" />

### Prenem "Next"

<img width="857" height="595" alt="image" src="https://github.com/user-attachments/assets/1df05683-9d8a-41a0-96a2-b9148d52acba" />

### Activem la opció de "Active Directory Domain Services", prenem "Add Features" i a continuació "Next"

<img width="1017" height="767" alt="image" src="https://github.com/user-attachments/assets/5bb72115-99c6-4e63-8e2a-3f33ab620b0c" />

### Prenem "Next"

<img width="916" height="699" alt="image" src="https://github.com/user-attachments/assets/78f25a6c-658a-4e46-a4f3-
242eee5dc41c" />

### Prenem "Next"

<img width="842" height="619" alt="image" src="https://github.com/user-attachments/assets/c7ac9dbc-b142-490a-882e-389528e4ef95" />

### Prenem "Install"

<img width="843" height="633" alt="image" src="https://github.com/user-attachments/assets/9fe5c3b4-016a-422b-811d-0b7fd7564986" />

### Un cop se'ns ha instal·lat, anem a la "Alerta" i prenem a "Promote this server to a domain controller" com surt a la captura de pantalla"

<img width="945" height="742" alt="image" src="https://github.com/user-attachments/assets/7f44af87-b8d9-4211-9915-1a1b0bd614dd" />

### Prenem a "Add a new forest" per crear un nou bosc, afegim el nostre domini "translogic18.test" i prenem "Next"

<img width="792" height="610" alt="image" src="https://github.com/user-attachments/assets/9f29f79d-543f-4d4c-9a91-55d36b4f7b9f" />

### Afegim la nostra contrasenya i oreb en "Next"

<img width="825" height="627" alt="image" src="https://github.com/user-attachments/assets/4e9c7993-ab70-4630-94e0-20e574d897ec" />

### Prenem "Next"

<img width="798" height="622" alt="image" src="https://github.com/user-attachments/assets/b1b91120-8c6e-4505-b31f-81cb5ae24cc2" />

### Prenem "Next"

<img width="858" height="649" alt="image" src="https://github.com/user-attachments/assets/f6fbec7f-6c00-4e6d-aaca-f4df73f6ea55" />

### Prenem "Next"

<img width="816" height="612" alt="image" src="https://github.com/user-attachments/assets/23e2f052-a563-4456-bc76-7b8e758a3f37" />

### Prenem "View Script"

<img width="806" height="589" alt="image" src="https://github.com/user-attachments/assets/f61a46cf-f350-42b4-ab02-09e1bba61ec6" />

### Ens guardem la script "Edit" > "Save As"

<img width="807" height="602" alt="image" src="https://github.com/user-attachments/assets/42b1e4b2-97c4-4b18-82a5-1bcbabb71a5a" />

### Ho guardem a documents

<img width="761" height="550" alt="image" src="https://github.com/user-attachments/assets/3f02adb3-a333-4723-a908-dbc8a69ba319" />

### Prenem "Next"

<img width="798" height="600" alt="image" src="https://github.com/user-attachments/assets/9dc984a8-b82c-4729-b647-04d62644cb47" />

### Prenem "Install"

<img width="834" height="627" alt="image" src="https://github.com/user-attachments/assets/0003c0bb-fec4-4fde-bed4-d2aba4786e7c" />

### Despres de que es reinci la màquina, ens loguejem com administrador de domini

<img width="955" height="792" alt="image" src="https://github.com/user-attachments/assets/16a0351d-80d1-4e9f-875a-3d8ef68204d0" />

### Canviem l'hora perque per defecte es posa en horari Estats Units, anem a "Settings" > "Time & security" > "Date & Time" i la canviem a horari de españa

<img width="858" height="653" alt="image" src="https://github.com/user-attachments/assets/11fb2753-15ed-4604-8904-22b9e28ed7df" />

### Ara anem a "DNS" , click dret a sobre del nostre DNS i prenem a "DNS Manager"

<img width="961" height="785" alt="image" src="https://github.com/user-attachments/assets/a44b4db1-7f60-47b4-885e-422463cd00d6" />ç

### Entrem dintre del domini, prenem "Forwarders" > "Edit"

<img width="801" height="699" alt="image" src="https://github.com/user-attachments/assets/a981c139-5f17-43fc-82ee-3c204dce6c9d" />

### Configurem el dns, 8.8.8.8 i li donem "Apply" i "OK"

<img width="868" height="745" alt="image" src="https://github.com/user-attachments/assets/923e2fa6-3891-48c5-8d68-6501b3ac475c" />




⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⣀⣤⣴⣶⣶⣶⣤⣤⣀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⢀⣴⣿⡿⠟⠛⠉⠉⠛⠻⢿⣿⣷⣄⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⢀⣴⣿⡿⠋⠀⠀⠀⠀⠀⠀⠀⠀⠙⢿⣿⣦⡀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⢠⣿⣿⡟⠀⠀⠀⣀⣤⣤⣤⣀⠀⠀⠀⠈⢿⣿⣿⡄⠀⠀⠀⠀⠀
⠀⠀⠀⠀⣼⣿⣿⡇⠀⢠⣾⡿⠛⠛⠛⢿⣷⡄⠀⠀⢸⣿⣿⣧⠀⠀⠀⠀⠀
⠀⠀⠀⢸⣿⣿⣿⡇⠀⣿⣿⠀⠀⠀⠀⠀⣿⣿⠀⠀⢸⣿⣿⣿⡇⠀⠀⠀⠀
⠀⠀⠀⢸⣿⣿⣿⡇⠀⣿⣿⣀⠀⠀⠀⣀⣿⣿⠀⠀⢸⣿⣿⣿⡇⠀⠀⠀⠀
⠀⠀⠀⠀⣿⣿⣿⣧⠀⠙⢿⣿⣦⣀⣴⣿⡿⠋⠀⣰⣿⣿⣿⣿⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠘⣿⣿⣿⣦⡀⠀⠙⠻⠿⠿⠋⠀⢀⣴⣿⣿⣿⣿⠃⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠈⢿⣿⣿⣿⣦⣄⠀⠀⠀⣠⣴⣿⣿⣿⣿⡟⠁⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠙⢿⣿⣿⣿⣿⣶⣿⣿⣿⣿⡿⠋⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠈⠻⢿⣿⣿⣿⡿⠟⠁⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠈⠉⠁⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
