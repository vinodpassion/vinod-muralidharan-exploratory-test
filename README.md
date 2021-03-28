# Monefy app exploratory testing

## Findings from your charters. Did everything work as expected? What bugs were discovered?

yes, everything worked as expected apart from below
 
 - When expenses were provided with zero income then still balance is shown in prositive
 - Add expenses only but not income and clear app data. Then app data still doesnt get removed

## Prioritisation of those charters - which area of the app or testing would you explore first and why?

Below are the prioritisation provided interms of area in the order from High to low

- Installation of App -  High
- Usage of App -  High
- Expenses and income --> smoke testing and detailed testing - High
- Header - New Transfer - High
- Functionality of charts and its association to income and expenses - High 
- Sidebar Accounts  - Medium
- Sidebar Date - Medium
- Options - Categories - Medium
- Options - Accounts - Low
- Options - Settings - Low
- Header-Menu - Low

## How much time you have planned for each charter?

I have decided to spend 2 hours for exploratory testing below are the breakup

| Charter                                                            | Time spent |
|--------------------------------------------------------------------|------------|
| Installation                                                       | 1 hr       |
| Usage                                                              |            |
| Expense & Income                                                   |            |
| Chart                                                              |            |
| Functionality of charts and its association to income and expenses | 45 mins    |
| Sidebar Accounts                                                   |            |
| Sidebar Date                                                       |            |
| Options - Categories                                               |            |
| Options - Accounts                                                 | 15 mins    |
| Options - Settings                                                 |            |
| Header-Menu                                                        |            |



## What kind of risks you need to mitigate for this type of application?

 - First risk is there are more scenarios when you start thinking about the combinations. To mitigate this risk we need to use risk based testing. We need to focus more on high priority area and maximize the coverage and reduce the coverage in low priority aread. 
 - As there are more number of test cases were need to automate most of them, it involves lot of effore, to reduce this effort we can start automating high priority testcases and easy complexity. This way we reduce manual effort in each iteration


## Testcases written for exploratory testing:

