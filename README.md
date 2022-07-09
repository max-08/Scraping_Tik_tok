# Scraping_Tik_tok
Effetua lo scraping di un hashtag di TikTok e restitusce in formato JSON il file di testo con tutte le informaizioni, di Account, Utenti... ecc; da sostituire nel codice la variabile TAG con la chiave di ricerca.


PREREQUISITI
Installazione librerie 
https://github.com/davidteather/TikTok-Api

1) pip install TikTokApi
2) python -m playwright install
3) Recuperare la sessione di cookie dal browser, accedere a TikoTok, andare sul lucchetto e selezionare il cookie "s_v_web_id" copiare il contenuto "verify_l5b32qzh_XXXXXXXXXXXXX" ed inserirlo nella variabile  "verify_fp"
4) attivare una VPN o un server Proxy altrimenti il social blocca le connessioni
5) lanciate lo script solo da terminale 
python3 Scraping_Tik_tok.py
6) Restituirà un link che va copiato nel browser
7) Il contenuto sarà in formato JSON
![Schermata da 2022-07-09 16-07-15](https://user-images.githubusercontent.com/52009177/178109318-7bcb6efc-38b6-4727-be7c-4ab0905a7ed8.png)
8) Utilizzate alcuni dei formattatori per JSON - https://jsonformatter.org/ e riceverete le informazioni dei video in formato leggibile, si può esportare il contenuto in file di testo, TXT;
 ![Schermata da 2022-07-09 16-13-35](https://user-images.githubusercontent.com/52009177/178109607-12619598-e190-4e15-9175-aecf0957e5bc.png)
![Schermata da 2022-07-09 16-13-28](https://user-images.githubusercontent.com/52009177/178109610-562eafff-a5a8-4f8e-a6cc-8d72f823e34a.png)
