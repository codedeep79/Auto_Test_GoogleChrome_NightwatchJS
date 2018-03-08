### This project is auto test Google Chrome demo NightwatchJS on Ubuntu

### Auto test Google Chrome demo NightwatchJS on Windows 

At file nightwatch.json changes:
  ```
  "cli_args" : {
        "webdriver.chrome.driver" : "drivers/chromedriver",
        "webdriver.gecko.driver" : "drivers/geckodriver"
   }
  ```
  to
  ```
  "cli_args" : {
        "webdriver.chrome.driver" : "drivers/chromedriver.exe",
        "webdriver.gecko.driver" : "drivers/geckodriver.exe"
   }
 ``` 
 Build unit test:
 
 + Start Server: `java -jar selenium-server-standalone-3.4.0.jar`
 + Run Project: nightwatch 
 
 Note: Download driver selenium version suitable with your OS at [click](https://www.seleniumhq.org/download/)

  
