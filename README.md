# Lab8-Starter
Ryan Le

## Q. How are graceful degradation and service workers related?
Graceful degradation and service workers are related because service workers allow for graceful degradation. Service workers let you gracefully handle failures, and not have it be a single point of collapse, making degradation graceful. It provides a fallback for when network goes down or a server fails, and the service worker intercepts the failed request and returns the cached results that were loaded earlier instead of crashing. 

https://ryanqgle.github.io/Lab8_Starter/

![pwa](pwa.png)