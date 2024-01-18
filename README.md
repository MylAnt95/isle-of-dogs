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

1. Would appreciate more comments and it would be nice if they explained more.
2. You have constructed a lot of functions which all look good.
3. Input is not sanitized. But I see you have "TODO" on it in booking.php 15.
4. Hotel name doesnt respond well to smaller viewports.
5. Responsivness looks good overall, adpated to 3 types of devices.
6. Would be nice to have a Home button.
7. Room availability is a bit confusing, you have a calendar in the rooms page but not when you book.
8. + Consistent naming on classes.
9. You could've merged "registerBooking" and "registerFeature" since they both deal with the database. Also "validatePayment" and "depositTransfercode" could be merged.
10. Overall you have done a really good job, hard to find something to complain about! :D 
