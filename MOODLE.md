## INSTAL·LACIÓ MOODLE

Primer instal·larem el LAMP (apache mariddb i PHP) 
## Apache
![image](https://user-images.githubusercontent.com/114423054/204297735-9024b033-a9a2-4e16-8b4f-04c58187bcd6.png)

## MariaDB
![image](https://user-images.githubusercontent.com/114423054/204298167-39e30ed8-871d-40a5-9900-a14bd8b2bb48.png)

Execució mariadb.

![image](https://user-images.githubusercontent.com/114423054/204298796-27032dfe-b106-4992-8539-d47217532c21.png)

Segidament afegire el repositori PHP.

![image](https://user-images.githubusercontent.com/114423054/204299456-ddcb34b1-5df1-4e72-9043-d86358b8a7d9.png)

Ara instal·lare el PHP 7.3

![image](https://user-images.githubusercontent.com/114423054/204299695-80e09595-1d6a-4c23-89ff-b1e77116a38e.png)

## Ara ja podre començar a instal·lar el moodle.

Primer hem connectare amb SSH per poder avançar més rapid.

![image](https://user-images.githubusercontent.com/114423054/204300667-35948553-445f-4cee-84f0-368bcfdbb581.png)

Després descomprimire l'arxiu.

![image](https://user-images.githubusercontent.com/114423054/204301377-44a395b3-8713-44fb-a17a-777b0d373258.png)

![image](https://user-images.githubusercontent.com/114423054/204301457-4a7f5f58-6f0f-4386-bc41-97b825840565.png)

A continuació crearem els directoris.

![image](https://user-images.githubusercontent.com/114423054/204301945-47916e14-e1cf-481e-b50a-490d9f5bf05f.png)

![image](https://user-images.githubusercontent.com/114423054/204302421-6112e346-e2bd-4ac1-9332-78169bd94806.png)

Configuració base de dades.

![image](https://user-images.githubusercontent.com/114423054/204302694-cab2f39b-e4e2-4c99-a5ea-20055d45f408.png)

![image](https://user-images.githubusercontent.com/114423054/204302886-ad89f1f7-3a08-4873-ad5c-4e964e4948de.png)

Crearem la base de dades de moodle.

![image](https://user-images.githubusercontent.com/114423054/204303186-c58713f3-4486-4fbd-84a9-c11155b98a7d.png)

Per acabar posare privilegis al manager 

![image](https://user-images.githubusercontent.com/114423054/204303688-89afaf21-89cb-454a-baac-954978e6e45b.png)

Ara ja podrem accedir al moodle posan la meua ip /moodle/install.php.

![image](https://user-images.githubusercontent.com/114423054/204304379-c3d814f5-c00f-42df-af58-1be2ae87229c.png)

Ara buscarem el php 

![image](https://user-images.githubusercontent.com/114423054/204305581-c06e2343-3085-4416-a26b-c846a3a68b24.png)

Instal-lo el php dins de moodle.

![image](https://user-images.githubusercontent.com/114423054/204305751-75ac9071-a25b-48bb-b505-c555ea9f4ae6.png)

I el php curl.

![image](https://user-images.githubusercontent.com/114423054/204305991-6285d510-665c-4789-9eb6-e509698435e1.png)

Per acabar reiniciare el servidor.

![image](https://user-images.githubusercontent.com/114423054/204306189-333b3766-c9aa-449e-ab70-700eb348c6a0.png)

Si tornem a entrar posan la ip /moodle/install.php
ens sortira aixó.

![image](https://user-images.githubusercontent.com/114423054/204332963-65eaffad-bf72-49b2-bb80-607fffe4c942.png)

Tindrem que cambiar la ultima destinació per la que hem posat nosaltres /home/moodledata.

![image](https://user-images.githubusercontent.com/114423054/204333295-198393a5-852b-4fb4-ab48-d419b5acc37b.png)

Després ens preguntara quina base de dades volem utilitzar li indicarem la que hem instl·lat mysql

![image](https://user-images.githubusercontent.com/114423054/204334331-288cf6d5-ec1e-4c73-a183-36e50fc64c3e.png)

Finalment renellem les dades 

![image](https://user-images.githubusercontent.com/114423054/204334769-884a6962-a1b9-4ee3-9bf0-5c03af94f81c.png)

Abans de continuar ens demanara també instal·lar el PHP XML.

![image](https://user-images.githubusercontent.com/114423054/204346986-5f9824c9-ad77-4e8e-91d0-e911eb9eb352.png)

També caldra instal·lar aquesta extensió.

![image](https://user-images.githubusercontent.com/114423054/204347272-00b4d8df-f5f8-4a74-a72c-3fe4ceea754a.png)

Ara ja podrem passar a la proxima pantalla.

![image](https://user-images.githubusercontent.com/114423054/204347649-a28edfe0-4f12-4c5c-b833-004d2e3b4b25.png)

Ara ens sortiria les comprovacions si ens falta algo com podem veure a mi me fa falta algunes.

![image](https://user-images.githubusercontent.com/114423054/204348690-ecf491e3-c091-48b4-98b5-b6354df0e78a.png)

![image](https://user-images.githubusercontent.com/114423054/204348639-2aa1002d-fc1b-416b-b643-00712ef5bd54.png)

Anirem arreglant les exensions.

![image](https://user-images.githubusercontent.com/114423054/204348856-f6b4c17f-c0ac-4965-8896-877b31c49e93.png)

Una vegada instal·lats totes les extensions i tot correcte ja estarà.

![image](https://user-images.githubusercontent.com/114423054/204352477-873f1286-d3bf-482a-ac92-a1bf4ad411e5.png)

![image](https://user-images.githubusercontent.com/114423054/204352514-d2da8125-2ff7-4517-babd-68604680e6ce.png)

També he solucionat aquest error cambiant de 1000 a 5000.

![image](https://user-images.githubusercontent.com/114423054/204353557-b25eec4c-821e-4180-bcd1-7d803b268c29.png)

