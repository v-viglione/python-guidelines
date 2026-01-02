# python-guidelines

# INSTALLAZIONE PYTHON
Seguire il tutorial:
 https://www.youtube.com/watch?v=C3bOxcILGu4&t=95s
fino al minuto 2:30 quindi senza installare IDLE perché noi come ambiente di sviluppo usiamo Visual Studio Code, anche lui da installare (vedi sotto).

# INSTALLAZIONE VISUAL STUDIO CODE
Seguire tutto il tutorial:
https://www.youtube.com/watch?v=cu_ykIfBprI

Aprire VScode e installare le estensioni Python per essere agevolati durante le simulazioni:
1.	Premere l’icona indicata dalla freccia nella figura
2.	Installare le estensioni elencate nella figura (Mypy Type Checker, Pylance, Python, Python Debugger, Python Environments)
 <img width="1004" height="478" alt="image" src="https://github.com/user-attachments/assets/4c20c509-416a-4cdd-b93d-6aca1e37f147" />


# UTILIZZO DI PYTHON SU VISUAL STUDIO CODE
Affinché compili correttamente il codice, prima di tutto bisogna aprire la cartella contente il file .py da lanciare. 
Per farlo, premere: File > Open folder e selezionare la cartella corretta. 
Se tutto è stato eseguito correttamente, nell’Explorer (che si raggiunge cliccando sull’icona indicata dalla freccia rossa nella figura) si dovrebbe trovare proprio la cartella selezionata.
Nell’esempio in figura, il file .py da lanciare è “Batch_runner_v2.py” e si trova nella cartella Olive-FruitFlyModel_v3.
 <img width="1004" height="626" alt="image" src="https://github.com/user-attachments/assets/a7ca1365-df3b-440f-a9c2-ba65bc5f8940" />


# CREAZIONE VIRTUAL ENVIRONMENT
Per creare un virtual environment con VS code:
1.	aprire il terminale nella cartella dove lo si vuole creare
2.	eseguire 
```r
python -m venv nome_venv
```
sostituendo a nome_venv il nome che si preferisce dare alla cartella (normalmente si usa venv)
3.	attivare l’ambiente con .\nome_venv\Scripts\activate
4.	con l’ambiente attivo, per installare le librerie eseguire pip install nome_lib
Si possono anche scrivere le librerie necessarie per un progetto su un file requirements.txt in modo da installarle tutte insieme eseguendo pip install -r requirements.txt
Quest’ultima opzione è particolarmente utile quando si usa il progetto implementato da un altro utente e si deve creare il proprio virtual environment per quel progetto.

# SPECIFICO PER PROGETTO OLIVO
Data/ora del PC dev’essere nel formato inglese (mm/gg/yy)
