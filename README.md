# EndToEndOFDM

## Osnovno o projektu
U ovom projektu modelovan je kompletan OFDM sistem koji uključuje predajnik, prenosni
radio kanal i prijemnik. Prikazan je detaljno postupak prenošenja jednog OFDM bloka
kroz sistem.

## OFDM
OFDM je ključni element kako 4G( LTE), tako i narednih generacija mobilnih komunikacija, 
pa ćemo  pružiti osnovne informacije vezane za njega.OFDM se koristi i u tehnologijama 
kao što su WiMAX i DVB.OFDM je tehnika modulacije koja koristi više paralelnih podnosača 
(subcarrier) koji su međusobno ortogonalni,kako bi se redukovala njihova interferencija.
Ortogonalnost podnosača znači da je integral proizvoda dva različita podnosača po jednom 
periodu jednak nuli.Ortogonalni podnosači se obično realizuju korišćenjem  IFFT 
operacije koja predstavlja numerički efikasnu implementaciju Inverzne Diskretne Furijeove 
transformacije (IDFT). Suština postupka je da IDFT transformiše frekvencijski u vremenski
domen. Dakle, kada imamo niz kompleksnih brojeva koji predstavljaju amplitude i faze signala 
pojedinačnih podnosača u frekvencijskom domenu, IDFT će generisati vremenski signal koji je 
superpozicija signala svih podnosača.

## Reference
[1] Shahrokh Hamidi,End-to-End OFDM Simulation in Python for a SISO Communication System,
https://www.researchgate.net/publication/382795116_End-to-End_OFDM_Simulation_in_Python_for_a_SISO_Communication_System
[2] Branislav Todorović, Osnove telekomunikacija, Akademska misao, Beograd, 2021

[3] David Tse, and Pramod Viswanath, Fundamentals of Wireless Communication, Cambridge University Press, Cambridge CB2 2RU, UK, 2005

[4] Learning DSP Illustrated https://dspillustrations.com/pages/index.html
