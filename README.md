# Fuck Off As A Service

FOAAS (Fuck Off As A Service) provides a modern, RESTful, scalable solution to the common problem of telling people to fuck off.

I only use this API to play with my boyfriend and this API should not be used to bully or harass anyone!!
If you find someone is abusing this API, please tell me and I will shut it down immediately.

Their [official API and documentation server](https://foaas.com/) is down. It seems like their [official github repo](https://github.com/tomdionysus/foaas) is no longer maintained. Updated May 7, 2023: It seems like their server is back!

Therefore I deployed my own server: https://foaas-hoaxd.ondigitalocean.app/ . Click it to see the documentation of all endpoints.

## Random Fuck-off Generator

I added a random fuck-off generator service, with an endpoint of `/random/:name/:from`. 

For example, if you wanna fuck-off your friend called Jack and you are called Jill, send him https://foaas-hoaxd.ondigitalocean.app/random/Jack/Jill .
It will generate different fuck-off message everytime refreshed.

Play with it.

## Contribution

All kinds of contribution is welcomed. Check out the files in the folder `lib` and `spec` and create your own endpoint following their pattern. Create a pull request and I will add ur endpoint in.
