# projetVercel

4. vercel -v

5.
npm i -g @angular/cli
ng new projetVersel

6. vercel deploy

7. vercel list

8. vercel logs https://projet-versel.vercel.app

9. vercel inspect https://projet-versel.vercel.app

10. Les variables d'environnement sont accessible en "Runtime" comme en "Build step". Elle permettent d'utiiser des variables sans
avoir besoin de les placer dans le code source. Elle peuvent etre accessible durant les différentes étapes du développement (Production,
Preview, Devloppement).

11. vercel env add plain envVar1 production 

12. vercel env ls

13. Les variables secret sont sont des variables chiffrée. Elle sont utiles pour stoquer des informations sensibles.

15. vercel secrets add nom_secret nicolas
    vercel env add secret SECRET_NAME production

16. Production, Preview, Devloppement -> permet de developper en testant les fonctionnalité puis de déployer une fois le résultat satisfaisant
