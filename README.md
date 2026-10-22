# AI coach

Trener przygotowania motorycznego w okienku: łączy dane z zegarka Garmin z rozmową z Claude.
*A strength and conditioning coach in a window: your Garmin data plus a conversation with Claude.* ([English below](#english))

**[⬇ Pobierz najnowszą wersję / Download the latest version](https://github.com/lsielewicz/AICoach-releases/releases/latest/download/AICoach-instalator.zip)**

---

## Polski

### Czego potrzebujesz
- Windows 10 lub 11
- Konto Garmin Connect (zegarek Garmin)
- Konto Claude z subskrypcją **Pro lub wyższą** - rozmowa z trenerem odbywa się w Claude Code na Twoim koncie

### Instalacja
1. Pobierz [AICoach-instalator.zip](https://github.com/lsielewicz/AICoach-releases/releases/latest/download/AICoach-instalator.zip) i rozpakuj (prawy przycisk - "Wyodrębnij wszystko").
2. Kliknij dwukrotnie **Zainstaluj.cmd**. Instalator doinstaluje brakujące składniki i utworzy skrót **AI coach** na Pulpicie.
   Jeśli Windows pokaże ostrzeżenie "System Windows ochronił ten komputer" - kliknij "Więcej informacji", potem "Uruchom mimo to".
3. Uruchom **AI coach** ze skrótu.

### Pierwsze kroki
1. Utwórz profil (imię, sport).
2. Zakładka **Garmin** - zaloguj się kontem Garmin Connect (hasło nie jest zapisywane).
3. Zakładka **Trener** - "Zaloguj się" do Claude (otworzy się strona w przeglądarce).
4. **Nowa rozmowa** - trener zada kilka pytań o cel i ułoży plan. Plan zobaczysz w zakładce **Plan** (także jako Excel).

### Aktualizacja i odinstalowanie
- Nowa wersja: pobierz zip ponownie i uruchom **Zainstaluj.cmd** - profile i plany zostają.
- Odinstalowanie: **Odinstaluj.cmd** z paczki. Dane profili zostają w `%APPDATA%\GarminTrener` (usuń ten folder, jeśli chcesz je skasować).

### Prywatność
- Dane z Garmina są tylko odczytywane i przechowywane lokalnie na Twoim komputerze.
- Aplikacja nie zna Twojego hasła do Garmina ani danych logowania do Claude.
- Nie jest to porada medyczna - przy niepokojących objawach skonsultuj się z lekarzem.

---

## English

### Requirements
- Windows 10 or 11
- A Garmin Connect account (Garmin watch)
- A Claude account with a **Pro or higher** subscription - the coaching conversation runs in Claude Code on your account

### Install
1. Download [AICoach-instalator.zip](https://github.com/lsielewicz/AICoach-releases/releases/latest/download/AICoach-instalator.zip) and extract it (right-click - "Extract All").
2. Double-click **Zainstaluj.cmd** (install). It adds any missing components and creates an **AI coach** shortcut on the Desktop.
   If Windows shows "Windows protected your PC" - click "More info", then "Run anyway".
3. Start **AI coach** from the shortcut. Switch the language to English in the top-right corner.

### First steps
1. Create a profile (name, sport).
2. **Garmin** tab - sign in with your Garmin Connect account (the password is not stored).
3. **Coach** tab - "Sign in" to Claude (a browser page opens).
4. **New conversation** - the coach asks a few questions about your goal and builds a plan. You'll see it in the **Plan** tab (also as Excel).

### Update and uninstall
- New version: download the zip again and run **Zainstaluj.cmd** - profiles and plans are kept.
- Uninstall: **Odinstaluj.cmd** from the package. Profile data stays in `%APPDATA%\GarminTrener` (delete that folder to remove it).

### Privacy
- Garmin data is read-only and stored locally on your computer.
- The app never sees your Garmin password or your Claude credentials.
- This is not medical advice - if something feels wrong, see a doctor.
