# trade-bot

## Summary

So the tradebot should do a couple of things.

### Requisites:

-   Web scraper functionality

#### Why web scrape:

-   Get url endpoints to build platform

### MVP:

-   Needs to be a REPL environment
-   allows user input

    -   examples:
        -   open msft 9/4 250 1.5 should send (calls by default) to a broker to open a call contract for msft with an expiration of 9/4 for a limit buy of 1.5
        -   close msft 9/4 250 2 should send a sell (call) order to

-   connects to a trading site -- Webull
    -   handles the login and mfa nuances
-   Takes the users input and makes a LIMIT order on a security's option
    -   see above in allowing user input
