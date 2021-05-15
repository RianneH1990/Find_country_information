##Steps
    
    0. Setup
    
    1. zoek knop maken -> die data ophaalt over belgie
        - [x] HTML
            - [x] Knopje maken
            - [x] geef hem een id
        - [] interactie programmeren
            - [x] knopje selecteren document.getElementById
            - [x] Voeg event listner toe "button".addEventListner
            - [x] Event handler async functie maken, die wordt uigevoerd als je klikt
        - [x] requist naar de api 
            - [x] axios installeren/importeren
            - [x] url opzoeken voor belgie (api docs)
            - [x] axios.get(url)     
            - [x] Await ervoor zetten (anders krijg je een promise)
            - [x] we hebben de data (loggen)


7. Voeg een plaatje toe aan de pagina (de flag van het land)

- [ ] zoek de url van het plaatje (uit de response van de api)
- [ ] HTML
- [ ] div maken (met id)
- [ ] div selecteren (getElement)
- [ ] createElement -> img
- [ ] url toevoegen aan het plaatje `img.src = url`, `img.setAttribute('src', url)`
- [ ] appendChild -> aan het divje

8. Maak een inputveld op de pagina en zorg ervoor dat als de gebruiker op enter drukt, de functie wordt aangeroepen waarmee de gegevens over België worden opgehaald.

- [ ] HTML
- [ ] Maak een inputveld
- [ ] id geven aan het inputveld
- [ ] Interacties programmeren
- [ ] Input veld selecteren
- [ ] Event listener toevoegen aan her inputveld (keyup)
- [ ] In het event kijken naar de "code" (event.code)
- [ ] Als event.code "Enter" is dan -> data ophalen uit de api

9. Zorg ervoor dat de waarde uit het input veld wordt gebruikt als query voor het GET request.

- [ ] selecteer het input veld (const inputfield = document...)
- [ ] const query = inputfield.value
- [ ] vervang belgium in url voor de "dynamische waarde" (query)

        