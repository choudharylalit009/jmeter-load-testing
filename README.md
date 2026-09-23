# JMeter Performance & Load Testing

A performance and load testing project using **Apache JMeter** to simulate concurrent users, execute application/API requests, and analyze system performance through response time, throughput, and error-rate metrics.

## 📌 Project Overview

This project demonstrates the implementation of **performance testing and load testing using Apache JMeter**.

The test plan is designed to simulate concurrent users and evaluate how the target application/API behaves under load. The project includes the complete JMeter test plan, aggregated test results, an HTML performance report, and response-time visualization.

## 🛠️ Technologies & Tools

- Apache JMeter
- Performance Testing
- Load Testing
- Stress Testing
- API Testing
- HTTP Request Testing
- CSV Data Analysis
- HTML Reporting
- Git
- GitHub

## 🎯 Testing Objectives

- Simulate multiple concurrent users
- Evaluate application performance under load
- Measure request response times
- Analyze throughput and request-processing rate
- Monitor failed requests and error percentage
- Analyze system behavior under concurrent load
- Generate detailed performance reports
- Visualize response-time performance

## 🧪 Testing Workflow

    Concurrent Users
           ↓
        JMeter
           ↓
    HTTP/API Requests
           ↓
    Response Validation
           ↓
    Performance Metrics
           ↓
      Result Analysis
           ↓
    HTML Report & Graphs

## 📊 Performance Metrics

| Metric | Description |
|---|---|
| Response Time | Time taken by the application to respond to a request |
| Average Response Time | Average response time across executed requests |
| Minimum Response Time | Lowest recorded response time |
| Maximum Response Time | Highest recorded response time |
| Throughput | Number of requests processed per unit of time |
| Error Percentage | Percentage of failed requests |
| Total Requests | Total number of requests executed |

## 📈 Test Results

The repository contains the performance results generated during test execution.

### Response Time Graph

The response-time visualization is available in:

`Response time graph.png`

The graph provides a visual representation of response-time behavior during the test execution.

### Aggregate Results

The aggregated performance results are available in:

`aggregate.csv`

The CSV file contains performance-related metrics collected during the test execution.

### HTML Performance Report

The generated JMeter HTML report is available in:

`index.html`

The report provides detailed information about the test execution and performance metrics.

## 📂 Project Structure

    jmeter-load-testing/
    │
    ├── README.md
    ├── Testing.jmx
    ├── aggregate.csv
    ├── index.html
    └── Response time graph.png

### File Description

**Testing.jmx**

The main Apache JMeter test plan containing the test configuration and execution setup.

**aggregate.csv**

Contains aggregated performance-testing results generated during test execution.

**index.html**

Contains the generated HTML performance report.

**Response time graph.png**

Contains the response-time visualization generated from the test results.

**README.md**

Project documentation containing the testing approach, tools, results, and instructions.

## 🚀 How to Run

### Prerequisites

Install the following:

- Java
- Apache JMeter

### Steps

1. Clone the repository:

   `git clone https://github.com/choudharylalit009/jmeter-load-testing.git`

2. Open Apache JMeter.

3. Open the JMeter test plan:

   `Testing.jmx`

4. Review and configure the required test parameters.

5. Run the test plan.

6. Analyze the generated performance metrics and reports.

## 🔍 Testing Approach

### 1. Test Configuration

Configure the JMeter test environment and required testing parameters.

### 2. User Simulation

Use JMeter Thread Groups to simulate concurrent users.

### 3. Request Execution

Execute HTTP/API requests against the target application.

### 4. Response Validation

Validate responses and identify failed requests.

### 5. Performance Measurement

Collect response-time, throughput, request-count, and error-related metrics.

### 6. Result Analysis

Analyze the collected performance data using JMeter results and reports.

### 7. Visualization

Use generated graphs and reports to understand application performance.

## 💡 Key Learning Outcomes

Through this project, I gained practical experience in:

- Apache JMeter
- Performance Testing
- Load Testing
- Stress Testing
- API Testing
- Concurrent User Simulation
- JMeter Test Plan Development
- Response-Time Analysis
- Throughput Analysis
- Error-Rate Analysis
- Performance Report Generation
- Test Result Analysis

## 📚 Skills Demonstrated

- Performance Testing
- Load Testing
- Stress Testing
- API Testing
- Test Automation
- Apache JMeter
- Test Plan Development
- Performance Analysis
- Test Reporting
- Data Analysis

## ⚠️ Disclaimer

This repository is intended for **learning, demonstration, and portfolio purposes**.

No confidential credentials, authentication tokens, customer information, or other sensitive information should be included in this repository.

## 👨‍💻 Author

**Lalit Choudhary**

B.Tech — Civil Engineering  
Indian Institute of Technology Hyderabad

GitHub: https://github.com/choudharylalit009
