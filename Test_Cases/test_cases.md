### Below you can find high level test cases based on the allegro.pl web site. ###

| First Header  | Second Header |
| ------------- | ------------- |
| Content Cell  | Content Cell  |
| Content Cell  | Content Cell  |


| NO  | TITLE | PRECONDITIONS  | EXPECTED RESULT |
| ------------- | ------------- | ------------- | ------------- |
| 1.  | Registering new user.  | E-mail and user name not exist in database. | New user succesfully registered. |
| 2.  | Logging into account. | User has an account.  | User successfully logged to the account.  |
| 3.  | Changing localization configuration.  | -  | Flag in the button changed into selected country flag.  |
| 4.  | Changing language cofiguration.  | -  | Language of the site changed entirely into selected language.  |
| 5.  | Changing currency cofiguration.  | -  | Prices of the products changed into selected currency.  |
| 6.  | Adding item to the chart for unlogged user.  | -  | Item successfully added to the chart and Small round icon with number “1” appears on the chart icon. |
| 7.  | Adding item to the chart for logged user.  | User logged to the account.  | Item successfully added to the chart and Small round icon with number “1” appears on the chart icon.  |
| 8.  | Changing amount of items in the chart.  | User logged to the account.  | The amount of items in the chart increased  and the total amount icreased proportionally.  |
| 9.  | Deleting items from the chart.  | At least two items added to the chart.  | Items deleted from the chart, notification that the chart is empty appears.  |
| 10.  | Changing item amount in the chart into number with minus.  | At least one item added to the chart.  | The amount of items in the chart changed into “1”.  |
| 11.  | Deselecting items in the chart.  |  At least two items added to the chart.  | Deselected item visible in a grey shadow, the value of the chart shows only of only the value ot the selected item.   |
| 12.  | Adding items to the chart from the same supplier from chart view.  |  At least one item added to the chart.  | Sucessfully added items from the selected supplier and all added items visible one under another, under selected supplier section.   |
| 13.  | Checking notifications of the logged user.  |  User correctly logged.   | Open user notifications section.   |
| 14.  | Checking messages of the logged user.  |  User correctly logged.   | Open user messages section.   |
| 15.  | Adding item to observe section.  |  User correctly logged.   | Items visible correctly in the observed items section.   |
| ------------- | ------------- | ------------- | ------------- |


