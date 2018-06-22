# SeleniumBasic_Ruby
SeleniumBasic_Ruby

## Introduction


## Setup
```
- Install Rubby

- Verify that Installed Ruby

- Install Gem as below
```
## API
Example script:
```
require "selenium-webdriver"

driver = Selenium::WebDriver.for :firefox
driver.navigate.to "http://google.com"

element = driver.find_element(name: 'q')
element.send_keys "Hello WebDriver!"
element.submit

puts driver.title

driver.quit
```
