# Random-User-API-Performance-Test 

## Prerequisite:
- Apache JMeter

## About this project:
In order to determine whether the system could support 120000 users for 12 hours, Load testing and Stress testing were conducted using Apache JMeter. Here, I used the CLI to generate a report. 

## How to run this project:
- Clone this project
  ``` https://github.com/Fammemeem/Random-User-API-Performance-Test ```
- Open the given jmx file in Apache JMeter
- Give following input to run:
   - Goto Thread Group
   - Give Number of threads (user)
   - Give Ramp-Up period (seconds)
   - Goto View Results Tree & click on run button

## CLI Report: 

![screencapture-file-E-apache-jmeter-5-6-2-bin-Random-User-Report-Reports-index-html-2023-12-07-21_44_42](https://github.com/Fammemeem/Random-User-API-Performance-Test/assets/106922643/cab9e198-985f-4037-ac62-5f8d7419dea6)

## Load Test Report

![Load test report](https://github.com/Fammemeem/Random-User-API-Performance-Test/assets/106922643/a95c001f-16ef-46c8-8968-4d2b5189e9bb)

## Stress Test Report

![Stress test report](https://github.com/Fammemeem/Random-User-API-Performance-Test/assets/106922643/8fc3d783-15c2-49d4-b689-a5d818b2afe6)
