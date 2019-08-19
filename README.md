# Stock Tracker

### Overview

Stock Tracker is a financial app that uses the _IEX Trading API_ to request stock data for a searched company

### Implementation

This app has 4 View Controller Scenes:

* __CompanySearch__- When the app is launched the user is presented with a simple background view, watchlist button, and search bar. The user can enter the name of a desired company to search or press the watchlist button and they are directed to the their watchlist. If a new company is entered the API fetches and parses all the companies(and their data) that match the search while the user is directed to the Symbol View.

* __CompanyDataProfile__- The user is presented with a list of companies that match the search to choose from. Once the user selects a company they are then direted to the Quote View.

* __CompanyKeyData__- The data for selected company is then displayed in a tableview. If the user wants to add selected company to their watchlist they simply press the +watchlist button and are directed to the Watchlist view while selected company is saved in core data. When the user is finished they can simply back out to the Search view to enter a new company.

* __CompanyNews__- This view allows the user to see the companies they have saved. It can be accessed from the Search view or when a new company is added.




### Requirements
* Xcode 10.0
* Swift 5.0
