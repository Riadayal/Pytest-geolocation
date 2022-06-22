# How to add geolocation to an automation test in Pytest on [LambdaTest](https://www.lambdatest.com/?utm_source=github&utm_medium=repo&utm_campaign=Pytest-geolocation)

If you want to run your automation test for a particular location in Pytest on Lambdatest, you can use the following steps. You can refer to sample test repo [here](https://github.com/LambdaTest/pytest-selenium-sample).

# Steps:

To run your automation test from a particular location to test location based functionality, you can change the geolocation using the 'geolocation' capability:

 ```python
capabilities = {
        "build": "Sample PY Build",
        "platformName": "Windows 11",
        "browserName": "Chrome",
        "browserVersion": "latest",
		"geoLocation": "US"
}
 ```

For the full list of available geolocations, you can refer [here](https://www.lambdatest.com/support/docs/selenium-automation-capabilities/#selenium-automation-testing-from-different-geolocations).

## Run your test

```bash
cd tests //navigate to tests directory
python sample_todo.py
```

# Links:

[LambdaTest Community](http://community.lambdatest.com/)

