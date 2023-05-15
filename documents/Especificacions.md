
### Equip: 

	-Pau Bofill Collado: 	1635944
	-Igor Pisarenko: 	1639543
	-Pau López: 		1603995 
	-Adrià Gil Martinez : 	1633884

### Enllaços: 
	
	-Github: 	https://github.com/Paub2002/ES23UAB-432-03.git
	-Azure:		https://dev.azure.com/UAB-EngSw-2023-432-03/ES23UAB-432-03

### Requisits 

		-ID | Funcional	/no funcional:  [Title_version](requisit link): Description . [relations ID](relation link) // (Coments)


#### Botigues i Transportistes 
	- 01-01 | Funcional	: Plataforma de serveis			: Infraestructura per demanar els serveis oferits. Això inclou un sistema per que els clients demanin una comanda, els botiguers ofereixin els seus productes, i el contacte transportistes que pugin ser avisats si es requereix.
	- 01-02 | No Funcional	: Crear noves fonts d'ingresos		: Crear noves fonts d'ingressos a la zona mitjançant la feina que oferim als locals com a transportistes, ja que no escollirem empreses de transportistes ni altres grups empresarials.

#### Comandes 
	- 02-01 | Funcional	: Solicitud de comanda 1.0		: Acció a emprendre dins de la plataforma, mitjançant unes especificacions introduïdes previament.
	- 02-02 | Funcional	: Presentació d'ofertes 1.0		: La plataforma presentara al client ofertes que li puguin interesar. 
	- 02-03 | Funcional	: Seleccio de comandes i enviament	:  Acció a emprendre dins de la plataforma, mitjançant unes especificacions introduïdes previament, la plataforma al oferent el que s'ha demanat i fará els pasos necessaris per complir el pagament i enviament segons les preferencies del client
	- 02-11 | No funcional	: Ui de la comanda amigavle		: Mentre el client faci la seva sol·licitud, es té que sentir cómode no només amb la implementació intuitiva de l'aplicació sinó també amb el seu disseny que té que considerar amigable.
	- 02-04 | Funcional	: Implementació d'un algoritme que identifiqui els productes que vol el client i els compari amb l'estoc de les tendes oferents, per a que no tingui que fer ell/ella la selecció dels productes.
	- 02-12 | No funcional	: Llistat de presentació d'ofertes	: El format en el que es presentarán les ofertes será: Llistat de productes que li enviem, per cada producte la seva quantitat, preu, marca i altres especificacions. Després esmentarem el día i hora de l'entrega, finalment hi haurá el preu total que inclourá els càrrecs adicionals com transport, iva, etc...
	- 02-05 | Funcional	: Enviament				: Una vegada la comanda s'ha confirmat per el client, l'oferent ha de rebre una notificació amb les especificacions a complir.
	- 02-13 | No Funcional	: Informe del producte			: Una vegada la comanda s'ha confirmat per el client, el client rebrá un informe de l'estat de la comanda que s'actualitzará en temps real.
	- 02-14 | No Funcional  : Format  Informe del producte		: Quan el client rebi un informe de l'estat de la comanda que s'actualitzará en temps real, els possibles estats de la comanda serán : comanda rebuda per la tenda, en preparació de la comanda, distribuint la comanda.
	- 02-15 | No funbcional : Capacitat per usuari de comandes	: Cada usuari ha de poder tenir com a máxim 100 comandes .


#### Pagaments
	- 03-01 | Funcional	: Sistema de pagaments			: La plataforma ha de tenir un sistema integrat de pagament per a que els clients, transportistes i oferent puguin fer les transaccions diferents, i nosaltres cobrar una comisió.
	- 03-11 | No Funcional	: Métodes de pagament			: Els metodes de pagament que es podrán utilitzar inclouen: Efectiu, Paypal o Targeta de crédit.
	- 03-02 | Funcional	: Comisió de ENCASA			: Una vegada el pagament entre client i oferent s'hagi completat, haurem pactat amb la botiga una comisió que ens pertoca i l'haurem de substreure dels seus ingressos.
	- 03-12 | No Funcional  : Ordre d'execució del pagament		: El client efectuará el pagament en el moment d'acceptar una de les ofertes proposades. Efectuará el pagament amb alguna de les opcions proposades i una vegada efectuat la comanda s'efectuará.
	- 03-04 | Funcional	: Sistema d'abonaments			: Si un client no está d'acord amb l'entrega podrá seleccionar el retorn de pagament dins de l'aplicació per a que se l'hi retorni els diners. Hi haurá un procés extern per avaluar aquests casos.
	- 03-13 | No Funcional	: Comisió en cad d'abonament		: Independentment de si el client ha demanat l'abonament, ENCASA ja haurá cobrat la comisió. Ja que es responsabilitat del botiguer l'integritat del producte.
	- 03-14 | No Funcional  : Garantía de la seguretat del client	: El client ha de estar segur de que els seus diners están segurs, i que a qualsevol incidencia amb la seva comanda els podrá tenir si ho considera necessari.
	- 03-05 | Funcional	: Gestió de la seguretat del botiguer	: Si el botiguer considera que ha sigut ultrajat amb comandes anul·lades o altres, el botiguer podrá presentar una reclamació, que nosaltres gestionarem per métodes externs.
	- 03-15 | No Funcional  : Gestió de la seguretat del botiguer	: El botiguer es te que sentir protejit sobre les reclamacions del client o cancel·lacions fora de temps.



#### Transports 
	- 04-01 | Funcional 	: Real Time traking 1.0			: El viatge que fa el transportista sera monotoritzat i enmagatzemat en temps real per la aplicació i podra ser consultat per a saber a on esta el paquet. // Aquesta informacio sera utilitzada per a calcular els costos de transport.
	- 04-02 | Funcional 	: Calcul costos transport 1.0		: L'aplicacio s'encarrega de calcular el cost del transport utilitzant la informacio de la distancia del trajecte enmagatzemada. Es calcula sobre el total del mes. 04-01, 04-10. // Nomes aplica a els transportistes contractats a traves de la aplicació.
	- 04-10 | No Funcional 	: Pagaments tranportistes 1.0		: L'empresa de ENCASA sera la que gestionara el pagament a cada transportista contractat per la aplicació. SENSE COBRAR COMISIO. Pagaments mensuals. 04-01,04-02
	- 04-11 | No Funcional 	: Cost Client 1.0			: El cost del transport que veu i paga el client es fixat i sera decidit per a la botiga independentment del cost real que tingui despres. Per a fer mes senzill saber quin hauria de ser aquest cost hi haura una eina dedicada a calcular-lo. 04-03.
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
### Usuaris: 
		- Botiga
		- Transportista
		- Client
		- Admin
		- Proveïdor Extern (Anuncis)
