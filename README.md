# Current Corona Cases

An Excel Spreadsheet that updates with the current data from John Hopkins [(link to their repo)](https://github.com/CSSEGISandData/COVID-19)
but offers a little more details about the current situation in each country

## Select Countries to Compare

In the section for Confirmed cases just replace any name in the first column with the one you would like to add (needs to be named exactly like in the data from John Hopkins) and charts will be automatically updated

## Select Country for more details

Under Currently selected find the name of the Country in green. You can then use the dropdown to select one of the countries specified under Confirmed Cases to have a closer look at the situation

## Deaths and Recoveries

Rows will automatically be filled like the ones under the section Confirmed Cases

### Immediacy of the data

You can always hit Refresh data to get the latest stand from their github database. However this data seems to be a little behind the one on their website and the sheet is not using the REST API which might be a little more up to date

## To Do

Until now you will have to adjust the Range of the Charts manually each day (I am trying to post updates every day though). To do that you will have to select the chart and pull the range out further. However I hope I'll manage to finish up a Macro this weekend that will take care of that automatically.