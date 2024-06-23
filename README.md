# Eliminate Infinite Scroll and Choice Overload on Streaming Services
This little project helps users to overcome the infinite scroll mechanism of streaming services, thereby reducing choice overload by limiting the number of options available.

Layer 1: Watchlist and Streaming Service Integration
- Takes the user's IMDb watchlist.
- Finds available streaming services in user's country using the JustWatch API.
- Filters results based on the user's subscriptions.

Layer 2: Custom GPT Movie Recommendations
- The output is saved to an output.csv file.
- This file can be fed into a custom GPT model for movie recommendations. (or instead a random function can be used to choose one)
- Recommendations are based on duration, genre, and streaming service availability.
