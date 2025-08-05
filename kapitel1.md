# Kapitel 1 – Python: Det første skridt

## Hvorfor Python – og ikke JavaScript?

Du har måske hørt om JavaScript – det sprog, der styrer alt fra hjemmesider til webapps. Men Python er anderledes. Python er designet til at være let at læse, let at skrive og let at lære. Det er sproget, som forskere, hackere, datafolk og AI-udviklere bruger, når de skal have computeren til at gøre noget smart.

Python er ikke kun til web – det
Du kan fx:

- Automatisere alt fra simple opgaver til komplekse workflows
- Udveksle data med web-API'er og bygge integrationer
- Udforske og analysere store datamængder
- Udvikle og træne machine learning og AI-modeller
- Styre og programmere IoT-enheder og hardware
- Skrive scripts, der hacker, overvåger og optimerer systemer

> Python er **din adgang til den digitale verden** – hvor data, maskiner og netværk mødes.

---

## Hvad er kode – helt principielt?

Forestil dig, at du skal forklare en robot, hvordan den skal lave en kop te. Du kan ikke bare sige "lav te" – du skal give præcise instruktioner, trin for trin:

1. Gå hen til vandhanen
2. Fyld kedlen med vand
3. Tænd for kedlen
4. Læg en tepose i koppen
5. Hæld kogende vand i koppen
6. Vent 3 minutter
7. Tag teposen op

Kode er netop sådan: Du skriver **præcise instruktioner**, som computeren kan følge én ad gangen. Computeren gør kun det, du siger – intet andet og intet mindre.

Når du skriver kode, bliver du den, der styrer maskinen. Du bestemmer, hvad der skal ske – og du kan få computeren til at gøre alt fra at regne, hente data, styre hardware eller analysere billeder.

> Kode er din måde at tale med computeren på. Jo mere præcise du er, jo bedre forstår den dig.

---

## Hvad er en terminal?

En **terminal** er et sted, hvor du kan **skrive beskeder direkte til computeren** – og få svar tilbage.
Det er lidt som en chat, men uden emojier.

### Opgave 1: Åbn din terminal

1. **På Mac:** Tryk `Cmd + Mellemrum`, skriv `Terminal`, tryk Enter
2. **På Windows:** Tryk Start og skriv `cmd` eller `Windows Terminal`

Terminalen er god i begyndelsen når du skal lære at programmere - for den kan modtage instruktioner og køre kode direkte.

---

## Terminalen: Din direkte adgang til computeren

Terminalen er som en superkraft for nørder. Her kan du styre din computer med tekstkommandoer – hurtigt og præcist. Her er nogle af de vigtigste ting, du kan gøre:

### Find rundt i mapper

**Mac:**

- Se hvor du er: `pwd`
- Se indholdet af en mappe: `ls`
- Gå til en anden mappe: `cd mappenavn`

**Windows:**

- Se hvor du er: `cd`
- Se indholdet af en mappe: `dir`
- Gå til en anden mappe: `cd mappenavn`

### Opret en ny mappe

**Mac:**

- `mkdir minmappe`

**Windows:**

- `mkdir minmappe`

### Opret en ny fil

**Mac:**

- `touch minfil.txt`

**Windows:**

- `type nul > minfil.txt`

### Slet en fil

**Mac:**

- `rm minfil.txt`

**Windows:**

- `del minfil.txt`

### Slet en mappe

**Mac:**

- `rm -r minmappe`

**Windows:**

- `rmdir /s minmappe`

### Terminalen kan mere end mapper

Her er nogle  ting, du kan gøre direkte fra terminalen:

**Mac:**

- Åbn et program (fx Notes): `open -a Notes`
- Åbn en hjemmeside i din browser: `open https://www.python.org`
- Tag et screenshot: `screencapture ~/Desktop/billede.png`

**Windows:**

- Åbn et program (fx Notepad): `start notepad`
- Åbn en hjemmeside i din browser: `start https://www.python.org`
- Tag et screenshot (Windows 10+): `snippingtool` (eller brug Print Screen-tasten)

> Terminalen kan styre programmer, åbne websider, vise filer og meget mere – alt sammen med én linje kode!


> Når du skriver kommandoer i terminalen, har du faktisk allerede programmeret! Du har givet computeren præcise instruktioner – i et sprog, din computer forstår. Hver gang du skriver en kommando, styrer du maskinen direkte med tekst. Det er grundprincippet i programmering: Du fortæller computeren, hvad den skal gøre, én linje ad gangen.

Når du skriver kommandoer i terminalen, bruger du faktisk terminalens eget "sprog" – det kaldes ofte shell-kommandoer. På Mac er det typisk Bash eller Zsh, og på Windows er det Command Prompt (cmd) eller PowerShell.

Disse kommandoer er ikke Python, men små programmeringssprog, som operativsystemet (i.e. mac eller windows) forstår direkte. Når du senere skriver Python-kode, bruger du et rigtigt programmeringssprog, som kræver at Python er installeret.

---

# Hvorfor skal Python installeres?

Computeren forstår ikke Python fra naturens side. Du skal installere et program (Python), der kan læse og køre din kode. Det er ligesom at installere en app, der kan åbne et bestemt filformat. 

---

## Opgave: Tjek om du har Python

1. Åbn din terminal
2. Skriv:
   ```bash
   python3 --version
   ```
3. Hvis du får et versionsnummer (fx `Python 3.11.6`), er Python installeret.
4. Hvis du får en fejl, skal du installere Python fra [python.org](https://www.python.org/downloads/)

---

## Opgave: Skriv din første Python-kode direkte i terminalen

1. Åbn din terminal
2. Skriv:
   ```bash
   python3
   ```
3. Nu ser du et prompt, der ligner dette:
   ```
   >>>
   ```
4. Skriv:
   ```python
   print("Hej verden!")
   ```
5. Tryk Enter – og se, hvad der sker!
6. For at afslutte Python, skriv:
   ```python
   exit()
   ```

---

## Hvad sker der, når Python fortolker din kode?

Når du skriver en Python-kommando og trykker Enter, sker der følgende:

1. **Python-softwaren læser din kode** – linje for linje.
2. **Fortolkning:** Python oversætter din tekst til instruktioner, som computeren forstår.
3. **Udførelse:** Computeren gør præcis det, du har skrevet – fx viser "Hej verden!" på skærmen.

Python er et såkaldt fortolket sprog. Det betyder, at koden bliver læst og udført med det samme, uden at du skal "oversætte" den til maskinkode først. Det gør det nemt at eksperimentere og se resultater med det samme.

---

## Hjemmeopgave: Leg med Python i terminalen

Prøv at skrive og eksperimentere med følgende Python-kode direkte i terminalen. Du kan ændre tallene, teksten eller lave dine egne variationer!

1. Start Python i terminalen:
   ```bash
   python3
   ```
2. Skriv og prøv disse kommandoer én ad gangen:

```python
# Regn med tal
print(5 + 7)
print(42 * 2)

# Gem og brug variabler
navn = input("Hvad hedder du? ")
print("Hej, " + navn + "!")

# Lidt logik
alder = int(input("Hvor gammel er du? "))
if alder < 18:
    print("Du er under 18!")
else:
    print("Du er voksen!")
```

### Opgave

- Prøv at ændre tallene og teksten i eksemplerne.
- Lav din egen lille "chatbot" i terminalen, der stiller spørgsmål og svarer.
- Aflever din kode og et eksempel på output.

> Du kan kopiere din kode til en tekstfil, hvis du vil gemme eller aflevere den.

---


