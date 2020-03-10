# Check Canada visa processing time

A replacement for
[Check processing times - Canada.ca](https://www.canada.ca/en/immigration-refugees-citizenship/services/application/check-processing-times.html)
that supports URL query strings.

# Example

http://chrisxue815.github.io/canada-visa-processing-time/index.html?type=visitor-outside-canada&country=US

This will show you the processing time for `visitor-outside-canada` in `US`.

Parameters:
* type (Required): Which visa type are you applying for? Go to the data sources below to see the full list of supported values.
* country (Required): Where are you applying from? Go to the data sources below to see the full list of supported values.
* start (Optional): If provided, an anticipated visa approval date (start + processing time) is displayed on the page.

# Data sources

* https://www.canada.ca/content/dam/ircc/documents/json/data-ptime-en.json
* https://www.canada.ca/content/dam/ircc/documents/json/data-country-name-en.json
