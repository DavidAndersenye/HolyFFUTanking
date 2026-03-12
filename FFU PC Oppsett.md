Dette er hvordan du har lyst å sette opp pcen du skal lage FFUer på.

Det er viktig at du har en PC med en fresh Windows 11 install med ingen andre filer. Dette er ofte et hull folk faller inn i når de lurer på hvorfor det ikke funker.
Richard Balsley, Microfosft ingeniøren som lagde FFU løsningen, har sagt at dette er ofte en fix for folk som har problemer med lagingen av FFU filer.

Når du har en fresh pc med Windows 11 trenger du noen extra programmer

Dette er:

----------------------------------------------------------------------------------------------------------------------------

FFU Development

https://github.com/rbalsleyMSFT/FFU

Trykk på releases og last ned den nyeste utgivelsen av FFU.

Unzip FFU filen i C:/

----------------------------------------------------------------------------------------------------------------------------

Windows 11 ADK og Windows PE add-on for the ADK:

https://learn.microsoft.com/en-us/windows-hardware/get-started/adk-install

Helst bruk november 2025 release.

Det er ingenting du trenger å endre på install, bare installer trykk next gjennom alt.

----------------------------------------------------------------------------------------------------------------------------

Hyper-V

Trykk Start, og søk opp Control Panel, trykk på Programs, så trykk "Turn Windown features on or off", så hook av "Hyper-v". Den burde begynne å laste ned.

----------------------------------------------------------------------------------------------------------------------------

Powershell 7

Trykk start, og søk opp "Powershell". Åpne som admin ("CTRL + Shift + Left click" er en shortcut for å åpne som admin)

Paste inn denne kommandoen og vent

winget install --id Microsoft.PowerShell --source winget

Når den er ferdig, lukk Powershell, og åpne Powershell 7.

----------------------------------------------------------------------------------------------------------------------------
