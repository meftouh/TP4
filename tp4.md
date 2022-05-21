


### 

dans les activités précédentes on a développé une architecture monolithic avec node js (express)

on avait un seul service (crud + authentication authorization)


dans cette activité on va créer une architecture (microservices)

donc on a séparé le seul service monolithique  sur trois services: crud , client , auth  ( figure 1)
        

         L'API:

         -  service 1 (auth) : authentication  + authorization

         -  service 2 (CRUD) :  (Create, read, update and delete ) ce service permet de insérer et supprimer  et
modifier et faire la lecture   des  données annonce vente 

 ----------------------------------------------
       frontend :


         -  service 3(clinet) : on a utilisé la bibliothèque React + Redux pour créer le frontend 


--------------------------------------
 
![](https://file%2B.vscode-resource.vscode-cdn.net/Users/md/Desktop/node_test/images/Capture%20d%E2%80%99%C3%A9cran%202022-05-21%20%C3%A0%2017.46.44.png?version%3D1653151665573)

(figure 1)


--------------------------------------------
## service 1 (auth) (API)
 #### signup (S'inscrire)


![](https://file%2B.vscode-resource.vscode-cdn.net/Users/md/Desktop/node_test/images/Capture%20d%E2%80%99%C3%A9cran%202022-05-21%20%C3%A0%2018.26.58.png?version%3D1653154395552)



pour  la vérification  de username (si username  existe sur la database users le le message s'affiche (" Failed! Username is already in use!"))
![](https://file%2B.vscode-resource.vscode-cdn.net/Users/md/Desktop/node_test/images/Capture%20d%E2%80%99%C3%A9cran%202022-05-21%20%C3%A0%2018.35.28.png?version%3D1653155071166)


et pour  la vérification  de email (si email  existe sur la database users le le message s'affiche ("Failed! Email is already in use "))

![](https://file%2B.vscode-resource.vscode-cdn.net/Users/md/Desktop/node_test/images/Capture%20d%E2%80%99%C3%A9cran%202022-05-21%20%C3%A0%2018.40.18.png?version%3D1653155092090)------------------------------------------------

### signin
pour login




![](https://file%2B.vscode-resource.vscode-cdn.net/Users/md/Desktop/node_test/images/Capture%20d%E2%80%99%C3%A9cran%202022-05-21%20%C3%A0%2018.27.41.png?version%3D1653154412071)








------------------------------------------------
## service 2 (CRUD)  (API)

![](https://file%2B.vscode-resource.vscode-cdn.net/Users/md/Desktop/node_test/images/Capture%20d%E2%80%99%C3%A9cran%202022-05-21%20%C3%A0%2018.47.46.png?version%3D1653155303945)


-----------------------------------------------

service 3 (clinet) (frontend)

pour register


![](https://file%2B.vscode-resource.vscode-cdn.net/Users/md/Desktop/node_test/images/Capture%20d%E2%80%99%C3%A9cran%202022-05-21%20%C3%A0%2018.51.34.png?version%3D1653155805759)


![](https://file%2B.vscode-resource.vscode-cdn.net/Users/md/Desktop/node_test/images/Capture%20d%E2%80%99%C3%A9cran%202022-05-21%20%C3%A0%2018.51.41.png?version%3D1653155826933)



![](https://file%2B.vscode-resource.vscode-cdn.net/Users/md/Desktop/node_test/images/Capture%20d%E2%80%99%C3%A9cran%202022-05-21%20%C3%A0%2018.51.55.png?version%3D1653155862333)


![](https://file%2B.vscode-resource.vscode-cdn.net/Users/md/Desktop/node_test/images/Capture%20d%E2%80%99%C3%A9cran%202022-05-21%20%C3%A0%2018.52.25.png?version%3D1653155884032)

![](https://file%2B.vscode-resource.vscode-cdn.net/Users/md/Desktop/node_test/images/Capture%20d%E2%80%99%C3%A9cran%202022-05-21%20%C3%A0%2018.50.42.png?version%3D1653155899810)

-------------

pour login 

![](https://file%2B.vscode-resource.vscode-cdn.net/Users/md/Desktop/node_test/images/Capture%20d%E2%80%99%C3%A9cran%202022-05-21%20%C3%A0%2018.59.08.png?version%3D1653156136130)
 

![](https://file%2B.vscode-resource.vscode-cdn.net/Users/md/Desktop/node_test/images/Capture%20d%E2%80%99%C3%A9cran%202022-05-21%20%C3%A0%2018.59.15.png?version%3D1653156180251)



![](https://file%2B.vscode-resource.vscode-cdn.net/Users/md/Desktop/node_test/images/Capture%20d%E2%80%99%C3%A9cran%202022-05-21%20%C3%A0%2018.59.27.png?version%3D1653156195092)




-----------------


profile


![](https://file%2B.vscode-resource.vscode-cdn.net/Users/md/Desktop/node_test/images/Capture%20d%E2%80%99%C3%A9cran%202022-05-21%20%C3%A0%2019.05.22.png?version%3D1653157470009)



![](https://file%2B.vscode-resource.vscode-cdn.net/Users/md/Desktop/node_test/images/Capture%20d%E2%80%99%C3%A9cran%202022-05-21%20%C3%A0%2019.05.42.png?version%3D1653157517677)


-------------------
crud

c

![](https://file%2B.vscode-resource.vscode-cdn.net/Users/md/Desktop/node_test/images/Capture%20d%E2%80%99%C3%A9cran%202022-05-21%20%C3%A0%2019.15.02.png?version%3D1653157545124)


![](https://file%2B.vscode-resource.vscode-cdn.net/Users/md/Desktop/node_test/images/Capture%20d%E2%80%99%C3%A9cran%202022-05-21%20%C3%A0%2019.15.11.png?version%3D1653157604361)

----

r

![](https://file%2B.vscode-resource.vscode-cdn.net/Users/md/Desktop/node_test/images/Capture%20d%E2%80%99%C3%A9cran%202022-05-21%20%C3%A0%2019.15.25.png?version%3D1653157624633)


![](https://file%2B.vscode-resource.vscode-cdn.net/Users/md/Desktop/node_test/images/Capture%20d%E2%80%99%C3%A9cran%202022-05-21%20%C3%A0%2019.15.33.png?version%3D1653157654917)
---
u

![](https://file%2B.vscode-resource.vscode-cdn.net/Users/md/Desktop/node_test/images/Capture%20d%E2%80%99%C3%A9cran%202022-05-21%20%C3%A0%2019.20.30.png?version%3D1653157834672)

![](https://file%2B.vscode-resource.vscode-cdn.net/Users/md/Desktop/node_test/images/Capture%20d%E2%80%99%C3%A9cran%202022-05-21%20%C3%A0%2019.22.05.png?version%3D1653157866763)

--
d

![](https://file%2B.vscode-resource.vscode-cdn.net/Users/md/Desktop/node_test/images/Capture%20d%E2%80%99%C3%A9cran%202022-05-21%20%C3%A0%2019.28.24.png?version%3D1653157898424)


------------------
docker 


![](https://file%2B.vscode-resource.vscode-cdn.net/Users/md/Desktop/node_test/images/Capture%20d%E2%80%99%C3%A9cran%202022-05-21%20%C3%A0%2019.40.27.png?version%3D1653158614660)

