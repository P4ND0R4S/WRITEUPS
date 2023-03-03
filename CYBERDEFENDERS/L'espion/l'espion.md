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

#### ➤ Q4
**What university did the insider go to?**

Hacemos una búsqueda de google y encontramos su perfil de Linkedin.

![imagen](https://user-images.githubusercontent.com/126393691/222688671-6be71e75-fd8d-45b2-891f-7573bd62ef0c.png)
> Sorbonne

#### ➤ Q5
**What gaming website the insider had an account on?**

Volvemos a hacer una búsqueda en google y nos encontramos con su instagram,entramos y vemos que tiene una foto con un codigo QR que menciona algo de videojuegos.

![imagen](https://user-images.githubusercontent.com/126393691/222690556-a1c76084-621f-481c-942a-63323653fa36.png)

Usamos un [QR Scanner](https://www.qrscanner.org/) el QR nos lleva a un enlace de Steam.

![imagen](https://user-images.githubusercontent.com/126393691/222691280-513ed23f-13db-4170-a1d7-7067ec9caf05.png)
> Steam

#### ➤ Q6
**What is the link to the insider Instagram profile?**

![imagen](https://user-images.githubusercontent.com/126393691/222691891-36de456f-235c-4aa0-a837-2d2a592783e6.png)
> https://www.instagram.com/emarseille99/

#### ➤ Q7
**Where did the insider go on the holiday? (Country only)**

Hechamos otro vistazo en Instagram y vemos que tiene una foto en Singapur,que menciona sus vacaciones. 

![imagen](https://user-images.githubusercontent.com/126393691/222692512-bedac016-4b03-474f-bb52-7b4bbc7ca4b8.png)
> Singapore

#### ➤ Q8
**Where is the insider's family live? (City only)**

Seguimos mirando su instagram y vemos que tiene varias fotos en Dubai en las que menciona a su familia. (si no sabeis viendo las fotos donde son, simplemente usar la busqueda inversa, lo mismo con la pregunta anterior).

![imagen](https://user-images.githubusercontent.com/126393691/222693022-47565838-8229-4c5e-9d65-697631b848a9.png)
> Dubai

#### ➤ Q9
**File -> office.jpg:** <br>
**You have been provided with a picture of the building in which the company has an office. Which city is the company located in?** 

abrimos la imágen que nos han proporcionado y buscamos por el nombre del teatro y nos dice el nombre de la ciudad (hay distintas maneras de averiguarlo)

![imagen](https://user-images.githubusercontent.com/126393691/222695580-9199158f-ba22-466f-8997-49e2d5868ac0.png)
> Birmingham

#### ➤ Q10
**File -> Webcam.png:** <br>
**With the intel, you have provided, our ground surveillance unit is now overlooking the person of interest's suspected address. They saw them leaving their apartment and followed them to the airport. Their plane took off and has landed in another country. Our intelligence team spotted the target with this IP camera. Which state is this camera in?**

Hacemos una búsqueda rapida en google y averiguamos que se trata de la universidad de Notre Dame en EE.UU.

![imagen](https://user-images.githubusercontent.com/126393691/222696974-25db5a12-0e77-4e72-b3a4-c81488c3866e.png)
> Indiana
