# Samarbete i ett gemensamt repository

Ett gemensamt repository används i ett utvecklingsteam för att alla
ska kunna arbeta med samma kod och samma projekt, samtidigt som Git
håller ordning på alla ändringar som görs.

## Varför det används

- Alla i teamet kan se samma kod och samma historik
- Man kan arbeta i olika delar av projektet samtidigt utan att
  förlora varandras arbete
- Man kan gå tillbaka till tidigare versioner om något går fel
- Ändringar dokumenteras genom commit-meddelanden, så man ser vem
  som gjort vad och varför
- Man kan använda branches för att testa nya funktioner utan att
  påverka huvudversionen av projektet

## Hur det fungerar i praktiken

Varje person i teamet har en egen kopia av repositoryt på sin dator.
Man gör ändringar lokalt, committar dem, och skickar upp (push)
ändringarna till det gemensamma repositoryt (t.ex. på GitHub). Andra
i teamet kan sedan hämta (pull) dessa ändringar till sina egna
datorer.
