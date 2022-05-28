to jest plik README.md o nauce gita

Tutaj beda wpisywane komendy dotyczace podstaw gita:

# utworzenie nowego folderu
mkdir -p workspace/nauka_gita
cd workspace/nauka_gita

#konfiguracja gita
git config -l
git config --global user.name "nataliachamicewicz"

#nie lubimy spamerow
git config --global user.email "nataliachamicewicz@users.noreply.github.com"

#cala globalna konfiguracja jest w nastepujacym pliku
cat ~/.gitconfig

#sprawdzamy czy jestesmy na wlasciwej sciezce
pwd
