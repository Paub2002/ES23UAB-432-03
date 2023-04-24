
###Equip: 

	-Pau Bofill Collado: 	1635944
	-Igor Pisarenko: 	1639543
	-Pau López: 		1603995 
	-Adrià Gil Martinez : 	1633884

###Enllaços: 
	
	-Github: 	https://github.com/Paub2002/ES23UAB-432-03.git
	-Azure:		https://dev.azure.com/UAB-EngSw-2023-432-03/ES23UAB-432-03

###Requisits 

		-ID | Funcional 	/no funcoinal:  [Title_version](requisit link): Description . [relations ID](relation link) // (Coments)


#### Botigues i Transportistes 
#### Comandes 
#### Pagaments
#### Transports 
	- 04-01 | Funcional 	: Real Time traking 1.0			: El viatge que fa el transportista sera monotoritzat i enmagatzemat en temps real per la aplicació i podra ser consultat per a saber a on esta el paquet. // Aquesta informacio sera utilitzada per a calcular els costos de transport.
	- 04-02 | Funcional 	: Calcul costos transport 1.0		: L'aplicacio s'encarrega de calcular el cost del transport utilitzant la informacio de la distancia del trajecte enmagatzemada. Es calcula sobre el total del mes. 04-01, 04-10. // Nomes aplica a els transportistes contractats a traves de la aplicació.
	- 04-10 | No Funcional 	: Pagaments tranportistes 1.0		: L'empresa de ENCASA sera la que gestionara el pagament a cada transportista contractat per la aplicació. SENSE COBRAR COMISIO. Pagaments mensuals. 04-01,04-02
	- 04-11 | No Funcional 	: Cost Client 1.0: El cost del transport que veu i paga el client es fixat i sera decidit per a la botiga independentment del cost real que tingui despres. Per a fer mes senzill saber quin hauria de ser aquest cost hi haura una eina dedicada a calcular-lo. 04-03.
	- 04-03 | Funcional	: Aproximacio cost transport 1.0	: L'aplicacio s'encarrega d'aproximar el cost del transport utilitzant la informacio dels viatges previs i un calcul de la ruta aproximada. 04-01. 
#### Publicitat
	- 05-01 | Funcional 	: Publicitat 1.0			: L'app mostrara diferents banners de publicitat als clients. Entre 1 i 6 per oferta. 05-11 // L'objectiu de la aplicacio no es generar el maxim possible amb la publicitat, per tant es prioritzara que els anuncis no siguin invasius.
	- 05-11 | No Funcional 	: Google ads 1.0			: El servei utilitzat per a mostrar la publicitat sera google ads. 
#### Registre i acceés
	- 06-03 | Funcional 	: Login 1.0				: S'implementara un sistema de login.
	- 06-02 | Funcional 	: Registre transportistes 1.0		: Els transportietes hauran de autentificar totes les seves dades fiscals per motius legals. 
	- 06-11 | No Funcional	: Acces aplicacio 1.0			: Tots els usuaris poden asccedir de les mateixes formes, tot i que cada un tindra continguts diferents depenent del seu perfil. 
#### Altres 
	- 07-01 | Funcional 						: Base de dades 1.0 : Hi ha haura una base de dades relacional amb inrefície SQL (PostgreSQL)
	- 07-02 | Funcional 						: Disponibilitat de la plataforma 1.0 : Per garantir el funcionament de plataforma 24/7 i manteniment necessari, s'utilitzarà DigitalOcean com a proveïdor de IaaS.
	- 07-11 | No Funcional 	: Política empresarial 1.0		: Disseny suposa que totes les UI tindran el logo de la plataforma, el color majoritàriament serà groc i només es pot fer servir tipografies Open Source.
###Usuaris: 
		-Botiga
		-Transportista
		-Client
		-Admin
