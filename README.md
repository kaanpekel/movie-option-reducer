# Movie Option Reducer
It helps user to eliminate the infinite scroll mechanisms of streaming services and thus users choice overload problem by reducing the number of options.

Layer 1:
Takes users IMDb watchlist and finds available streaming services using JustWatch API. It also filters them by the subscriptions user has.

Layer 2:
The output.csv can be given to a custom GPT for movie recommendation by duration, genre and streaming service. 
