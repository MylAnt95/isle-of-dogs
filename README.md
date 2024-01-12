<img src="https://media.giphy.com/media/QgKsU1OlXJc5yAn3JH/giphy.gif" width="100%">

# Isle of dogs

Welcome to Isle of dogs, with its endless beaches, piles of tennis balls, and cotton candy sky.

# Bolmond Cockapoo Palace

Dive in the pool, chew on a sun lounger, or do some dog-watching in the hotel bar with a delicious mocktail. Enjoy a dinner prepared by top chefs before cuddling down in the fluffy duvets - perhaps with your human by your side?

("Bring human" is a feature offered for an additional fee)

# Database structure

ROOMS
id
name
price
imageUrl
info

FEATURES
id
name
price
imgUrl

BOOKINGS
id
arrival_date
departure_date
first_name
last_name
room_id
total_cost
transfer_code

BOOKINGS_FEATURES
feature_id
booking_id

# Instructions

If your project requires some installation or similar, please inform your user 'bout it. For instance, if you want a more decent indentation of your .php files, you could edit [.editorconfig]('/.editorconfig').

# Code review

1. + Koden är väldigt lättläst men några fler kommentarer hade inte skadat.
2. + Snyggt med så många funktioner.
3. + Inget hårdkodat.
4. - Kunde använt en funktion för att skicka bokning till databas.
5. + Bra struktur på projektet (varje sektion har egen php fil med funktioner separerade).
6. Funktionen "calculateDiscount(int $days)" Kunde varit kompaktare eller integrerat med en totalcost funktion.
7. Lite otydligt med hur bokade datum för rum visas.
8. Input från användare är inte saniterad.
9. Namn på klasser är tydliga, lätt att förstå vad de gör.
10. Koden är så välkodad och strukturerad så att jag inte kan hitta fler punkter.. :D
