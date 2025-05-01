# GridSelenium

## Prerequisites
- Java 11 or higher installed
- Browser(s) installed
- Browser driver(s)
  - Selenium Manager will configure the drivers automatically if you add --selenium-manager true.
  - Installed and on the PATH
  - Download the Selenium Server jar file from the latest release
- Start the Grid
  - java -jar selenium-server-<version>.jar standalone
- Point* your WebDriver tests to http://localhost:4444
- (Optional) Check running tests and available capabilities by opening your browser at http://localhost:4444