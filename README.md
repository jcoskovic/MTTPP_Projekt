# MTTPP_Projekt
 
 ## Testiranje rada stranice http://demowebshop.tricentis.com/
 
  ### Izvršeno je parcijalno testiranje frontenda i backenda stranice tako što su provedeni sljedeći testovi:
     1. Korisnik unosi podatke potrebne za registraciju, ali ostavlja email polje prazno
     2. Korisnik unosi podatke potrebne za registraciju, ali u polje za email unosi email koji se već koristi
     3. Korisnik unosi podatke potrebne za registraciju, ali confirm password se ne slaže s polje password
     4. Korisnik unosi podatke potrebne za prijavu te se pokušava prijaviti
     5. Korisnik se pokušava prijaviti s netočnim passwordom
   
  ### Upute za pokretanje testova
       Testovi su pisani u C# programskom jeziku korištenjem NUnit Frameworka i Selenium WebDriver
       Testovi su implementirani u VisualStudio 2022 programu
       Za korištenje testova na računalu je potrebno imati VisualStudio 2022 te Firefox browser
       
  ### Pokretanje Testova:
      1. Klonirajte repozitorij sa linka: https://github.com/jcoskovic/MTTPP_Projekt/tree/main/MTTPP_Projekt
      2. Pokrenuti MTTPP_Projekt.sln datoteku
      3. Pokrenuti testove klikom na Run All Test unutar Test (Test->Run All Tests)
      4. Ako želimo pokrenuti pojedinačno neki test otvorimo Test Explorer unutar Test (Test->Test Explorer) ili označimo pojedini test
      
 ### Ukoliko se iz nekog razloga nisu automatski dodali paketi koji se nalaze u packages folderu na repozitoriju potrebno ih je ručno instalirati
      1. Kliknemo na Manage NuGet Packages unutar taba Project (Project->ManageNuGet Packages)
      2. Kliknemo na prvi tab Browse
      3. Pojedinačno nađemo i instaliramo sljedeće pakete:  
             NUnit
             NUnit3TestAdapter
             Selenium Support
             Selenium WebDriver
             Selenium WebDriver Gecko Driver
   
     
     
  
     
