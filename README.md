# Apie:

![](img/screen.png)


Ši programa naudoja `tkinter` biblioteką, kad sukurtų grafinį langą, kuris atvaizduoja orų informaciją, NordPool elektros kainas ir naujienas iš įvairių šaltinių.

## Diegimo instrukcijos

1. Įdiekite reikalingas bibliotekas:
   ```sh
   pip install -r requirements.txt 
2. Sukurkite config.py failą šakniniame programos kataloge, kuriame bus lokacija ir kiti parametrai:
   ```sh    
    location = "city"  # Enter city    
3. Paleiskite programą:
    ```sh
   python main.py
## Naudojimo instrukcijos
Programa atvaizduoja šią informaciją:

Orai: Rodo orų informaciją.

NordPool elektros kainos: Rodo NordPool elektros kainų informaciją.

Naujienos: Rodo naujienas iš skirtingų šaltinių (15min, LRT, Delfi, Verslo žinios) iš news.py.

### Ši programa naudoja šias papildomas bibliotekas:

1. **beautifulsoup43**
   - HTML ir XML analizės biblioteka, naudojama duomenų ištraukimo iš tinklalapių, pvz., naujienų šaltinių (pvz., `news.py`).
2. **pillow**
    - Išplėstinė vaizdų apdorojimo biblioteka, naudojama orų ir vėjo krypties ikonų perdirbimui ir atvaizdavimui.

3. **pynordpool**
    - Biblioteka, skirta NordPool elektros kainų duomenų gavimui.
4. **request**
    - GET ir POST užklausos: Siųskite užklausas ir gaukite atsakymus iš serverių