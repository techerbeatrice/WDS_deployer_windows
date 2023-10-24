# Déployer Windows avec WDS   

____

**Etape 1 - Installer le rôle WDS**     

🔧 **Prérequis**  
Tu as besoin d'une VM Microsoft Windows Server (en version au moins 2008) :

Adresse IP fixe du serveur : **192.168.10.2/24**
Nom du serveur : **srv-wds**  
Ce serveur est installé avec le rôle DHCP dans la configuration suivante :

Début de plage d'adresses : **192.168.10.10**  
Fin de plage d'adresses : **192.168.10.100**  
Masque : **/24**  
Ce serveur dispose de **2 disques** configurés comme ceci :  

Disque système : **30 GO**
Disque WDS :   
Taille de volume : **30 Go**  
Partition de type : **GPT**  
File system : **NTFS**  
Nom : **WDS**  

![image](https://github.com/techerbeatrice/WDS_deployer_windows/assets/138071140/be0fbc90-6056-4500-a5ae-daff0a89b6bc)
![image](https://github.com/techerbeatrice/WDS_deployer_windows/assets/138071140/a7e9d504-8f7f-4ab4-be1c-43e385ef309f)
![image](https://github.com/techerbeatrice/WDS_deployer_windows/assets/138071140/55df08d0-9eae-4f5e-847a-dac1fa33ccd1)


___


🔬 Installation du rôle  




_____


![image](https://github.com/techerbeatrice/WDS_deployer_windows/assets/138071140/5822b8fc-0f8c-4649-90a1-8b47a61e8d7c)

![image](https://github.com/techerbeatrice/WDS_deployer_windows/assets/138071140/52ec2b22-10f4-4703-85af-937801d63a16)

___

Pour cela, il faut :  

Une image de démarrage  
Une image d'installation  

___

