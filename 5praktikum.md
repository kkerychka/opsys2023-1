Selles praktikumis õppisin, kuidas tõõtada failidega ubuntus. Läks umbes 4 tundi praktikumi lõpetamiseks. Allpool vastan küsimustele, mis olid praktikumis ning laadin üles ekraanipildid.
1) a) kataloogis /tmp/kaust oleva faili minufail.txt lugemiseks? r
b) kataloogis /tmp/kaust oleva faili minufail.txt kustutamiseks? rwx
2) On vajalik lugemisõigus r skriptifailile. Kui skriptifailil puudub lugemisõigus, ei saa seda lugeda ja seetõttu ei saa seda käivitada.
3) Igal kasutajal on oma nimeline grupp (vaikegrupp) , privaatsuse ja turvalisuse jaoks, et igal kasutajal olid võrdsed õigused failidele.
4) ![5 4](https://github.com/alop372/opsys2023/assets/121293934/76e8cec5-dc47-4159-b0b4-9c365b66c828)
5) ![5 5_1](https://github.com/alop372/opsys2023/assets/121293934/a948f103-dd6d-47a0-87be-7e6c9ad17861)
6) Jah, setuid võib potentsiaalselt vähendada süsteemi turvalisust, kui seda ei tehta hoolikalt ja kooskõlas turvareeglitega.
7) Mitte keegi, kuna faili modifitseerimise võimalus on ainult omanikul. Kasutaja peeter saab oma faile ise kustutada. 
8) ![5 8](https://github.com/alop372/opsys2023/assets/121293934/1e3771ba-866d-460d-9812-ba045e48a6f1)
9) Mitte keegi, isegi omanik, sudo chattr -i testfail-2 ja rm testfail-2.
