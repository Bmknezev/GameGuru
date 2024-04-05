# tempName

ESOF-3675 Project
By Braydon, David, Cisco

Our project uses a combination of multiple datasets from steam in order to find useful connections between them. Using python libraries like pandas, mlxtend, pymongo, and flask, We were able to upload our datasets to a database and perform some data mining on them to find these connections and relationships, then display all the information on a self hosted website. Preprocessing used pandas to manipulate the data and get it into a form required, pymongo then let us communicate with the database to upload all of our data. Mining used the apriori and association rule functions from the mlxtend library, and flask was used to host the website, which was built using html.
