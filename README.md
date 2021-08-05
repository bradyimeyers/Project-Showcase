# Title
- Linked List Data Structure

# Description
- A singly linked list structure created from scratch, capable of holding a collection of bids from CSV data (informtion extracted from a local municipal government data feed containing bids submitted for auction of property)
- Console menu interface to load CSV files, display bids, find bids, sort bids, and manually enter/remove bids
- Tick Clock to measure speed/performance of sort function

# Included CSV Files
- eBid_Monthly_Sales.csv (larger set of 12,023 bids)
- eBid_Monthly_Sales_Dec_2016.csv (smaller set of 76 bids)

# Features
- LinkedList.cpp
  + Structured to hold bid information
  + Append, Prepend, PrintList, Remove, Search Methods
  + Uses CSVparser to parse through CSV and load each bid into data structure
  + Singly linked list to iterate through nodes for printing bids, removing bids, and searching bids

- CSVparser.cpp
  + Public API used to parse CSV files
  + Determine if data sets are empty, corrupted, or don't exist
  + Determines if header exists/when to skip header
