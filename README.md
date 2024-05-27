# Lab8-Starter

https://kennethkietvuong.github.io/Lab8-Starter/

## Name(s)
- Kenneth Vuong
- Umar Khan

### How are graceful degradation and service workers related?

Graceful degradation is the practice of accounting for failures in web apps such that the page remains functional even if some components fail. Service workers are files run in the background on a seperate thread and store call requests as well as their respective responses locally, so that if the same call is later made without internet access, the app will still be able to carry out that response offline. Service workers help us implement graceful degradation in our web applicatons by allowing us to account for failed requsts, such as when the user is offline. The service worker can still provide a cached response in the case of network failure to retain functionality of the program.

![pwa.png](pwa.png)