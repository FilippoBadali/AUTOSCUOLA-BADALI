per avviare l'applicazione:
 Comandi per il venv:                         
       python -m venv .venv                       
       .venv\Scripts\activate                     
                                                  
   Comandi per installare le librerie:            
       pip install flask                          
       pip install flask-session                  
       pip install mysql-connector-python        
       pip install redis
       se mancano delle cose da installare si fa pip install e il nome che ti chiede
                                                  
   Comando per lanciare l'app:                    
       cd cartella salvata            
       python server.py                           
        
    avviare redis prima dell'uso:                                
       cd C:\Programmi\Redis                      
       redis-server.exe                           
   tenere aperto in un altro terminale redis 

   avviare MYSQL con XAMP
   
   se non dovesse funzione controllare nella cartella .env se corrisponde con le varie porte del proprio computer
   una volta che starta si vede il link, bisogna schiacciarlo e aprirà una pagina web, può darsi che dia sito non sicuro, continuare lo stesso e aprire il link.
   se non starta ancora c'è scritto l'erroe, se non si ha il database salvato in locale, te lo crea lui in automatico. ATTENZIONE: se non vede prenotazioni e         lezioni è perchè ho fatto in modo che si vedano dal giorno stesso in avanti e non quelle vecchie dunque vanno aggiunte dall'istruttore
    
   funzionalità base:
    RUOLI:
    - non loggato: vede solo la pagina iniziale, se prova a schiacciare le varie funzionalità vedrà sempre la pagina di login
    - studente: vede le funzioni principali: prenotarsi,seguire le lezioni e fare quiz. non può aggiungere date o studenti
    - istruttore: può aggiungere date per le prenotazioni,lezioni,quiz,utenti. PUO’ FARE TUTTO
