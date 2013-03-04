Simple Patterns for Scaling Websites: Some lessons learned at Mozilla
=====================================================================

:Speakers:
    Brandon Burton, Chris Turra

:Date:
    2013-02-22

:Presentation:
    http://solarce.github.com/mozilla-scaling-patterns/

Summary
-------

Description of scaling techniques used at Mozilla to deliver Firefox.
Some interesting topics:

+ Zeus load balancer + cache (stingray) used
+ Multi-master MySQL
+ No virtualization in production
+ Async (background) tasks used often
+ AMD Seamicro used for 192 hosts in 45U rack
+ Self service functions

 - Monitoring
 - Log processing with LogStash and Kibana
 - Sentry used to centralize exception reporting (for Django stack)
