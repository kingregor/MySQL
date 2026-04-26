1. Wpierw instalujemy Server, potem Worbencha.
2. Jeśli nie idzie uruchomić instalatora, bo program żąda doinstalowania bibliotek Visual Studio, to instalujemy wpierw plik VC_redist.x64.
3. W czasie instalacji serwera, gdy instalator będzie dawał możliwości wyboru wykonujemy "execute" lub "next", z dwoma wyjątkami:
 - port dostępu do serwera zamieniamy z 3306 -> 3307 (33070 można odpuścić),
 - gdy będzie pytał o dodanie przykładowych danych wybieramy obie bazy Sakila i World.
 4. Potem instalujemy Workbencha.
