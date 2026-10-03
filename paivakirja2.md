# Oppimispäiväkirja: Hajautettu git

__Mikä osion tehtävissä oli vaikeaa ja mikä helppoa? Mikä auttoi minua oppimaan? Miten selvitin esteet, jotka vaikuttivat tehtävän suorittamiseen?__

Tämä oli vähän vaikeampaa, menin hieman sekaisin mitä minun kuului tehdä tehtävissä, selvisin sinnikyydellä

## Osiossa käyttämäni Git-komennot

| Komento | Kuvaus |
| ------- | ------ |
| `git clone osoite` | Kopioi etärepositorion omalle koneelle |
| `git remote -v` | Näyttää etärepositorioiden osoitteet |
| `git remote add nimi osoite` | Lisää uuden etärepositorion |
| `git remote set-url origin osoite` | Vaihtaa etärepositorion osoitteen |
| `git push -u origin haara` | Vie haaran etärepositorioon ja yhdistää seurannan |
| `git push` | Vie talletukset etärepositorioon |
| `git push --tags` | Vie tunnisteet etärepositorioon |
| `git fetch` | Hakee etärepositorion muutokset yhdistämättä niitä |
| `git pull` | Hakee muutokset ja yhdistää ne nykyiseen haaraan |
| `git branch -a` | Näyttää paikalliset ja etähaarat |
| `git branch -d haara` | Poistaa paikallisen haaran |
| `git fetch --prune` | Siivoaa viittaukset poistettuihin etähaaroihin |
| `git switch --detach origin/haara` | Siirtyy katselemaan etähaaran tilaa |
| `git merge origin/haara` | Yhdistää etähaaran muutokset paikalliseen haaraan |
| `git merge actions/main --allow-unrelated-histories` | Yhdistää toisen repositorion historian omaan |
| `git show` | Näyttää talletuksen muutokset rivitasolla |