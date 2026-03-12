Så nå som du har Powershell 7 åpen som administrator så har vi noen commandoer vi skal kjøre.

Først kjør

Set-ExecutionPolicy-ExecutionPolicy Bypass -Scope Process

----------------------------------------------------------------------------------------------------------------------------

Deretter skal vi bytte directory til ffu mappen våres

Skriv i Powershell 7

cd "C:\FFU-2xxx.x\FFUDevelopment"

Denne må du endre på tilsvarende versjonen av FFU du har

----------------------------------------------------------------------------------------------------------------------------

Til slutt skal vi åpne BuildFFUVM_UI.ps1

Skriv i Powershell 7:

./BuildFFUVM_UI.PS1

Vis alt er gjort riktig, skal UI til FFU åpne.
