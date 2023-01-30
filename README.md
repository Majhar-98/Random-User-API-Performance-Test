# Random-User-API-Performance-Test
## Why Choose Apache JMeter for API Testing?

1. Open-source tool - The Apache JMeter is an open-source tool based on Java used to perform load testing and performance testing.
2. Cross-platform testing - Since JMeter is solely Java-based, it can be used on any platform that has a JVM; Windows, Linux, or macOS.
3. Smooth API Testing - API Testing enables easy, smooth, and rapid API testing.

## Load Testing Strategy:
In Load testing, I got actual tps when I hit the .https://random-data-api.com/api/v2/users server with 833 users in 300 second. The actual value is 2.7 which is close to expected value. Afterword, I hit the server with 3333 users in 1200 second then I found exactly 0.98 % error which close to 1 % error.

![load1](https://user-images.githubusercontent.com/123467715/215390403-c55a3f84-91a9-4e94-8100-88e2f11d6db1.jpg)

## Stress Testing Strategy:
When, I hit the system with 20000 users in 18000 second then, I find out the bottleneck/stress test point which is exactly 1% error.

![stress-2](https://user-images.githubusercontent.com/123467715/215391230-b4e91161-12d5-4651-81f4-bd6aa59e8e45.jpg)


## Report: 
Report file is available in github
![Report](https://user-images.githubusercontent.com/123467715/215391288-6019ddfa-13d1-4c84-b507-c9c169105959.jpg)



