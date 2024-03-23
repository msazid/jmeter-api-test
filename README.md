# Money transaction api test usig Jmeter

<p>This repository contains a series of API tests designed to validate the functionality of a money transaction system. The tests cover common scenarios including agent and customer creation, deposits, balance inquiries, withdrawals, and payments. These tests were implemented using Apache JMeter to ensure the reliability and performance of the system under varying transaction loads. Refer to the test scripts for detailed scenarios and configurations.</p>
<h3></h3>
<h3>Tools used</h3>
<ul>
  <li>Jmeter</li>
  <li>VS Code</li>
</ul>

<h3>Jmeter guide</h3>
<ul>
  <li>Adding Thread Group: Begin by creating a thread group to simulate user behavior.</li>
  <li>Adding HTTP Request Sampler: Add an HTTP request sampler to represent the API endpoint you want to test.</li>
  <li>Adding Listeners: Include listeners such as View Result Tree and Summary Report to monitor test results.</li>
  <li>Adding Timers: Use timers, like Constant Timer, to control the frequency of requests.</li>
  <li>Adding User Defined Variables: Set up user-defined variables to store predefined values like URLs and keys.</li>
  <li>Adding HTTP Header Manager: Configure an HTTP header manager to add necessary headers, such as Content-Type for JSON requests.</li>
  <li>Adding Post Processors: Include post processors like JSON Extractor to extract tokens or other values from responses.</li>
  <li>Adding Random Variable: Introduce random variables for generating random values during testing.</li>
  <li>Adding Assertions: Set up assertions, like JSON Assertion, to verify the correctness of responses.</li>
  <li>Adding CSV Data Set Config: Incorporate a CSV data set config to parameterize test data, allowing for iteration over multiple inputs.</li>
</ul>
