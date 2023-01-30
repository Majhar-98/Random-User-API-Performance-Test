# Random-User-API-Performance-Test
## Purpose of Performance Testing:
Features and Functionality supported by a software system are not the only concern. A software application’s performance, like its response time, reliability, resource usage, and scalability, do matter. The goal of Performance Testing is not to find bugs but to eliminate performance bottlenecks.




## Why Choose Apache JMeter for API Testing?

1. Open-source tool - The Apache JMeter is an open-source tool based on Java used to perform load testing and performance testing.
2. Cross-platform testing - Since JMeter is solely Java-based, it can be used on any platform that has a JVM; Windows, Linux, or macOS.
3. Smooth API Testing - API Testing enables easy, smooth, and rapid API testing.

## Load Testing Strategy:
In Load testing, I got always actual tps when I hit the .https://random-data-api.com/api/v2/users server with multiple users in severl times in every request. The actual value is 2.7 which is close to expected value. I did nit found any error when I hit the system.

![Load-1](https://user-images.githubusercontent.com/123467715/215394853-fedc6abe-2866-4f5c-b141-0dd2284c4738.PNG)
![load1](https://user-images.githubusercontent.com/123467715/215390403-c55a3f84-91a9-4e94-8100-88e2f11d6db1.jpg)

## Stress Testing Strategy:
When, I hit the system with 4200 users in 1200 second then, I find out the bottleneck/stress test point which is exactly 1% error.

![Stress](https://user-images.githubusercontent.com/123467715/215394905-b662a1b5-9680-422a-8948-ac30a1df6c9f.PNG)


## Report: 
Report file is available in github
![Report](https://user-images.githubusercontent.com/123467715/215391288-6019ddfa-13d1-4c84-b507-c9c169105959.jpg)



