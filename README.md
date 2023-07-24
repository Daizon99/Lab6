# Lab 6

## Partie 1 : Lancement de BookstoreApp
Avant de commencer le laboratoire, j'ai configuré maven[3.8.6](https://maven.apache.org/download.cgi) . J'ai ensuite compilé les sources de BookstoreApp avec 
```mvn compile```:

![178128317-666e7265-f03e-4a9e-960a-cae3cec3e7a5](https://github.com/Daizon99/Lab6/assets/113944271/6f29557d-fa20-4290-8b14-b5b3c5f5a4ba)

L'étape suivante a consisté à construire le projet à l'aide de la commande ```mvn package -DskipTests``` 

![178128373-b25d692e-8cd7-4cb1-ba4a-690790af37b8](https://github.com/Daizon99/Lab6/assets/113944271/480a8869-6838-4ddf-9c5d-3c39d0ef5811)

Nous lançons maintenant l'application avec ```java -jar ./target/BookstoreApp-0.1.0.jar```:

![178128429-3d2b2e2f-bdb2-4dc5-8ba4-25643b37a337](https://github.com/Daizon99/Lab6/assets/113944271/723aa68e-abe5-4d9f-9ab1-2fc711d99234)

## Partie 2 : Ajout d'un test unitaire à BookstoreApp

J'ai d'abord exécuté les tests déjà mis en œuvre en lançant ```mvn test```

![178128485-910a4a06-5288-472c-8e00-2d626641b118](https://github.com/Daizon99/Lab6/assets/113944271/c97aa0b3-d256-47df-88c5-e0c1cfbbcae1)

Ensuite, j'ai ajouté un test unitaire à ExampleSeleniumTest.java:

![178128642-76556dcb-486f-4314-b4d2-56b170dd771b](https://github.com/Daizon99/Lab6/assets/113944271/72173745-27f8-462b-92d0-6ed1683284d2)

 Enfin, j'ai couru à nouveau ```mvn test```

![178128569-c1341a33-248e-465d-9caf-72ee9c9ca42d](https://github.com/Daizon99/Lab6/assets/113944271/59f0b652-772d-4da4-b97b-751a47a561eb)
