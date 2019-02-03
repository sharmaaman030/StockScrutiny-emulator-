# **StockScrutiny-Emulator**

A stock market simulator is a webapp where users and buy and sell real life stocks using fake money. Users have to pay the actual market price and all the other charges to buy the stocks.

## Requirements

TBD

The following technologies will be used:
- Javascript and jQuery [Frontend]
- Bootstrap [Frontend]
- Node.js [Backend]
- MongoDB with NoSQL [Backend]
- UDP and TCP Protocol [Network]

## Action Plan

### Backend

1. CLIENT

- [ ] Make the protocols for connection between MDU & CLIENT and CLIENT & BOOK.
- [ ] Make the Backend functions of the CLIENT.
      - [ ] Reading the data from .json file which was received from MDU.
      - [ ] Encrypting the buy/sell order to sent it to BOOK server.
      - [ ] Sending the Encrypted data to BOOK and receiving the acknowledgment from BOOK server.
      - [ ] Storing the list of stocks available in cache.

2. BOOK  

- [ ] Make the protocols for connection between MDU & BOOK and BOOK & CLIENT.
- [ ] Make the Database schema for BOOK.
- [ ] Make the Backend functions of the BOOK.
     - [ ] Decrypting the data received from CLIENT.
     - [ ] Reading the data from .json file which was received from MDU.
     - [ ] Updating the database with the data received from CLIENT and MDU.
     - [ ] Sending the acknowledgment to the CLIENT.

3. MDU

TBD

### Frontend

~~
1. There will be a dashboard. Users will only get access to this once they signup for login. This page will also be separated into several components.

- [ ] A component which will show the stock that the user currently holds. It will only be visible when the user click on the show stock button. This component will be situated in the the left side of the webpage.
- [ ] A component of searchbar. User can enter the name of the stock in this searchbar and information of that particular will be retrieved from the API. It will also include a "Add to the watchlist" button. This component will go in the upper middle portion of the page.
- [ ] A component of watchlist. This will show the real time data of stocks that the user currently does not own but wants to buy. The real time data include stock name, current market price, OHLC for that day and volume. We will also include a buy and sell button. The Sell button will be grayed out until the user own that stock. This component will go in the lower middle portion of the page.
- [ ] A box that shows the amount of money the user currently has will also be included. It will be situated the top right corner. A button to logout will also be included. It will be situated in the lower right corner.
- [ ] Assemble all the above component in a single webpage.

2. There will be a signup page where users have to input their details to get access to the website. The signup page will be divided into several components.

- [ ] Make a component of login (for registered user)
- [ ] Make a component of signup (for unregistered user)
- [ ] Make a component of component (button) to switch between login and signup
- [ ] Assemble all of them into a single webpage.
~~

## Running The Test

TBD

## Working (Internal):

TBD

## Contribution 

TBD

## Author

- [Supragya Raj](https://github.com/supragya)

## List of Contributors

TBD