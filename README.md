# Rakendusserverite halduse automatiseerimine
## git
### paigaldamine
git paigaldamiseks tuleb teostada järgmised käsud:
...
apt install git
...
### seadistamine
git seadistamiseks on vaja konfigureerida kasutaja nimi ja email, samuti teostada redaktor:
...
git config --global user.name "Ees Perekonnanimi"
git config --global user.email email@domeen.com
git config --global core.editor nano
...
