# Jmeter_Performance_Testing_reqres
Dear, 

I’ve completed performance test on frequently used API for test site https://reqres.in. <br />
Test executed for the below mentioned scenario in server https://reqres.in. 

* 10 Concurrent Request with 10 Loop Count; Avg TPS for Total Samples is ~ 1.333 And Total Concurrent API requested: 80.
* 50 Concurrent Request with 10 Loop Count; Avg TPS for Total Samples is ~ 6.667 And Total Concurrent API requested: 400.
* 100 Concurrent Request with 10 Loop Count; Avg TPS for Total Samples is ~ 13.3 And Total Concurrent API requested: 800.
```diff
- While executed 100 concurrent request, found  1 request got connection timeout and error rate is 0.13%.
```
**Summary:** Server can handle almost concurrent 780 API call with almost zero (0) error rate.
Report Image:
![reqres](https://github.com/Rasujon3/Jmeter_Performance_Testing_reqres/assets/61946723/51d4f51f-c3cb-461f-8f94-a5f03e81a601)
