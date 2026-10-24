#h1 Hei Ansiblen maailma
##Artikkeli: Hello Ansible
- Ansible on konfiguraation hallintatyökalu
- Toimii SHH:n kautta
- Lista hosteista jota hallitaan, hosts.ini
- Listaa mitkä ryhmät (joissa hosteja) saavat mitkäkin konfiguraatiot (roolit), Site.yml

##Artikkeli SSH public key, Login without password
- SSH on käytetyin ja turvallinen tapa kirjautua etänä palvelimelle
- SSH pääsyavaimet: private ja public key
- Pääsyavainta avulla sinun ei tarvitse käyttää salasanaa (turvallisempaa)
- SSH on daemon
- Moni palvelu käyttää SSH:ta, muun muassa Ansible
- ssh-keygen-komennolla luodaan avainpari
- Public key kopioidaan hostille mihin haluat kirjautua, esimerkiksi ssh-copy-id localhost

##Johdanto
Tämän tehtävän päämääränä on asentaa Linux Debian 13 käyttöjärjestelmä virtuaalikoneeseen, sekä asentaa siihen SSH-daemon. Kun SSH on asennettu automatisoidaan kirjautuminen localhosgtiin public keyllä. Tehtävässä myös asennetaan Debianille Ansible konfiguraation hallintatyökalu.

##a) Debian 13 asennus virtuaalikoneseen
Loin tätä kurssia varten jo ennen ensimmäistä luentoa uuden virtuaalikoneen, jolle asensin Linux Debian 13. Käytin hyödyksi Johanna Heinosen Linux-palvelimet-kurssin GitRepoa, joka on listattu lähteissä. Debianin asennus sujui ilman ongelmia, joten jätän tämän osan raportissa suppeaksi.
img/h1_my_vm.png









##Lähteet
Karvinen 2026: Hello Ansible https://terokarvinen.com/hello-ansible/
Karvinen 2026: SSH public key - Login without password https://terokarvinen.com/ssh-public-key-login-without-password/
Heinonen 2026: Linux palvelimet Module 1 https://github.com/johannaheinonen/johanna-test-repo/blob/main/module_1.md


Tätä dokumenttia saa kopioida ja muokata GNU General Public License (versio 2 tai uudempi) mukaisesti. http://www.gnu.org/licenses/gpl.html
