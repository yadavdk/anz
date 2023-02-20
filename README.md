Requirements
•Java Development Kit
•Maven
•WebDriver, using ChromeDriver

Running Tests
•Clone the repository from your fork to this directory
•Open the project using any Java IDE
•Run the tests with the script below `shell $ mvn clean install `
•If you want to run the specific test, use the cucumber tags like this `shell $ mvn clean install -Dcucumber.filter.tags="@REPLACE_WITH_ANY_TAGS_THAT_YOU_WANT" `

Test Results
•Test report automatically generated on target folder after finished the test execution
•See test report from target/cucumber-reports/advanced-reports/cucumber-html-reports/overview-features.html
•You can also share your Cucumber Report with another person at https://reports.cucumber.io, just go to src/test/resources/cucumber.properties then change the value to be true `properties cucumber.publish.enabled=true `
•For more information about reports cucumber you can go to https://reports.cucumber.io/docs/cucumber-jvm

