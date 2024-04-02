# Usage statistics

A component which reports on usage of resources. Generally 2 approaches for usage monitoring are available:

- embed a javascript snippet which triggers a count to a stats software at page load
- analyse access (and error) logs of the infrastructure

Note that option one only counts website visits, calls to API's are not included.

Typical tools for either solution are:

Javascript include
- [Google Analytics](https://marketingplatform.google.com/about/analytics/)
- [Matomo](https://matomo.org/)

Access log analyses
- [Elastic logstash](https://www.elastic.co/logstash)
- [Splunk](https://www.splunk.com/)
- [AWStats](https://awstats.sourceforge.io/)

## Feed back into search ranking

Data acquired through usage analyses can typically be used to improve user experience, popular resources may outrank others.
A feedback loop from the usage statistics component 

## GDPR

Data collected as part of Usage monitoring is typically sensitive in the scope of GDPR. Careful governance is required.

## Soilwise website

Notice that the soilwise website currently uses google analytics
