Instrukcja Minecraft
====


Instalacja
---

**Windows**

1. Zainstaluj Minecrafta z [tego linka](https://minecraft.net/pl-pl/download/)
2. Zainstaluj następnie [MinecraftForge](https://files.minecraftforge.net/) (wybierz instalator zalecany (*Recommeneded*).
3. **TODO**

**MacOS**

1. Zainstaluj Minecrafta z [tego linka](https://minecraft.net/pl-pl/download/)
2. Zainstaluj następnie [MinecraftForge](https://files.minecraftforge.net/) (wybierz instalator zalecany (*Recommeneded*).
3. Podczas instalacji MinecraftForge wybierz folder domyślny instalacji (`Application Support/minecraft`).
4. Po zainstalowaniu uruchom Minecrafta i wybierz Graj Forge. Kiedy inicjalizacja zostanie zakończona, wyłącz grę.
5. Idź do katalogu `/minecraft/mods` (`cd ~/Library/“Application Support”/minecraft/mods`)
6. Pobierz moda dla Pythona używając komendy `wget https://github.com/arpruss/raspberryjammod/releases/download/0.94/mods.zip`. Jeśli nie masz wgeta, możesz je pobrać ręcznie i wrzucić do katalogu `mods`.
7. Wypakuj moda używając `unzip mods.zip` lub ręcznie.
8. Idź wyżej, do katalogu `minecraft` i zainstaluj `python-scripts`: `wget https://github.com/arpruss/raspberryjammod/releases/download/0.94/python-scripts.zip` (także możesz to zrobić ręcznie jak w pkt. 6).
9. Wypakuj skrypty w katalogu `minecraft`: `unzip python-scripts.zip`.
10. Sprawdź czy wszystkie skrypy są umieszczone w katalogu `minecraft/mcpipy`. 



Uruchamianie skryptów
---
1. Uruchom Minecrafta
2. Wybierz Tryb jednoosobowy --> Stwórz nowy świat --> Wybierz:
	- Tryb gry: **Kreatywny** 
	- Więcej opcji świata: 
	    - Generuj struktury: **Wył**
	    - Typ świata: **Super płaski**
3. Uruchom skrypt podczas gry:
   - Uruchom konsolę / terminal klikając `/` na klawiaturze
   - wpisz: `py twoj-skrypt`

   
Edytor kodu
---
Będziemy używać **VS Code**, który można pobrać [stąd](https://code.visualstudio.com/).

1. Zainstaluj VS Code.
2. Otwórz edytor i następnie otwórz folder ze wszystkimi skryptami `minecraft/mcpipy`.
3. Edytor zapyta, czy zainstalować rozszerzenie Python --> wyraź zgodę.
4. Możesz teraz przejść do kodowania. 


