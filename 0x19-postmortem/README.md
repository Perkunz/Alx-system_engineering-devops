<style>
h1 {
    font-family: Georgia, 'Times New Roman', Times, serif;
    font-weight: bold;
    background-color: #96aa4d; 
}

</style>

<h1> Server requests failure report </h1>

It was reported by our clients that the platform was returning 500 Error on all requests made on the platform routes, all the services were down. 70% of the users were affected. The root cause was the failure of our master server.

<h1> Timline </h1>

The error was realized on Monday 6th March 0900 hours (West Africa Time) when Mr Sunday noticed how slow the master server was. Our engineers on call disconnected the master server for further system analysis and channelled all requests to client server web-02. They solved the problem by Monday 6th March 2100 hours (West Africa Time).

<h1> Causes and Resolution </h1>

The platform is served by 2 ubuntu cloud servers. The master server  was connected to serve all requests, and it stopped functioning due to memory outage as a result of so many requests

<h1> Prevention </h1>

<ol>
    <li> Choosethe best loadbalancing algorithm for your programs </li>
    <li> Always keep an eye on our servers </li>
    <li> Have a back-up server for emergency </li>
<ol>

