## Flipcart 

### References
- [slideshare - Lessons Learnt Building India's E-Commerce Supply Chain in Ruby, by Yogi Kulkarni](http://www.slideshare.net/yogi/lessons-learnt-building-indias-largest-e-commerce-supply-chain-in-ruby) 
- [video](http://confreaks.tv/videos/gardencityruby2014-lessons-learnt-building-india-s-e-commerce-supply-chain-in-ruby)
 
### Case Study 
Flipkart, is an E-Commerce company
> In 2012 Flipkart's supply chain system was re-built as a service oriented architecture with Ruby at its core. This talk will cover our experiences designing, building and scaling a mission-critical Ruby-based system where data integrity and performance is vital. Dealing with cross-service transaction integrity JRuby - the good, bad & ugly Coordinating gem upgrades across multiple services Performance tuning to get predictable response times - taming queries, external calls, GC, locks Monitoring & profiling production systems Ruby app servers: Trinidad vs Passenger vs Unicorn Challenges in ramping up teams on Ruby etc

Performance is not a language issue. It's architecture issue.
Why Ruby? The idea is the speed of development

Dev mainly done in (MRI)Ruby, but when it required to use we started JRuby.
AtiveRecords, the connection pool is not the threadsafe
Moved back to CRuby from JRuby


[Githut](https://github.com/flipkart)
![Architecture](images/flipcart/architecture.jpg?raw=true)


