# Performance Test with JMeter

This project is used to performance test using JMeter on site http://automationpractice.pl/index.php.


## Dependencies

#### Install the items

1. Java Development Kit 8 or 11
2. JMeter 5.5



---

## Run Tests:

#### To download, get clone this project to your computer and execute the commands bellow:

1. Open project with JMeter (ecommerce.jmx).
2. Run test with compiler or execute commands on terminal.
3. To run test in handless on terminal and generate results and generate dashboard, run the command:

```bash
/Users/YOUR_USER/apache-jmeter-5.5/bin/jmeter -t /Users/YOUR_USER/apache-jmeter-5.5/bin/ecommerce.jmx -l /Users/YOUR_USER/apache-jmeter-5.5/bin/results.jtl -e -o /Users/YOUR_USER/apache-jmeter-5.5/bin/results_dash
```

4. To run test with JMeter application on terminal and generate results and generate dashboard, run the command:

```bash
/Users/YOUR_USER/apache-jmeter-5.5/bin/jmeter -n -t /Users/YOUR_USER/apache-jmeter-5.5/bin/ecommerce.jmx -l /Users/YOUR_USER/apache-jmeter-5.5/bin/results.jtl -e -o /Users/YOUR_USER/apache-jmeter-5.5/bin/results_dash
```


---
