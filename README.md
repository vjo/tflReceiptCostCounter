# About
**Transport For London(TFL)** provides the option to it's customers to download a csv file that contains their travelling info for the last 7 days or for a specific month(in the last year, from the current date). However, the generate csv file contains entries for the cost of each trip withoug providing a total cost for all the trips in the file. 
**tflReceiptCostCounter** reads the generated csv file, sums up the trips and provides you with the total. This tool can be handy for people who rely on those csv files from TFL to submit expenses.

# Usage
- To show the help dialog
```bash
./tflReceiptCostCounter --help
./tflReceiptCostCounter -h
```
- To calculate the sum of daily travels from a csv file
```bash
./tflReceiptCostCounter --input <path to your csv file>
./tflReceiptCostCounter -i <path to your csv file>
```

# Install
Grab the generated artifact from the latest sucessful action(https://github.com/ipavlidakis/tflReceiptCostCounter/actions?query=workflow%3ASwift+is%3Asuccess)

# Next steps
My next plans are to migrate from my custom argument parser to the one provided by Apple(https://github.com/apple/swift-argument-parser)
