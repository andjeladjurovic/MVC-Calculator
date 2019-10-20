Model-View-Controller

MODEL - nosilac podataka. Takodje, sadrzi logiku za
update-ovanje kontrolera ukoliko se podaci promene.

VIEW - vizuelna reprezentacija podataka koje model
sadrzi.

CONTROLLER - povezuje model i view. Kontrolise tok
podataka koji ulaze u model i update-uje view
kada god se podaci promene.

Konkretan primer kalkulatora:
Model sadrzi promenljivu rezultat(u kojoj se cuva
zbir dva broja), kao i dve metode: addition,
koja vraca zbir dva broja i returnResult, koja 
vraca rezultat.

View sadrzi vizuelnu reprezentaciju kalkulatora,
kao i ActionListener na dugmetu, koje poziva
kontrolera.

Kontroler na pritisak dugmeta, tj. na obavestenje
View-a sabira dva broja.
