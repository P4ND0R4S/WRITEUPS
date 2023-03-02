![imagen](https://user-images.githubusercontent.com/126393691/222401430-4b12dd1c-3b33-4491-9478-4d7dd0bbd2db.png)

#

![imagen](https://user-images.githubusercontent.com/126393691/222400113-cc1e2dde-8774-4b23-99f1-d294fc377833.png)

#

### $\color{#000000}{𝗜𝗡𝗙𝗢𝗥𝗠𝗔𝗖𝗜Ó𝗡}$
You have been tasked by a client whose network was compromised and brought offline to investigate the incident and determine the attacker's identity.

Incident responders and digital forensic investigators are currently on the scene and have conducted a preliminary investigation. Their findings show that the attack originated from a single user account, probably, an insider.

Investigate the incident, find the insider, and uncover the attack actions.

#

### $\color{#000000}{𝗜𝗡𝗦𝗧𝗥𝗨𝗖𝗖𝗜𝗢𝗡𝗘𝗦 \ 𝗬 \ 𝗛𝗘𝗥𝗥𝗔𝗠𝗜𝗘𝗡𝗧𝗔𝗦}$
- Uncompress the challenge (pass: cyberdefenders.org)
- Google Maps
- Google Image search
- Sherlock

#

### $\color{#000000}{𝗠𝗘𝗧𝗢𝗗𝗢𝗟𝗢𝗚Í𝗔}$
Descarga los archivos del reto y obtendras un archivo de texto <br> y dos imágenes . El archivo de texto contiene un enlace a <br> una cuenta de GitHub. 

#### ➤ Q1
**File -> Github.txt:** <br>
**What is the API key the insider added to his GitHub repositories?** 

Nos dirigimos al único repositorio de github creado por la cuenta que nos han proporcionado, y ahi nos encontramos con un archivo `login page.js`.

![imagen](https://user-images.githubusercontent.com/126393691/222410895-87e53023-4720-4b9c-86b7-a460aba03d74.png)

Dentro nos encontraremos con la **API Key** 
>aJFRaLHjMXvYZgLPwiJkroYLGRkNBW

#### ➤ Q2
**File -> Github.txt:** <br>
**What is the plaintext password the insider added to his GitHub repositories?**

En el mismo archivo que antes, nos encontramos con una contraseña en **base64**.

![imagen](https://user-images.githubusercontent.com/126393691/222412586-50898aa8-7256-4123-a518-4be762492df6.png)

para decodificarla yo usaré [Base64 Decode](https://www.base64decode.org/) (podeis usar cualquiera)
>PicassoBaguette99

#### ➤ 𝗤3
**File -> Github.txt:** <br>
**What cryptocurrency mining tool did the insider use?** 

En el github del objetivo buscamos en sus repositorios y encontramos la mining tool que usa.

![imagen](https://user-images.githubusercontent.com/126393691/222417202-8f7a80b2-653c-4a08-942a-f9f295dd9710.png)
> Xmrig
