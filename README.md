# JPA

(A noter que je n'ai pas fait de classe Kanban comme demandé, je n'ai fait que deux classes contenant des données : Employee et Department, par manque d'attention au sujet avant de démarrer)

Les deux classes citées précédemment se trouvent dans le package fr.istic.tpjpa.domain.

Les classes de JPA se trouvent dans le package fr.istic.tpjpa.jpa.

Au final, en lançant les deux requêtes sur la base de données, on s'aperçoit que N1 Select met 8609ms à s'effectuer, alors que JoinFetch n'en met que 3529, on peut en conclure que la deuxième requête est bien plus efficace que la première.
