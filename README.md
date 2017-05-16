# JBoss Business Day 2017 - OpenShift in der Praxis
##### Based on Grant Shipleys MLB Parks example (https://github.com/gshipley/openshift3mlbparks)

This is a short demo of OpenShift 3, for the so called <b>Viada JBoss Business Day 2017</b> in Frankfurt.

The demo deals with development and operational issues too.

 If you want to reuse this demo, just follow the instructions explained at the bottom of the page.    
## Agenda
### Build and Deploy an image
  1. Source to Image
    - Explanation
    - MLB Parks Template
    - Logs
    - Influence build process
    - Defining Health Checks
  2. Docker Strategy
    - How to use Docker Images
    - Logs
  3. Deployment Strategies
    - Recreate
    - Rolling

### Failover Scenerios
  1. Pod crashes
  2. Liveness probe fails
  3. Readiness probe fails

### Logging & Debugging
  1. Debug Terminal
  2. Remote Debugging
  3. EFK

### Development Tools
  1. JBoss Tools
  2. oc cluster up
  3. minishift

### Q&A

## How to use this demo
### Build and Deploy an image
1. Source to Image
  - Just use [this][aa426728] presemtation

  [aa426728]: https://github.com/Sifa91/businessDayDemo/blob/master/misc/source-to-image.pdf "Source to Image"
