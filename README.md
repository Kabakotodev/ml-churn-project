---
noteId: "a18b95b0dac811f1b883a199acf6104b"
tags: []

---

PARTIE 1 — PRÉPARATION DE L’ENVIRONNEMENT
1.1 Vérifier le système
Sous Ubuntu : lsb_release -a
#
Vérifier Python : python3 --version
#
Vérifier Git : git --version
#
Vérifier Docker : docker --version
#
Vérifier Docker Compose : docker compose version
#
Si Docker n'est pas installé :
#
sudo apt update
sudo apt install docker.io docker-compose-v2 -y
Activer Docker :

sudo systemctl enable docker
sudo systemctl start docker
Ajouter l'utilisateur au groupe Docker : sudo usermod -aG docker $USER

 
Puis redémarrer la session.

Tester : docker run hello-world

####################
Créer l'environnement virtuel : python3 -m venv venvFilRouge

 
Activer : source venvFilRouge/bin/activate

 
Sous Windows : venvFilRouge\Scripts\activate

