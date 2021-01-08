# Vaja-7-PWM-s-STM32F4-Discovery
2.
b.1) Kateri pin ste omogočili? PE9 
b.2) Kaj se izpiše poleg pina? TIM1_CH1
d) Koliko je vrednost Perscaler? 16
e) Koliko znaša frekvenca sedaj? 10 kHz
f) Kaj pomeni pulse parameter? To je širina signala (duty cycle). 
3.
b) Poiščite prenastavljeni parameter Pulse v vaši kodi in prepišite ukaz, ki ga je generiral CubeMX: sConfigOC.Pulse = 50;
5.
a) V kodi spremenite vrednost širine pulza na 25 %. Zapišite popravljeni ukaz v kodi: sConfigOC.Pulse = 25;
b) Zapišite kaj počnejo ukazi v  1.,2. in 3. vrstici.
   1. vrstica: Nastavi spremenljivko dutyCycle za duty cycle.
   2. vrstica: Spremenljivki dutyCycle prišteje 10.
   3. vrstica: Če spremenljivka dutyCycle preseže 90, jo ponastavi na 10
   
komentar:
Osiloskopa ni bilo tako težko nastaviti, kot sem si sprva mislil. Čudna se mi zdi frekvenca urinega takta, saj sem mogel za željeno frekvenco 10 kHz
spremeniti glavno uro iz 32 MHz na 16 MHh. Drugače je bila frekvenca 20 kHz.
