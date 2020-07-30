# Gossip Project 

### Configuration
Entrez la commande suivante dans votre terminal:

`bundle install`

### Création BDD

`rails db:migrate`

### Initialisation BDD

`rails db:seed`

`rails c`


## Démarrage

Une fois dans la console Rails (`rails c`) vous pourrez explorer les tables de données suivantes avec la commande tp de la gem table_print (installée grâce au Gemfile présent lors du `bundle install`) :

`tp User.all`

`tp Gossip.all`

`tp Tag.all`

`tp JoinTableTagGossip.all`

`tp PrivateMessage.all`

`tp City.all`
