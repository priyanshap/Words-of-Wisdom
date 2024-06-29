# Words-of-Wisdom

This code implements a web scraping and guessing game program. Here's a description of its functionality:

## Web Scraping:
The program scrapes quotes from the website "http://quotes.toscrape.com/".
It uses the requests library to fetch web pages and BeautifulSoup for parsing HTML.
It iterates through multiple pages of quotes, extracting the quote text, author, and author's bio link.
All scraped quotes are stored in the all_quotes list.


## Quote Guessing Game:
A random quote is selected from the scraped data.
The user is presented with the quote and asked to guess the author.
The user has 4 attempts to guess correctly.


## Hint System:
If the user doesn't guess correctly, hints are provided:
After the 1st incorrect guess: The author's birth date and place.
After the 2nd incorrect guess: The first letter of the author's first name.
After the 3rd incorrect guess: The first letter of the author's last name.




## Game Flow:
The game continues until the user guesses correctly or runs out of attempts.
If the user guesses correctly, a congratulatory message is displayed.
If the user runs out of attempts, the correct author is revealed.


## Additional Features:
The program includes delays between web requests to avoid overwhelming the server.
It uses emoji in print statements for a more engaging user interface.
