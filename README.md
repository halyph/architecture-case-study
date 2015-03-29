# Ruby on Rails Architecture Case Studies

## List of case stadies
- Groupon
- SoundCloud
- Gilt

[Wanelo](wanelo.md)

## References

### Wanelo

- [Enterprise Architectures with Ruby (and Rails) (Konstantin Gredeskoul, CTO at Wanelo)](http://www.slideshare.net/kigster/enterprise-architectures-with-ruby-and-rails%20)

### Groupon

- [Groupon Architecture](https://engineering.groupon.com/2013/misc/i-tier-dismantling-the-monoliths/) We recently completed a year-long project to migrate Groupon’s U.S. web traffic from a monolithic Ruby on Rails application to a new Node.js stack with substantial results.

### SoundCloud

  - [Evolution of SoundCloud’s Architecture](https://developers.soundcloud.com/blog/evolution-of-soundclouds-architecture) This is a story of how we adapted our architecture over time to accomodate growth. Scaling is a luxury problem and surprisingly has more to do with organization than implementation. For each change we addressed the next order of magnitude of users we needed to support, starting in the thousands and now we’re designing for the hundreds of millions.  We identify our bottlenecks and addressed them as simply as possible by introducing clear integration points in our infrastructure to divide and conquer each problem individually.
  - [From a monolithic Ruby on Rails app to the JVM](http://www.slideshare.net/pcalcado/from-a-monolithic-ruby-on-rails-app-to-the-jvm)
  - [Building Products at SoundCloud - Part I: Dealing with the Monolith](https://developers.soundcloud.com/blog/building-products-at-soundcloud-part-1-dealing-with-the-monolith)
  - [Building Products at SoundCloud - Part II: Breaking the Monolith](https://developers.soundcloud.com/blog/building-products-at-soundcloud-part-2-breaking-the-monolith)
  - [Building Products at SoundCloud - Part III: Microservices in Scala and Finagle](https://developers.soundcloud.com/blog/building-products-at-soundcloud-part-3-microservices-in-scala-and-finagle)

### Gilt

- [Scaling Gilt: from Monolithic Ruby Application to Distributed Scala Micro-Services Architecture](http://www.slideshare.net/InfoQ/scaling-gilt-from-monolithic-ruby-application-to-distributed-scala-microservices-architecture) and here is [Gilt Case stady from Typesafe](http://downloads.typesafe.com/website/casestudies/Gilt-Live-Case-Study-v1.3.pdf)
  - [Interview With Eric Bowman of Gilt.com](http://code.tutsplus.com/articles/interview-with-eric-bowman-of-giltcom--net-35653)
  - [How Gilt's Insane Traffic Spikes Pushed It Off Rails To Scala](http://readwrite.com/2014/05/08/gilt-eric-bowman-interview-scala-rails-jvm-reactive-platform)

Performance is not a language issue. It's architecture issue.
Why Ruby? The idea is the speed of development

### Flipcart 
Flipkart, is an E-Commerce company
In 2012 Flipkart's supply chain system was re-built as a service oriented architecture with Ruby at its core. This talk will cover our experiences designing, building and scaling a mission-critical Ruby-based system where data integrity and performance is vital. Dealing with cross-service transaction integrity JRuby - the good, bad & ugly Coordinating gem upgrades across multiple services Performance tuning to get predictable response times - taming queries, external calls, GC, locks Monitoring & profiling production systems Ruby app servers: Trinidad vs Passenger vs Unicorn Challenges in ramping up teams on Ruby etc

[Githut](https://github.com/flipkart)
![Architecture](images/flipcart/architecture.jpg?raw=true)

- [Lessons Learnt Building India's E-Commerce Supply Chain in Ruby, by Yogi Kulkarni](http://www.slideshare.net/yogi/lessons-learnt-building-indias-largest-e-commerce-supply-chain-in-ruby) and [video](http://confreaks.tv/videos/gardencityruby2014-lessons-learnt-building-india-s-e-commerce-supply-chain-in-ruby)

### Others
- [Quora - Does Ruby on Rails scale?](http://www.quora.com/Does-Ruby-on-Rails-scale) ask long time ago - 2013
- YellowPages
- [Book - Enterprise Rails](http://dan.chak.org/enterprise-rails)
- [Phusion Passenger Design and Architecture](https://www.phusionpassenger.com/documentation/Design%20and%20Architecture.html)
- [Deployment with Ruby on Rails](http://www.slideshare.net/jweiss/deployment-with-ruby-on-rails)
- [Deploying And Monitoring Rails](http://www.slideshare.net/jweiss/deploying-and-monitoring-rails)
- [Why Do They Say Rails Doesn't Scale?](http://codefol.io/posts/why-do-they-say-rails-doesnt-scale)
