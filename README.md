# Git ja GitHub -lopputyö
Miikka Laakso 
2608089

Gitin käyttö ja versiohallinta
Git konfliktin tekeminen ja ratkaisu

## Harjoiteltavat asiat

- Git commit ja push
- Git branch ja merge
- Merge-konfliktien ratkaiseminen
- Git stash ja revert
- Git cherry-pick ja rebase
- Git tag ja .gitignore
- GitHub Pull Request

## Gitin peruskomennot

Projektin seuraavat komennot:

- git clone: Kloonaa GitHub-repositorion.
- git status: Näyttää tiedostojen muutokset.
- git add: Lisää muutokset.
- git commit: Tallentaa muutokset.
- git push: Lähettää muutokset GitHubiin.
- git switch: Vaihtaa haaraa.

## Git stash -harjoitus

Väliaikainen muutos, jonka tallennan git stash -komennolla.

## Lopputyön toteutus

Tässä lopputyössä harjoittelin Gitin ja GitHubin käyttöä
VS Codessa.

Loin GitHub repositorion ja yhdistin sen tietokoneelleni
SSH-yhteydellä. Harjoittelin tiedostojen lisäämistä,
commitien tekemistä sekä muutosten lähettämistä GitHubiin.

Loin erillisiä feature haaroja ja yhdistin niitä
main haaraan. Harjoittelin myös merge-konfliktin
tekemistä ja ratkaisemista VS Codessa.

Käytin git stash ja git stash pop -komentoja
keskeneräisten muutosten tallentamiseen ja palauttamiseen.

Tein myös Pull Requestin GitHubissa ja yhdistin
muutokset päähaaraan.

## Mitä opin?

Opin käyttämään Gitin peruskomentoja ja ymmärtämään,
miten versionhallinta toimii käytännössä.

Opin luomaan haaroja, yhdistämään niitä sekä
ratkaisemaan Git-konflikteja.

Ymmärsin myös, miten GitHubia käytetään projektin
muutosten tallentamiseen ja hallintaan.

## Git cherry pick -harjoitus

Harjoittelin git cherry pick -komentoa, jolla voidaan
siirtää commit toisesta haarasta main haaraan.

## Versionhallinnan kehittäminen

Projektissa harjoiteltiin Gitin toimintoja
ja eri haarojen hallintaa.
## Git rebase -harjoitus

Harjoittelin git rebase -komentoa, jolla feature haara
voidaan päivittää main haaran uusimpien muutosten päälle.

## Gitin toiminnot

### Git revert
Tein tarkoituksella virheellisen commitin ja peruin sen
git revert -komennolla. Opin, että revert luo uuden
commitin eikä poista aikaisempaa historiaa.

### Git cherry-pick
Loin erillisen feature haaran ja tein siihen commitin.
Siirsin yksittäisen commitin main haaraan käyttämällä
git cherry pick -komentoa.

### Git rebase
Harjoittelin feature haaran päivittämistä main haaran
uusimpien muutosten päälle git rebase -komennolla.
Rebasen aikana syntyi konflikti, jonka ratkaisin
VS Codessa säilyttämällä molemmat muutokset.

### Git tag
Loin projektille version v1.0.0 ja lähetin tagin
GitHubiin.

### .gitignore
Loin .gitignore-tiedoston, jolla estetään väliaikaisten
tiedostojen lisääminen versionhallintaan.
Testasin toimintaa testi.log tiedostolla.

## Yhteenveto

Opin käyttämään Gitin peruskomentoja
sekä versionhallintatoimintoja.

Haastavinta oli merge- ja rebase konfliktien
ratkaiseminen. Opin selvittämään konfliktit VS Codessa
ja jatkamaan versionhallintaa niiden ratkaisemisen jälkeen.

GitHubin avulla opin hallitsemaan projektin eri
versioita, haaroja ja muutoksia.
