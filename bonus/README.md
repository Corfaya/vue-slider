# TRACCIA
Descrizione:
Partendo dal markup della versione svolta in js plain, rifare lo slider ma questa volta usando Vue.
Bonus:
1- al click su una thumb, visualizzare in grande l'immagine corrispondente
2- applicare l'autoplay allo slider: ogni 3 secondi, cambia immagine automaticamente
3- quando il mouse va in hover sullo slider, bloccare l'autoplay e farlo riprendere quando esce

# FLOW
- Istanza di applicazione
- Metodo createApp() di VUE
    - Tramite data() definire i dati dell'applicazione
        - Restituire array di oggetti ("slides")
        - Restituire una variabile per la slide attiva
    - Tramite methods property definire le funzioni dell'applicazione
        - Funzione per ciclo infinito in incremento
        - Funzione per ciclo infinito in decremento
- Montare l'applicazione su elemento del DOM