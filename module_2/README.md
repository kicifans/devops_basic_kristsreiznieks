Pēc pirmā commita ar module_1 man GitHub un lokāli kommitam uzrādīja dažādus hash:  
github hash : 7bc9aa1bbde36b9ae422372ef597ab4d27f6894d  
commit hash: 52e5f0f1759a00600e48466544ebf2f2b5541ae9  
  
Bet pēc otrā commita, salīdzinot kopētiem failiem, hashi sakrīt:  
100644 380a021ee6875e0e24094b22504aa3e95565ac91 0    &nbsp;&nbsp;&nbsp;&nbsp;  -  README.md  
100644 b281b84f80a9c105a774f49cd032aeb712131320 0     &nbsp;&nbsp;&nbsp;&nbsp;  - module_1/README.md  
100644 f9aad69a225be2a82996355af94d8c77c0e62f51 0    &nbsp;&nbsp;&nbsp;&nbsp;  - module_1/git.png  
100644 a18e8e4e2f25625f48a37147e4fa42fe83c51e66 0    &nbsp;&nbsp;&nbsp;&nbsp; -    module_1/helloworld.png  
100644 e69de29bb2d1d6434b8b29ae775ad8c2e48c5391 0     &nbsp;&nbsp;&nbsp;&nbsp; -  module_2/README.md  
100644 f9aad69a225be2a82996355af94d8c77c0e62f51 0   &nbsp;&nbsp;&nbsp;&nbsp; -    module_2/git.png  
100644 a18e8e4e2f25625f48a37147e4fa42fe83c51e66 0    &nbsp;&nbsp;&nbsp;&nbsp; -   module_2/helloworld.png  
  
16. Veidi kā meklēt izmaiņas, kas veiktas ne agrāk kā divas nedēļas:
Atverot GitHub Actions, un filtrējot pēc : "created:>2022-04-12"
Izmantojot git komandu : "$ git log --since=2.weeks"

18. Laura Pacilio nav veikusi commitus pagājušā gadāa septembrī (pirmais redzamais ieraksts: Mon Jun 28 11:33:06 2021 -0400)

19. Laura Pacilio nav veikusi commitu vakar

*papilduzdevums*  
Redzu, ka uzrādās commit ar 16.06.2021, bet nesapratu kāpēc.  
Meklējot pēc autora visus commitus, šis commits arī uzrādās laikā starp 20.04 un 22.04 (ar datumu 16.04.).
  

