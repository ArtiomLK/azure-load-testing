# Azure Load Testing

## Determine requests per second

The virtual user count is the number of parallel requests that Azure Load Testing performs at a given time.

- Latency
  - Application latency is the total time from sending an application request by the test engine, to receiving the response.
- Virtual Users
  - The virtual user count is the number of parallel requests that Azure Load Testing performs at a given time.
- Request Per Seconds Formula
  - RPS = (# of VUs) * (1/latency in seconds)
  - If application latency is 20 milliseconds (0.02 second), and you're generating a load of 2,000 VUs, you can achieve around 100,000 RPS (2000 * 1/0.02s).

## Additional Resources

- Azure Load Testing
- [MS | Learn | Read data from a CSV file in JMeter with Azure Load Testing Preview][6]
- [MS | Learn | Create configurable load tests with secrets and environment variables][5]
- [MS | Learn | Configure Azure Load Testing Preview for high-scale load][2]
- [MS | Learn | Azure Load Testing pricing][4]
- [Youtube | Betabit | Betatalks #63 - An introduction to Azure Load Testing][3]
- [Youtube | Azure Power Lunch | Azure Load Testing Preview][7]
- Azure Load Testing
- [Youtube | Ashish Thakur | JMeter CSV Data Set Config - JMeter Tutorial (Part 9)][9]
- [Youtube | QAInsights | S1E7 Learn JMeter Series - HTTP Header Manager][8]

[2]: https://learn.microsoft.com/en-us/azure/load-testing/how-to-high-scale-load
[3]: https://www.youtube.com/watch?v=0RfCQf_Uy8s
[4]: https://azure.microsoft.com/en-us/pricing/details/load-testing
[5]: https://learn.microsoft.com/en-us/azure/load-testing/how-to-parameterize-load-tests
[6]: https://learn.microsoft.com/en-us/azure/load-testing/how-to-read-csv-data
[7]: https://www.youtube.com/watch?v=bY6k46Tvzy0
[8]: https://www.youtube.com/watch?v=2zvfnTaMeuM
[9]: https://www.youtube.com/watch?v=1w4BbscBPdg
