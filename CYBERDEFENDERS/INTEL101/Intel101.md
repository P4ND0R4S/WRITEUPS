![imagen](https://user-images.githubusercontent.com/126393691/222701426-a088a4ee-9c45-4e96-9387-ab016870a912.png)

#

![imagen](https://user-images.githubusercontent.com/126393691/222701611-73f7363f-3c2d-41e4-bd93-efac8a55446e.png)


#

### $\color{#000000}{ππ‘ππ’π₯π πππΓπ‘}$
Open-source intelligence (OSINT) exercise to practice mining and analyzing public data to produce meaningful intel when investigating external threats.

#

### $\color{#000000}{ππ‘π¦π§π₯π¨ππππ’π‘ππ¦ \ π¬ \ πππ₯π₯ππ πππ‘π§ππ¦}$
- Google Lens
- archive.org
- WhoIS


#

### $\color{#000000}{π ππ§π’ππ’ππ’πΓπ}$
Descargamos los archivos del reto y obtenemos una imagen.

#### β€ Q1
**Who is the Registrar for jameskainth.com?**

vamos a una pΓ‘gina para obtener informaciΓ³n sobre webs [ViewDnsInfo](https://viewdns.info/). Buscamos por whois.

![imagen](https://user-images.githubusercontent.com/126393691/222703049-47ae2b59-c568-44ea-8a3e-cf138dbd8151.png)
> Namecheap

#### β€ Q2
**You get a phone call from this number: 855-707-7328, they were previously known by another name? (No spaces between words)**

Hacemos una bΓΊsqueda en google de el nΓΊmero y vemos que pertenece a la compaΓ±ia Spectrum.Posteriormente buscamos en google cual era su nombre original.

![imagen](https://user-images.githubusercontent.com/126393691/222706169-233165a2-679a-43e6-b9fc-da39c282cf1e.png)
> Timewarnercable

#### β€ π€3
**What is the Zoom meeting id of the British Prime Ministers Cabinet Meeting?**

Hacemos una bΓΊsqueda rapida en google y encontramos un articulo donde aparece el ID del zoom.

![imagen](https://user-images.githubusercontent.com/126393691/222707166-569ccdff-432a-4401-a036-407b580e382f.png)
>539544323

#### β€ Q4
**What Percentage of full-time degree-seeking freshmen from the fall of 2018 re-enrolled to <br> Champlain in the fall of 2019?** 

No pude encontrar nada, asi que use una pista en la que te daban una pagina web: https://ucan-network.org/champlain, pero no habΓ­a ninguna informaciΓ³n asi que me fui a la waybackmachine y econtrΓ© el dato.

![imagen](https://user-images.githubusercontent.com/126393691/222711289-4e797d63-3aba-46b6-b78d-ecc7e2881bd0.png)


![imagen](https://user-images.githubusercontent.com/126393691/222711215-7b738afd-2df8-4ff7-be10-11669509c9e6.png)
>82.5%

#### β€ Q5
**Champlain College Has A Public Excel Sheet Listing Addresses Of Campus Locations Available on <br> The Internet, whatβs the SHA256 hash of the excel file?**

No es posible contestar a esta pregunta ya que el archivo ya no estΓ‘ disponible.

#### β€ Q6
**In 1998 specifically on February 12th, Champlain was planning on adding an exciting new building to its campus. Back then, it was called βThe Information Commonsβ. Can you find a picture of what the inside would look like? Upload the sha256 hash here.***

Primero hice una bΓΊsqueda rapida en google pero no encontre ningΓΊn resultado relevante, asi que fui a la pagina oficial de la universidad y abrΓ­ waybackmachine, resulta que tenian la pΓ‘gina guardada el 12 de febrero de 1998 con fotos de dentro del edificio.

![imagen](https://user-images.githubusercontent.com/126393691/222716250-fc03e4f5-fb8a-483f-8251-ac624ee5e6eb.png)
>f4952b314eb15acf0eec79c954f83881c17d50d2b5922ee37e8fc5e5cd1aeac2

#### β€ Q7
**One of Champlain College's Cyber Security Faculty got a bachelor's degree in arts from this <br> Ohioan university. Who was the other faculty member who studied there? (FirstName LastName - two words)**

Hacemos una busqueda en google `champlain college cyber security faculty`. entramos en la pΓ‘gina de la universidad y vemos que hay uno que estudio arte en la universidad de Toledo

![imagen](https://user-images.githubusercontent.com/126393691/222891241-7a7567c1-36cf-4994-a9c6-224160b219a4.png)

Comprobamos que la universidad de Toledo estΓ‘ en Ohio. A continuaciΓ³n usaremos Dorks para comprobar que otros profesores han estudiado en la universidad de Toledo `inurl:champlain.edu/academics/our-faculty University of Toledo`. 

![imagen](https://user-images.githubusercontent.com/126393691/222891373-6873c2d9-7e9d-4508-b76d-a5b41c6a2b42.png)
> Todd Schroeder

#### β€ Q8
**In 2019 UVMβs Ichthyology Class Had to Name their fish for class. Can you find out what the last <br> person on the public roster named their fish?**

No es posible completar esta pregunta ya que no se tiene acceso a la web.

#### β€ Q9
**Can You Figure Out Which State This Picture Has Been Taken From? See attached photo**

Hacemos una bΓΊsqueda inversa de la imagen en las distintas webs. Observamos que en bing nos aparece la imΓ‘gen.

![imagen](https://user-images.githubusercontent.com/126393691/222896313-c13e33c5-3358-4c6f-80f9-e72c73caab76.png)

pero no obtenemos mucha informaciΓ³n. Vemos que la imΓ‘gen de al lado se aprece tambien y menciona algo de Dinosaur Land, lo buscamos en google, miramos fotos del parque y encontramos la imΓ‘gen

![imagen](https://user-images.githubusercontent.com/126393691/222896480-6c6d3f78-b3c5-4c1b-bbed-4f7a4efc118f.png)
>Virginia
