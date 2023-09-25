POSTUP, JAK ROZJET PROJEKT NA LOCALHOSTU

1. Stáhnout oba soubory (School system.zip a schoolsystem.bacpac).
2. Spustit Microsoft SQL Server Management Studio.
3. Connect to server:
   Server type: Database Engine
   Server name: (localdb)\MSSQLLocalDb
   Authentication: Windows Authentication
4. Kliknout Connect.
5. Na levo v panelu Object Explorer -> rozbalit (localdb)\MSSQLLocalDb
6. Pravým kliknutím na složku Databases -> vybrat Import Data-tier Application
   -> NEXT -> Import from local disk (vybrat umístění kam jste si stáhli schoolsystem.bacpac  a tento soubor tam nahrát) -> NEXT -> NEXT -> FINISH
7. Na levo v Object Explorer se vám zobrazí databáze schoolsystem
8. Rozbalit ZIP -> otevřít složku -> v ní spustit soubor School System.sln -> standartní otevření proběhne ve
   VisualStudio
9. Na levo v panelu SQL Server Object Explorer -> rozbalit SQL server -> rozbalit (localdb)MSSQLLocalDb
   -> rozbalit složku Databases -> měla by jít vidět databáze pojmenovaná schoolsystem
10. F5 nebo v horní liště zelený trojúhelník spouští aplikaci ve vašem prohlížečí
11. Po načtení úvodní obrazovky s Login zadejte tyto přihl. údaje:
    UserName: admin
    Password: Abcd1234. (ANO na konci hesla je tečka)
12. Stisknout modré tlačítko Login a můžete prohlížet aplikaci.
