
## Features
 - Sample Page Object Pattern 
 - Sample Selenium Tests 
 - Dockerfile setup
 - BrowserStack Setup Support
 - More to Come! 

## Usage

- docker run -it -p 4444:4444 shawnshaligram/selenium-webdriver-docker-boilerplate
- Selenium UI is available at: http://DOCKERHOST:4444/wd/hub/static/resource/hub.html
- You should be able to click the "Create session" button and select "Chrome"

## Write tests

Check out [this document](http://www.seleniumhq.org/docs/) for Selenium's concepts and operations.

To write new tests, you can either bind mount your python files to the container or create a new Docker image and copy files into the image.
The example code is located at `tests` and `page_objects` in the container. You may overwrite this file or place your files at different locations


## Library documentation

- Selenium http://www.seleniumhq.org/docs/
- ChromeDriver https://sites.google.com/a/chromium.org/chromedriver/
- BrowserStack https://www.browserstack.com
- Cucumber http://www.rubydoc.info/github/cucumber/cucumber-ruby/
- Docker https://docs.docker.com/engine/quickstart/
