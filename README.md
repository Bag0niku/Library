# Library
manage your inventory of books, movies and games all in one place.


## Planned Features:
- Basic information about each entry
    - Books: {publisher: string, author: string, title: string, pages: int, hardcover: bool, edition: int, original_publish_date: date, edition_publish_date: date, purchased: date, purchase_location: string, language:string, condition: (string or int_rating, undecided), series: string}
    - Movies: {director: string, producers: list, title: string, rating: int, location: string, condition: (same type as books), studios: list, starring: list, series: string, release_date: date, remake: bool}
    - Games: 
      - Video Games: {title: string, publisher: string, remake: bool, series: string, genre: string, system: string, rating: int, studio: string, release_date:date, multiplayer: bool, max_players: int}
      - Boardgames: {title: string, publisher: string, release_date: date, max_players: int, min_players: int, average_playtime:(datetime or string)}
- Location in the house. (ex. Living Room)
- Did someone borrow it? Mark it as Borrowed  (their user id, date borrowed... )
- able to track user stats related to the objects. (history of borrowing, times played/read/watched, game stats, solo/group?)
- track wishlist and lost inventory 
- category/genre tags 
