# Selenium Tests

### Required gems:
  * rspec
  * selenium-webdriver

Ensure ruby is on your PATH, the rspec gem installs a script to this location. Tests assume selenium server is running on localhost and port 4444. This can be changed in spec/spec_helper.rb

To run all of the tests:
`rspec . --format html --out testResults.html`
