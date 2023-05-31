# cybersecurite_test_vulnerabilite


## I - Contexte et objectifs du projet

Laboratoire réalisé dans le cadre du cours de "Cybersécurité défensive : vulnérabilités et incidents" aun sein de l'université du Québec à Chicoutimi. 

Ce laboratoire porte sur les tests de vulnérabilités et porte sur plusieurs objectifs : 
- utilisation de Nessus et de Metasploit2
- détecter une vulnérabilité et la tester pour la confirmer
- déceler et confirmer quelques unes des vulnérabilités

## II - Point de situation

metasploitable2 contient une cinquantaine de vulnérabilités. Je me suis donc concentré sur seulement 2. 

## III - Installation et exécution de l'application

### Composition du repository
Le repository est composé des éléments :
- de l'énoncé du laboratoire 
- du rapport en réponse à l'énoncé 
- du rapport complet émis par Nessus suite à l'analyse de metasploitable2
### Lancement du projet

Etape de mise en place du msf selon le lien suivant :
- sudo msfdb init
- sudo msfdb start
- sudo msfdb status
- sudo msfconsole -q

Etape de réalisation des commandes NMAP :
- db_nmap -sV "adresse IP" => identifier les versions des services qui sont en cours d'exécution sur le système cible
- db_nmap -O "adresse IP" => déterminer le système d'exploitation utilisé sur le système cible

## IV - Sources

- https://www.kali.org/docs/tools/starting-metasploit-framework-in-kali/#:~:text=Kali%20PostgreSQL%20Service-,Start%20the%20Kali%20PostgreSQL%20Service,database%20kali%40kali%3A~%24
- https://www.exploit-db.com/?author=8

## V - Changelog

### V1 => new release

### V1 => version initiale