| Charter               | Test cases                                                                                                                      | Parameters                                | Outcome(Pass/fail) |
|-----------------------|---------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------|--------------------|
| Installation          | Verify if you are able to install the app                                                                                       |                                           | Pass               |
|                       | Verify if you are able to uninstall the app                                                                                     |                                           | Pass               |
| Usage                 | Verify if you are able to open the app                                                                                          |                                           | Pass               |
|                       | Verify if you are able to close the app                                                                                         |                                           | Pass               |
|                       | Open the app, lock the screen, unlock and try to open the app                                                                   |                                           | Pass               |
| Expense & Income      | Verify if user is able to add income using any category                                                                         |                                           | Pass               |
|                       | Verify if user is able to add income using                                                                                      | Deposit                                   | Pass               |
|                       |                                                                                                                                 | Salary                                    | Pass               |
|                       |                                                                                                                                 | Savings                                   | Pass               |
|                       |                                                                                                                                 | Add                                       | Pass               |
|                       | Verify if user able to add expense using any category with notes                                                                |                                           | Pass               |
|                       | Verify if user is able to add expense using with notes                                                                          | Bills                                     | Pass               |
|                       |                                                                                                                                 | Cars                                      | Pass               |
|                       |                                                                                                                                 | Clothes                                   | Pass               |
|                       |                                                                                                                                 | Communications                            | Pass               |
|                       |                                                                                                                                 | Eating out                                | Pass               |
|                       |                                                                                                                                 | Entertainment                             | Pass               |
|                       |                                                                                                                                 | Food                                      | Pass               |
|                       |                                                                                                                                 | Gifts                                     | Pass               |
|                       |                                                                                                                                 | Health                                    | Pass               |
|                       |                                                                                                                                 | House                                     | Pass               |
|                       |                                                                                                                                 | Pets                                      | Pass               |
|                       |                                                                                                                                 | Sports                                    | Pass               |
|                       |                                                                                                                                 | Taxi                                      | Pass               |
|                       |                                                                                                                                 | Toiletry                                  | Pass               |
|                       |                                                                                                                                 | Transport                                 | Pass               |
| Chart                 | Verify added expense and income are properly shown in charts                                                                    |                                           | Pass               |
|                       | Verify expense showed are correctly mapped the type of expense in the chat                                                      |                                           | Pass               |
| SideBar - Accounts    | Verify Toggling the accounts and it doesnŐt effect the app                                                                      |                                           | Pass               |
|                       | Verify Togging to account in cash and add expenses and income                                                                   |                                           | Pass               |
|                       | Verify Togging to account in card and add expenses and income                                                                   |                                           | Pass               |
|                       | Add income & expense n cash and card, then verify if the overall is reflecting when all accounts selected                       |                                           | Pass               |
|                       | Toggle to Cash and verify only cash related income and expense is displayed                                                     |                                           | Pass               |
|                       | Toggle to card and verify only cash related income and expense is displayed                                                     |                                           | Pass               |
| Sidebar - Date        | Add income & expense for different dates, year , month                                                                          |                                           | Pass               |
|                       | Select <Parameter> and scroll through the dates to verify if the expense and income are provided properly for the selected date | Day                                       | Pass               |
|                       |                                                                                                                                 | Week                                      | Pass               |
|                       |                                                                                                                                 | Month                                     | Pass               |
|                       |                                                                                                                                 | year                                      | Pass               |
|                       |                                                                                                                                 | All                                       | Pass               |
|                       |                                                                                                                                 | Interval                                  | Pass               |
|                       |                                                                                                                                 | Choose date                               | Pass               |
| Header - Search       | Search and verify few from  <Parameters> to make sure the type of expense or income is retreivable and details are shown        | Deposit                                   | Pass               |
|                       |                                                                                                                                 | Salary                                    | Pass               |
|                       |                                                                                                                                 | Savings                                   | Pass               |
|                       |                                                                                                                                 | Bills                                     | Pass               |
|                       |                                                                                                                                 | Cars                                      | Pass               |
|                       |                                                                                                                                 | Clothes                                   | Pass               |
|                       |                                                                                                                                 | Communications                            | Pass               |
|                       |                                                                                                                                 | Eating out                                | Pass               |
|                       |                                                                                                                                 | Entertainment                             | Pass               |
|                       |                                                                                                                                 | Food                                      | Pass               |
|                       |                                                                                                                                 | Gifts                                     | Pass               |
|                       |                                                                                                                                 | Health                                    | Pass               |
|                       |                                                                                                                                 | House                                     | Pass               |
|                       |                                                                                                                                 | Pets                                      | Pass               |
|                       |                                                                                                                                 | Sports                                    | Pass               |
|                       |                                                                                                                                 | Taxi                                      | Pass               |
|                       |                                                                                                                                 | Toiletry                                  | Pass               |
|                       |                                                                                                                                 | Transport                                 | Pass               |
| Header - New Transfer | Verify if card to cash transfer is allowed                                                                                      |                                           | Pass               |
|                       | Verify if cash to card transfer is allowed                                                                                      |                                           | Pass               |
|                       | After doing card to cash transfer, go to cash account and verify transfer type expense is shown                                 |                                           | Pass               |
|                       | Verify if same type of transfer is not allowed                                                                                  |                                           | Pass               |
| Header-Menu           | Click on menu button and verify <parameters> options are shown                                                                  | Categories, Accounts, Currencies, setting | Pass               |
| Options - Categories  | Verify below for each expense and income categories                                                                             |                                           | Pass               |
|                       | Edit category --> change icon                                                                                                   |                                           | Pass               |
|                       | Edit category --> delete category                                                                                               |                                           | Pass               |
|                       | Edit category --> disable category                                                                                              |                                           | Pass               |
|                       | Edit category --> enable disabled category                                                                                      |                                           | Pass               |
|                       | Edit category--> Merge with other category                                                                                      |                                           | Pass               |
| Options - Accounts    | Select exising account and verify if the details are displayed properly                                                         |                                           | Pass               |
|                       | Add new account and verify if the details are displayed propertly                                                               |                                           | Pass               |
|                       | Verify transfer functionality through Options - Accounts                                                                        |                                           | Pass               |
|                       | Delete existing accounts                                                                                                        |                                           | Pass               |
|                       | Enable exising accounts                                                                                                         |                                           | Pass               |
|                       | Disable existing accounts                                                                                                       |                                           | Pass               |
|                       | Change icon for the accounts                                                                                                    |                                           | Pass               |
|                       | Provide Intial account balance                                                                                                  |                                           | Pass               |
|                       | on and off for included in the balance                                                                                          |                                           | Pass               |
| Options - Currencies  | Verify if you are able to use currency option being non pro user                                                                |                                           | Pass               |
| Options - Settings    | Verify in budget mode, everything is working properly                                                                           |                                           | Pass               |
|                       | Verify in carry over mode, everything is working properly                                                                       |                                           | Pass               |
|                       | Verify in future recurring mode, everything is working properly                                                                 |                                           | Pass               |
|                       | Verify language change is working properly                                                                                      |                                           | Pass               |
|                       | Verify overall currency change is successful                                                                                    |                                           | Pass               |
|                       | Verify create backup data is working                                                                                            |                                           | Pass               |
|                       | Verify Restore data is working                                                                                                  |                                           | Pass               |
|                       | Verify clear data is working                                                                                                    |                                           | Pass               |
