# Arduino-Lex-Library
------------------------------------------------------------------------
Descrizione
------------------------------------------------------------------------

Libreria Linguaggio Lex per Arduino/ESP 32
Questa libreria permette di programmare Arduino e ESP32 in linguaggio LEX

-------------------------------------------------------------------------
Sintassi Linguaggio Lex
-------------------------------------------------------------------------

VOID SETUP:

setIn(pin); = pinMode(pin, INPUT);

setOut(pin); = pinMode(pin, OUTPUT);

VOID LOOP:

pinHigh(pin); = digitalWrite(pin, HIGH);

pinLow(pin); = digitalWrite(pin, LOW);

ALTRE FUNZIONI:

readPin(pin); = digitalRead(pin);

time(ms); = delay(ms);
