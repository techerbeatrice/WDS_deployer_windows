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
![image](https://github.com/techerbeatrice/WDS_deployer_windows/assets/138071140/ed5ac58b-17d3-49d0-9746-b41dfc6108c9)
![image](https://github.com/techerbeatrice/WDS_deployer_windows/assets/138071140/d6500223-7b4c-4c9e-bbd8-bcda4aacdd1e)

___


🔬 **Installation du rôle  WDS**    

![image](https://github.com/techerbeatrice/WDS_deployer_windows/assets/138071140/9191b324-acbb-4f91-a5e2-42bfa10fd5b0)

_____

🔬 **Configuration du WDS**      

![image](https://github.com/techerbeatrice/WDS_deployer_windows/assets/138071140/b3ea6fa7-f5a4-499e-8c87-33c048817e94)

![image](https://github.com/techerbeatrice/WDS_deployer_windows/assets/138071140/8f61e197-fdba-4acb-a6d2-b8b973604f3f)

**Choix du 2ème disque dur**      

![image](https://github.com/techerbeatrice/WDS_deployer_windows/assets/138071140/882fb799-ca99-4093-a58a-7ede8ee3c612)

![image](https://github.com/techerbeatrice/WDS_deployer_windows/assets/138071140/6a313ba8-778e-4e60-bcbc-406ab4da0688)

____

🔬 **Lancement du service WDS** 

![image](https://github.com/techerbeatrice/WDS_deployer_windows/assets/138071140/af883ab9-ad28-4937-9c5f-cd9e120119b2)

![image](https://github.com/techerbeatrice/WDS_deployer_windows/assets/138071140/4e668673-f5cf-41b3-a646-6f5a2c12e3f1)



