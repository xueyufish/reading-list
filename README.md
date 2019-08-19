# Tech Resource

A curated list of tech resrouces.

### Contents

- [Tech Resource](#tech-resource)
    - [Programming Language](#programming-language)
        - [Algorithms](#algorithms)
        - [Java](#java)
        - [Go](#go)
        - [CPP](#cpp)
        - [Rust](#rust)
    - [Operating System](#operating-system)
        - [Linux](#linux)
        - [Memory](#memory)
        - [Network](#network)
        - [I/O](#io)
        - [Lock-Free](#lock-free)
    - [Database](#database)
        - [MySQL](#mysql)
        - [Redis](#redis)
        - [Cassandra](#cassandra)
        - [HBase](#hbase)
        - [Document Database](#document-database)
        - [Time-Series Database](#time-series-database)
    - [Distributed System](#distributed-system)
    - [Arch Design](#arch-design)
        - [API Design Guidelines](#api-design-guidelines)
        - [Search](#search)
        - [Micro Service](#micro-service)
        - [Architecture](#architecture)
    - [Container](#container)
        - [Docker](#docker)
        - [Kubernates](#kubernates)
    - [Block Chain](#block-chain)
        - [Bitcoin](#bitcoin)
        - [Ethereum](#ethereum)
    - [Documentation](#documentation)
    

## Programming Language
*Resrouces for programming language, eg: Java, go.*

### Algorithms
[Data Structure Visualizations](https://www.cs.usfca.edu/~galles/visualization/Algorithms.html)

### Java
[Introduction to java bytecode](https://dzone.com/articles/introduction-to-java-bytecode)

[IBM developerworks Java bytecode](https://www.ibm.com/developerworks/library/it-haggar_bytecode/index.html)

[Spring Boot参考指南](https://qbgbook.gitbooks.io/spring-boot-reference-guide-zh/content/)

[Java Platform, Standard Edition HotSpot Virtual Machine Garbage Collection Tuning Guide](https://docs.oracle.com/javase/8/docs/technotes/guides/vm/gctuning/)

[Using JDK 9 Memory Order Modes](http://gee.cs.oswego.edu/dl/html/j9mm.html)

[JVM Anatomy Park](https://shipilev.net/jvm-anatomy-park/)

[Java Platform, Standard Edition Troubleshooting Guide](https://docs.oracle.com/javase/8/docs/technotes/guides/troubleshoot/)

### Go
[The Go Programming Language Specification](https://golang.org/ref/spec)

[Go By Example](https://gobyexample.com/)

[Go 101](https://go101.org/article/101.html)

[Go Project Layout](https://medium.com/golang-learn/go-project-layout-e5213cdcfaa2)

[Go Standards Project Layout](https://github.com/golang-standards/project-layout)

[Effective Go](https://golang.org/doc/effective_go.html)

[Go Code Review Comments](https://github.com/golang/go/wiki/CodeReviewComments)

[Github: Go Articles](https://github.com/golang/go/wiki/Articles)

[Github: Go Blogs](https://github.com/golang/go/wiki/Blogs)

[Github: Awesome Go](https://github.com/avelino/awesome-go)

### CPP
[cplusplus](https://www.cplusplus.com/)

### Rust

## Operating System
### Linux
[Product Documentation for Red Hat Enterprise Linux](https://access.redhat.com/documentation/en-us/red_hat_enterprise_linux/?version=7)

[linux-insides](https://github.com/0xAX/linux-insides)

[Linux Kernel index](https://lwn.net/Kernel/Index/)

[Linux Kernel Documentation](https://www.kernel.org/doc/)

[Kernal Planet](http://planet.kernel.org/)

[The Linux Kernel](http://tldp.org/LDP/tlk/tlk.html)

[Linux Performance](http://www.brendangregg.com/linuxperf.html)

[Linux Performance and Tuning Guidelines](https://lenovopress.com/redp4285.pdf)

### Memory
[What every programmer should know about memory, Part 1](https://lwn.net/Articles/250967/)

[Memory part 2: CPU caches](https://lwn.net/Articles/252125/)

[Memory part 3: Virtual Memory](https://lwn.net/Articles/253361/)

[Memory part 4: NUMA support](https://lwn.net/Articles/254445/)

[Memory part 5: What programmers can do](https://lwn.net/Articles/255364/)

[Memory part 6: More things programmers can do](https://lwn.net/Articles/256433/)

[Memory part 7: Memory performance tools](https://lwn.net/Articles/257209/)

[Memory part 8: Future technologies](https://lwn.net/Articles/258154/)

[Memory part 9: Appendices and bibliography](https://lwn.net/Articles/258188/)

[Memory Barriers: a Hardware View for Software Hackers](http://irl.cs.ucla.edu/~yingdi/web/paperreading/whymb.2010.06.07c.pdf)

[A Tutorial Introduction to the ARM and POWER Relaxed Memory Models](https://www.cl.cam.ac.uk/~pes20/ppc-supplemental/test7.pdf)

[Optimizing web servers for high throughput and low latency](https://blogs.dropbox.com/tech/2017/09/optimizing-web-servers-for-high-throughput-and-low-latency/)

[x86-TSO: A Rigorous and Usable Programmer’s Model for x86 Multiprocessors](https://www.cl.cam.ac.uk/~pes20/weakmemory/cacm.pdf)

[ptmalloc,tcmalloc和jemalloc内存分配策略研究](https://owent.net/2013/867.html)

[内存优化总结:ptmalloc、tcmalloc和jemalloc](http://www.cnhalo.net/2016/06/13/memory-optimize/)

[Scalable memory allocation using jemalloc](https://www.facebook.com/notes/facebook-engineering/scalable-memory-allocation-using-jemalloc/480222803919)

[Decreasing RAM Usage by 40% Using jemalloc with Python & Celery](https://zapier.com/engineering/celery-python-jemalloc/)

### Network
[Computer Network Design](http://www.site.uottawa.ca/~shervin/courses/ceg4185/lectures/)

[Computer Network Tutorials](https://www.geeksforgeeks.org/computer-network-tutorials/)

[Linux Advanced Routing & Traffic Control HOWTO](http://www.tldp.org/HOWTO/Adv-Routing-HOWTO/)

[Red Hat Enterprise Linux Network Performance Tuning Guide](https://access.redhat.com/sites/default/files/attachments/20150325_network_performance_tuning.pdf)

[Github: Awesome pcaptools](https://github.com/caesar0301/awesome-pcaptools)

[Making Linux TCP Fast](https://netdevconf.org/1.2/papers/bbr-netdev-1.2.new.new.pdf)

[Monitoring and Tuning the Linux Networking Stack: Sending Data](https://blog.packagecloud.io/eng/2017/02/06/monitoring-tuning-linux-networking-stack-sending-data/)

[Monitoring and Tuning the Linux Networking Stack: Receiving Data](https://blog.packagecloud.io/eng/2016/06/22/monitoring-tuning-linux-networking-stack-receiving-data/)

[RFC 826 - An Ethernet Address Resolution Protocol](https://tools.ietf.org/html/rfc826)

[RFC 1853 - IP in IP Tunneling](https://tools.ietf.org/html/rfc1853)

[RFC 2784 - Generic Routing Encapsulation (GRE)](https://tools.ietf.org/html/rfc2784)

[RFC 2661 - Layer Two Tunneling Protocol "L2TP"](https://tools.ietf.org/html/rfc2661)

[RFC 2637 - Point-to-Point Tunneling Protocol (PPTP)](https://tools.ietf.org/html/rfc2637)

[RFC 793 - Transmission Control Protocol](https://tools.ietf.org/html/rfc793)

[RFC 813 - Window and Acknowledgement Strategy in TCP](https://tools.ietf.org/html/rfc813)

[RFC 879 - The TCP Maximum Segment Size and Related Topics](https://tools.ietf.org/html/rfc879)

[RFC 896 - Congestion Control in IP/TCP Internetworks](https://tools.ietf.org/html/rfc896)

[RFC 896 - Congestion Control in IP/TCP Internetworks](https://tools.ietf.org/html/rfc896)

[RFC 5681 - TCP Congestion Control](https://tools.ietf.org/html/rfc5681)

[RFC 5682 - The NewReno Modification to TCP's Fast Recovery Algorithm](https://tools.ietf.org/html/rfc5682)

[RFC 5682 - The NewReno Modification to TCP's Fast Recovery Algorithm](https://tools.ietf.org/html/rfc5682)

[RFC 2018 - TCP Selective Acknowledgment Options](https://tools.ietf.org/html/rfc2018)

[RFC 2883 - An Extension to the Selective Acknowledgement (SACK) Option for TCP](https://tools.ietf.org/html/rfc2883)

[RFC 2998 - Computing TCP's Retransmission Timer](https://tools.ietf.org/html/rfc2998)

[RFC 6298 - Computing TCP's Retransmission Timer](https://tools.ietf.org/html/rfc6298)

[Congestion Avoidance and Control](http://ee.lbl.gov/papers/congavoid.pdf)

[Linux Programmer's Manual: TCP](http://man7.org/linux/man-pages/man7/tcp.7.html)

[RFC 7230 - Hypertext Transfer Protocol (HTTP/1.1): Message Syntax and Routing](https://tools.ietf.org/html/rfc7230)

[RFC 7231 - Hypertext Transfer Protocol (HTTP/1.1): Semantics and Content](https://tools.ietf.org/html/rfc7231)

[RFC 7232 - Hypertext Transfer Protocol (HTTP/1.1): Conditional Requests](https://tools.ietf.org/html/rfc7232)

[RFC 7233 - Hypertext Transfer Protocol (HTTP/1.1): Range Requests](https://tools.ietf.org/html/rfc7233)

[RFC 7234 - Hypertext Transfer Protocol (HTTP/1.1): Caching](https://tools.ietf.org/html/rfc7234)

[RFC 7235 - Hypertext Transfer Protocol (HTTP/1.1): Authentication](https://tools.ietf.org/html/rfc7235)

[Gitbook: HTTP/2 详解](https://legacy.gitbook.com/book/ye11ow/http2-explained/details)

[HTTP/2 for a Faster Web](https://cascadingmedia.com/insites/2015/03/http-2.html)

[HTTP/2 for Web Application Developers](https://www.nginx.com/wp-content/uploads/2015/09/NGINX_HTTP2_White_Paper_v4.pdf)

[Hypertext Transfer Protocol Version 2 (HTTP/2)](https://httpwg.org/specs/rfc7540.html)

[HPACK: Header Compression for HTTP/2](https://httpwg.org/specs/rfc7541.html)

[The TCP/IP Guide](http://www.tcpipguide.com/free/index.htm)

### I/O
[C10k problem](https://en.wikipedia.org/wiki/C10k_problem)

[Thousands of Threads and Blocking I/O](https://www.slideshare.net/e456/tyma-paulmultithreaded1)

[Scalable IO in Java](http://gee.cs.oswego.edu/dl/cpjslides/nio.pdf)

[Boost application performance using asynchronous I/O](https://www.ibm.com/developerworks/library/l-async/)

[Lazy Asynchronous I/O For Event-Driven Servers](https://www.usenix.org/legacy/event/usenix04/tech/general/full_papers/elmeleegy/elmeleegy_html/html.html)

[I/O Completion Ports](https://docs.microsoft.com/en-us/windows/desktop/FileIO/i-o-completion-ports)

[I/O Processing](https://flylib.com/books/en/4.491.1.85/1/)

[Inside I/O Completion Ports](http://sysinternals.d4rk4.ru/Information/IoCompletionPorts.html)

[libevent 2.0 book](http://www.wangafu.net/~nickm/libevent-book/)

[Libevent深入浅出](https://aceld.gitbooks.io/libevent/content/)

[Libuv Design Overview](http://docs.libuv.org/en/v1.x/design.html)

[Understanding Reactor Pattern: Thread-Based and Event-Driven](https://dzone.com/articles/understanding-reactor-pattern-thread-based-and-eve)

[The reactor pattern and non blocking IO](https://www.celum.com/en/blog/technology/the-reactor-pattern-and-non-blocking-io)

[Reactor: An Object Behavioral Pattern for Demultiplexing and Dispatching Handles for Synchronous Events](https://www.cse.wustl.edu/~schmidt/PDF/reactor-siemens.pdf)

[The Secret To 10 Million Concurrent Connections -The Kernel Is The Problem, Not The Solution](http://highscalability.com/blog/2013/5/13/the-secret-to-10-million-concurrent-connections-the-kernel-i.html)

[Select is fundamentally broken](https://idea.popcount.org/2017-01-06-select-is-fundamentally-broken/)

[Epoll is fundamentally broken 1/2](https://idea.popcount.org/2017-02-20-epoll-is-fundamentally-broken-12/)

[Epoll is fundamentally broken 2/2](https://idea.popcount.org/2017-03-20-epoll-is-fundamentally-broken-22/)

### Lock-Free
[Dr.Dobb: Lock-Free Data Structures](http://www.drdobbs.com/lock-free-data-structures/184401865)

[Andrei Alexandrescu: Lock-Free Data Structures](https://erdani.com/publications/cuj-2004-10.pdf)

[Is Parallel Programming Hard, And, If So, What Can You Do About It?](https://mirrors.edge.kernel.org/pub/linux/kernel/people/paulmck/perfbook/perfbook.html)

[Wiki: Non-blocking algorithm](https://en.wikipedia.org/wiki/Non-blocking_algorithm)

[Wiki: Read-copy-update](https://en.wikipedia.org/wiki/Read-copy-update)

[Wiki: Seqlock](https://en.wikipedia.org/wiki/Seqlock)

[Implementing Lock-Free Queues](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.53.8674&rep=rep1&type=pdf)

[All about 64-bit programming in one place](https://software.intel.com/en-us/blogs/2011/07/07/all-about-64-bit-programming-in-one-place/)

[What Scalable Programs Need from Transactional Memory](https://dl.acm.org/citation.cfm?id=3037750)

[Improving OpenSSL Performance](https://software.intel.com/en-us/articles/improving-openssl-performance)

[How eBay's Shopping Cart used compression techniques to solve network I/O bottlenecks](https://www.ebayinc.com/stories/blogs/tech/how-ebays-shopping-cart-used-compression-techniques-to-solve-network-io-bottlenecks/)

[Boosting Site Speed Using Brotli Compression](https://engineering.linkedin.com/blog/2017/05/boosting-site-speed-using-brotli-compression)

[Performance Testing with SSDs, Part 1](https://devs.mailchimp.com/blog/performance-testing-with-ssds-part-1/)

[Performance Testing with SSDs, Part 2](https://devs.mailchimp.com/blog/performance-testing-with-ssds-pt-2/)

[Secure Programming HOWTO - Creating Secure Software](https://www.dwheeler.com/secure-programs/)

[Hints for Computer System Design](https://www.microsoft.com/en-us/research/wp-content/uploads/2016/02/acrobat-17.pdf)

[The Five-Minute Rule Ten Years Later, and Other Computer Storage Rules of Thumb](http://jimgray.azurewebsites.net/5_min_rule_sigmod.pdf)

[The Five-Minute Rule 20 Years Later](https://cacm.acm.org/magazines/2009/7/32091-the-five-minute-rule-20-years-later/fulltext)

## Database
[Some study on database storage internals](https://medium.com/@kousiknath/data-structures-database-storage-internals-1f5ed3619d430)

[Tracking the Money — Scaling Financial Reporting at Airbnb](https://medium.com/airbnb-engineering/tracking-the-money-scaling-financial-reporting-at-airbnb-6d742b80f040)

[Mitigating replication lag and reducing read load with freno](https://githubengineering.com/mitigating-replication-lag-and-reducing-read-load-with-freno/)

[Why you don’t want to shard](https://www.percona.com/blog/2009/08/06/why-you-dont-want-to-shard/)

[How to Scale Big Data Applications](https://www.percona.com/sites/default/files/presentations/How%20to%20Scale%20Big%20Data%20Applications.pdf)

[Using Shards to Accommodate Millions of Users](https://devs.mailchimp.com/blog/using-shards-to-accommodate-millions-of-users/)

[Code Migration in Production: Rewriting the Sharding Layer of Uber’s Schemaless Datastore](https://eng.uber.com/schemaless-rewrite/)

[Sharding & IDs at Instagram](https://instagram-engineering.com/sharding-ids-at-instagram-1cf5a71e5a5c)

[How We Partitioned Airbnb’s Main Database in Two Weeks](https://medium.com/airbnb-engineering/how-we-partitioned-airbnb-s-main-database-in-two-weeks-55f7e006ff21)

[NoSQL Databases: a Survey and Decision Guidance](https://medium.baqend.com/nosql-databases-a-survey-and-decision-guidance-ea7823a822d)

[Distribution, Data, Deployment: Software Architecture Convergence in Big Data Systems](https://resources.sei.cmu.edu/asset_files/WhitePaper/2014_019_001_90915.pdf)

[No Relation: The Mixed Blessings of Non-Relational Databases](http://ianvarley.com/UT/MR/Varley_MastersReport_Full_2009-08-07.pdf)

[Visual Guide to NoSQL Systems](http://blog.nahurst.com/visual-guide-to-nosql-systems)

[SQL vs. NoSQL Databases: What’s the Difference?](https://www.upwork.com/hiring/data/sql-vs-nosql-databases-whats-the-difference/)

[SQL or NoSQL](https://engineering.salesforce.com/sql-or-nosql-9eaf1d92545b)

[Large-scale Incremental Processing
Using Distributed Transactions and Notifications](https://www.usenix.org/legacy/event/osdi10/tech/full_papers/Peng.pdf)

### MySQL
[MySQL Documentation](https://dev.mysql.com/doc/)

[MySQL Internals Manual](https://dev.mysql.com/doc/internals/en/)

[MySQL索引背后的数据结构及算法原理](http://blog.codinglabs.org/articles/theory-of-mysql-index.html)

[Sharding Pinterest: How we scaled our MySQL fleet](https://medium.com/@Pinterest_Engineering/sharding-pinterest-how-we-scaled-our-mysql-fleet-3f341e96ca6f)

[Choosing MySQL High Availability Solutions](https://dzone.com/articles/choosing-mysql-high-availability-solutions)

[High availability with MariaDB TX](https://mariadb.com/sites/default/files/content/Whitepaper_High_availability_with_MariaDB-TX.pdf)

[BOOKING.COM: EVOLUTION OF MYSQL SYSTEM DESIGN](https://www.percona.com/live/mysql-conference-2015/sessions/bookingcom-evolution-mysql-system-design)

[Why Uber Engineering Switched from Postgres to MySQL](https://eng.uber.com/mysql-migration/)

[MONITORING DELAYED REPLICATION, WITH A FOCUS ON MYSQL](https://engineering.imvu.com/2013/01/09/monitoring-delayed-replication-with-a-focus-on-mysql/)

[Better Parallel Replication for MySQL](https://medium.com/booking-com-infrastructure/better-parallel-replication-for-mysql-14e2d7857813)

[Evaluating MySQL Parallel Replication Part 2: Slave Group Commit](https://medium.com/booking-com-infrastructure/evaluating-mysql-parallel-replication-part-2-slave-group-commit-459026a141d2)

[Evaluating MySQL Parallel Replication Part 3: Benchmarks in Production](https://medium.com/booking-com-infrastructure/evaluating-mysql-parallel-replication-part-3-benchmarks-in-production-db5811058d74)

[Evaluating MySQL Parallel Replication Part 4: More Benchmarks in Production](https://medium.com/booking-com-infrastructure/evaluating-mysql-parallel-replication-part-4-more-benchmarks-in-production-49ee255043ab)

[Evaluating MySQL Parallel Replication Part 4, Annex: Under the Hood](https://medium.com/booking-com-infrastructure/evaluating-mysql-parallel-replication-part-4-annex-under-the-hood-eb456cf8b2fb)

[MySQL Sharding with ProxySQL](https://www.percona.com/blog/2016/08/30/mysql-sharding-with-proxysql/)

### Redis
[Distributed locks with Redis](https://redis.io/topics/distlock)

[How Twitter Uses Redis To Scale - 105TB RAM, 39MM QPS, 10,000+ Instances](http://highscalability.com/blog/2014/9/8/how-twitter-uses-redis-to-scale-105tb-ram-39mm-qps-10000-ins.html)

[Learn Redis the hard way (in production)](https://tech.trivago.com/2017/01/25/learn-redis-the-hard-way-in-production/)

[Moving persistent data out of Redis](https://githubengineering.com/moving-persistent-data-out-of-redis/)

[Scaling Slack’s Job Queue](https://slack.engineering/scaling-slacks-job-queue-687222e9d100)

[Optimising session key storage in Redis](https://deliveroo.engineering/2016/10/07/optimising-session-key-storage.html)

[Optimising Redis storage, part two](https://deliveroo.engineering/2017/01/19/optimising-membership-queries.html)

[Storing hundreds of millions of simple key-value pairs in Redis](https://instagram-engineering.com/storing-hundreds-of-millions-of-simple-key-value-pairs-in-redis-1091ae80f74c)

[GitHub: Awesome Redis](https://github.com/JamzyWang/awesome-redis)

[Redis分布式锁](http://www.redis.cn/topics/distlock.html)

### Cassandra
[Avoid pitfalls in scaling your Cassandra cluster: lessons and remedies](https://medium.com/walmartlabs/avoid-pitfalls-in-scaling-your-cassandra-cluster-lessons-and-remedies-a71ca01f8c04)

[Building Object Store — Storing Images in Cassandra at Walmart Scale](https://medium.com/walmartlabs/building-object-store-storing-images-in-cassandra-walmart-scale-a6b9c02af593)

[How We Scaled Our Ad Analytics with Apache Cassandra](https://engineeringblog.yelp.com/2016/08/how-we-scaled-our-ad-analytics-with-cassandra.html)

[Cassandra at Instagram 2016](https://www.slideshare.net/DataStax/cassandra-at-instagram-2016)

[Benchmarking Cassandra Scalability on AWS — Over a million writes per second](https://medium.com/netflix-techblog/benchmarking-cassandra-scalability-on-aws-over-a-million-writes-per-second-39f45f066c9e)

[How Discord Stores Billions of Messages](https://blog.discordapp.com/how-discord-stores-billions-of-messages-7fa6ec7ee4c7)

[Cassandra - A Decentralized Structured Storage System](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.161.6751&rep=rep1&type=pdf)

### HBase
[Imgur Notifications: From MySQL to HBase](https://medium.com/imgur-engineering/imgur-notifications-from-mysql-to-hbase-9dba6fc44183)

[Improving HBase backup efficiency at Pinterest](https://medium.com/@Pinterest_Engineering/improving-hbase-backup-efficiency-at-pinterest-86159da4b954)

[HBase File Locality in HDFS](http://www.larsgeorge.com/2010/05/hbase-file-locality-in-hdfs.html)

[Storage Infrastructure Behind Facebook Messages Using HBase at Scale](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.294.8459&rep=rep1&type=pdf)

[Awesome HBase](https://github.com/rayokota/awesome-hbase)

### Document Database
[Data Points - What the Heck Are Document Databases?](https://msdn.microsoft.com/en-us/magazine/hh547103.aspx)

[eBay: Building Mission-Critical Multi-Data Center Applications with MongoDB](https://www.mongodb.com/blog/post/ebay-building-mission-critical-multi-data-center-applications-with-mongodb)

[The AWS and MongoDB Infrastructure of Parse: Lessons Learned](https://medium.baqend.com/parse-is-gone-a-few-secrets-about-their-infrastructure-91b3ab2fcf71)

[Migrating Mountains of Mongo Data](https://medium.com/build-addepar/migrating-mountains-of-mongo-data-63e530539952)

[Couchbase Ecosystem at LinkedIn](https://engineering.linkedin.com/blog/2017/12/couchbase-ecosystem-at-linkedin)

[SimpleDB at Zendesk](https://medium.com/zendesk-engineering/resurrecting-amazon-simpledb-9404034ec506)

[Github: Awesome MongoDB](https://github.com/ramnes/awesome-mongodb)

### Time-Series Database
[Introducing Atlas: Netflix’s Primary Telemetry Platform](https://medium.com/netflix-techblog/introducing-atlas-netflixs-primary-telemetry-platform-bd31f4d8ed9a)

[What is Time-Series Data & Why We Need a Time-Series Database](https://blog.timescale.com/what-the-heck-is-time-series-data-and-why-do-i-need-a-time-series-database-dcf3b1b18563)

[Time Series Data: Why and How to Use a Relational Database instead of NoSQL](https://blog.timescale.com/time-series-data-why-and-how-to-use-a-relational-database-instead-of-nosql-d0cd6975e87c)

[Beringei: High-performance Time Series Storage Engine @Facebook](https://code.facebook.com/posts/952820474848503/beringei-a-high-performance-time-series-storage-engine/)

[Building a Scalable Time Series Database on PostgreSQL](https://blog.timescale.com/when-boring-is-awesome-building-a-scalable-time-series-database-on-postgresql-2900ea453ee2)

[Scaling Time Series Data Storage - Part I @Netflix](https://medium.com/netflix-techblog/scaling-time-series-data-storage-part-i-ec2b6d44ba39)

[Design of a Cost Efficient Time Series Store for Big Data](https://medium.com/@leventov/design-of-a-cost-efficient-time-series-store-for-big-data-88c5dc41af8e)

[GitHub: Awesome Time-Series Database](https://github.com/xephonhq/awesome-time-series-database)

### Distributed System
[Fallacies of Distributed Computing Explained](https://www.rgoarchitects.com/Files/fallacies.pdf)

[Distributed systems theory for the distributed systems engineer](https://www.the-paper-trail.org/post/2014-08-09-distributed-systems-theory-for-the-distributed-systems-engineer/)

[Distributed systems for fun and profit](http://book.mixu.net/distsys/)

[Scalable Web Architecture and Distributed Systems](http://nettee.github.io/posts/2016/Scalable-Web-Architecture-and-Distributed-Systems/)

[Distributed Systems Principles and Paradigms](http://barbie.uta.edu/~jli/Resources/MapReduce&Hadoop/Distributed%20Systems%20Principles%20and%20Paradigms.pdf)

[Principles of Distributed Computing](https://disco.ethz.ch/courses/podc_allstars/lecture/podc.pdf)

[Making reliable distributed systems in the presence of software errors](http://erlang.org/download/armstrong_thesis_2003.pdf)

[Scalability, Availability & Stability Patterns](https://www.slideshare.net/jboner/scalability-availability-stability-patterns)

[An introduction to distributed systems](https://github.com/aphyr/distsys-class)

[Byzantine fault tolerance](https://en.wikipedia.org/wiki/Byzantine_fault_tolerance)

[The CAP theorem](https://en.wikipedia.org/wiki/CAP_theorem)

[A Brief Tour of FLP Impossibility](http://www.the-paper-trail.org/post/2008-08-13-a-brief-tour-of-flp-impossibility/)

[Las Vegas algorithm](https://en.wikipedia.org/wiki/Las_Vegas_algorithm)

[Consensus in the Presence of Partial Synchrony](http://groups.csail.mit.edu/tds/papers/Lynch/jacm88.pdf)

[Fallacies of distributed computing](https://en.wikipedia.org/wiki/Fallacies_of_distributed_computing)

[Eight Fallacies of Distributed Computing](https://blog.fogcreek.com/eight-fallacies-of-distributed-computing-tech-talk/)

[Fallacies of Distributed Computing Explained](http://www.rgoarchitects.com/Files/fallacies.pdf)

[CAP Twelve Years Later: How the "Rules" Have Changed](http://www.infoq.com/cn/articles/cap-twelve-years-later-how-the-rules-have-changed)

[Harvest, Yield, and Scalable Tolerant Systems](http://www.rgoarchitects.com/Files/fallacies.pdf)

[Base: An Acid Alternative](http://www.cnblogs.com/savorboard/p/base-an-acid-alternative.html)

[Eventually Consistent - Revisited](https://www.allthingsdistributed.com/2008/12/eventually_consistent.html)

[Impossibility of Distributed Consensus with One Faulty Process](https://groups.csail.mit.edu/tds/papers/Lynch/jacm85.pdf)

[Dapper，大规模分布式系统的跟踪系统](http://bigbully.github.io/Dapper-translation/)

[An introduction to distributed systems](https://github.com/aphyr/distsys-class)

[Amazon Aurora: Design Considerations for High Throughput Cloud-Native Relational Databases](https://www.allthingsdistributed.com/files/p1041-verbitski.pdf)

[Dynamo: Amazon’s Highly Available Key-value Store](https://www.allthingsdistributed.com/files/amazon-dynamo-sosp2007.pdf)

[The Chubby lock service for loosely-coupled distributed systems](https://static.googleusercontent.com/media/research.google.com/en//archive/chubby-osdi06.pdf)

[The Google File System](https://static.googleusercontent.com/media/research.google.com/en//archive/gfs-sosp2003.pdf)

[Bigtable: A Distributed Storage System for Structured Data](https://static.googleusercontent.com/media/research.google.com/en//archive/bigtable-osdi06.pdf)

[MapReduce: Simplified Data Processing on Large Clusters](https://static.googleusercontent.com/media/research.google.com/en//archive/mapreduce-osdi04.pdf)

[Paxos Made Live - An Engineering Perspective](https://static.googleusercontent.com/media/research.google.com/en//archive/paxos_made_live.pdf)

[NEAT ALGORITHMS - PAXOS](http://harry.me/blog/2014/12/27/neat-algorithms-paxos/)

[Paxos By Example](https://angus.nyc/2012/paxos-by-example/)

[Paxos made code - Implementing a high throughput Atomic Broadcast](http://www.inf.usi.ch/faculty/pedone/MScThesis/marco.pdf)

[Paxos for System Builders](http://www.cnds.jhu.edu/pub/papers/cnds-2008-2.pdf)

[Paxos Made Practica](https://web.stanford.edu/class/cs340v/papers/paxos.pdf)

[Paxos Made Moderately Complex](http://www.cs.cornell.edu/courses/cs7412/2011sp/paxos.pdf)

[Zab: High-performance broadcast for primary-backup systems](https://www.semanticscholar.org/paper/Zab%3A-High-performance-broadcast-for-primary-backup-Junqueira-Reed/b02c6b00bd5dbdbd951fddb00b906c82fa80f0b3)

[ZooKeeper’s atomic broadcast protocol: Theory and practice](http://www.tcs.hut.fi/Studies/T-79.5001/reports/2012-deSouzaMedeiros.pdf)

[Raft Understandable Distributed Consensus](http://thesecretlivesofdata.com/raft/)

[The Raft Consensus Algorithm](https://raft.github.io/)

[Raft Distributed Consensus Algorithm Visualization](http://kanaka.github.io/raft.js/)

[In Search of an Understandable Consensus Algorithm](https://raft.github.io/raft.pdf)

[Why Vector Clocks are Easy](http://basho.com/posts/technical/why-vector-clocks-are-easy/)

[Why Vector Clocks Are Hard](http://basho.com/posts/technical/why-vector-clocks-are-hard/)

[Efficient Reconciliation and Flow Control for Anti-Entropy Protocols](https://www.cs.cornell.edu/home/rvr/papers/flowgossip.pdf)

[Gossip visualization](https://rrmoelker.github.io/gossip-visualization/)

[Spanner: Becoming a SQL System](https://static.googleusercontent.com/media/research.google.com/zh-CN//pubs/archive/46103.pdf)

[The Log-Structured Merge-Tree](https://www.cs.umb.edu/~poneil/lsmtree.pdf)

[日志结构的合并树 The Log-Structured Merge-Tree](http://www.cnblogs.com/siegfang/archive/2013/01/12/lsm-tree.html)

[Tango: Distributed Data Structures over a Shared Log](https://www.microsoft.com/en-us/research/wp-content/uploads/2013/11/Tango.pdf)

[The Unified Logging Infrastructure for Data Analytics at Twitter](http://vldb.org/pvldb/vol5/p1771_georgelee_vldb2012.pdf)

[Scaling Big Data Mining Infrastructure: The Twitter Experience](http://www.datascienceassn.org/sites/default/files/Scaling%20Big%20Data%20Mining%20Infrastructure%20-%20The%20Twitter%20Experience.pdf)

[Resilient Distributed Datasets: A Fault-Tolerant Abstraction for In-Memory Cluster Computing](https://www.usenix.org/system/files/conference/nsdi12/nsdi12-final138.pdf)

[Logic and Lattices for Distributed Programming](http://db.cs.berkeley.edu/papers/UCB-lattice-tr.pdf)

[PSYNC: A partially synchronous language for fault-tolerant distributed algorithms](https://www.di.ens.fr/~cezarad/popl16.pdf)

[Dremel: Interactive Analysis of Web-Scale Datasets](http://static.googleusercontent.com/media/research.google.com/en/us/pubs/archive/36632.pdf)

[The Twelve-Factor App](https://12factor.net/zh_cn/)

[On Designing and Deploying Internet-Scale Services](https://www.usenix.org/legacy/event/lisa07/tech/full_papers/hamilton/hamilton_html/index.html)

[4 Things to Keep in Mind When Building a Platform for the Enterprise](https://blog.box.com/blog/4-things-to-keep-in-mind-when-building-a-platform-for-the-enterprise/)

[Notes on Distributed Systems for Young Bloods](https://www.somethingsimilar.com/2013/01/14/notes-on-distributed-systems-for-young-bloods/)

[Designing For Resiliency](http://highscalability.com/blog/2012/12/31/designing-for-resiliency-will-be-so-2013.html)

[Ten design principles for Azure applications](https://docs.microsoft.com/en-us/azure/architecture/guide/design-principles/)

[Writing Code that Scales](https://blog.rackspace.com/writing-code-that-scales)

[Cloud Design Patterns](https://docs.microsoft.com/en-us/azure/architecture/patterns/)

[Automate and abstract: Lessons from Facebook on engineering for scale](https://architecht.io/lessons-from-facebook-on-engineering-for-scale-f5716f0afc7a)

[AWS Cloud Pattern](http://en.clouddesignpattern.org/index.php/Main_Page)

[Design patterns for container-based distributed systems](https://static.googleusercontent.com/media/research.google.com/zh-CN//pubs/archive/45406.pdf)

[A pattern language for microservices](https://microservices.io/patterns/index.html)

[FIT: Failure Injection Testing](https://medium.com/netflix-techblog/fit-failure-injection-testing-35d8e2a9bb2)

[Automated Failure Testing](https://medium.com/netflix-techblog/automated-failure-testing-86c1b8bc841f)

[Automating Failure Testing Research at Internet Scale](https://people.ucsc.edu/~palvaro/socc16.pdf)

[4 Architecture Issues When Scaling Web Applications](http://highscalability.com/blog/2014/5/12/4-architecture-issues-when-scaling-web-applications-bottlene.html)

[Scaling Stateful Objects](http://ithare.com/scaling-stateful-objects/)

[Scaling Up vs. Scaling Out: Hidden Costs](https://blog.codinghorror.com/scaling-up-vs-scaling-out-hidden-costs/)

[Best Practices For Horizontal Application Scaling](https://blog.openshift.com/best-practices-for-horizontal-application-scaling/)

[Scalability Worst Practices](https://www.infoq.com/articles/scalability-worst-practices)

[Reddit: Lessons Learned From Mistakes Made Scaling To 1 Billion Pageviews A Month](http://highscalability.com/blog/2013/8/26/reddit-lessons-learned-from-mistakes-made-scaling-to-1-billi.html)

[Auto scaling Pinterest](https://medium.com/@Pinterest_Engineering/auto-scaling-pinterest-df1d2beb4d64)

[Autoscaling based on request queuing](https://medium.com/square-corner-blog/autoscaling-based-on-request-queuing-c4c0f57f860f)

[Autoscaling applications @ PayPal](https://www.paypal-engineering.com/2017/08/16/autoscaling-applications-paypal/)

[Scryer: Netflix’s Predictive Auto Scaling Engine](https://medium.com/netflix-techblog/scryer-netflixs-predictive-auto-scaling-engine-a3f8fc922270)

[Your Definite Guide For Autoscaling Jenkins](https://tech.trivago.com/2017/02/17/your-definite-guide-for-autoscaling-jenkins/)

[Consistent Hashing](http://www.tom-e-white.com/2007/11/consistent-hashing.html)

[Consistent Hashing: Algorithmic Tradeoffs](https://medium.com/@dgryski/consistent-hashing-algorithmic-tradeoffs-ef6b8e2fcae8)

[Distributing Content to Open Connect](https://medium.com/netflix-techblog/distributing-content-to-open-connect-3e3e391d4dc9)

[Consistent Hashing in Cassandra](https://blog.imaginea.com/consistent-hashing-in-cassandra/)

[Life Beyond Distributed Transactions](https://queue.acm.org/detail.cfm?id=3025012)

[How Sharding Works](https://medium.com/@jeeyoungk/how-sharding-works-b4dec46b3f6)

[Why you don’t want to shard](https://www.percona.com/blog/2009/08/06/why-you-dont-want-to-shard/)

[How to Scale Big Data Applications](https://www.percona.com/sites/default/files/presentations/How%20to%20Scale%20Big%20Data%20Applications.pdf)

[MySQL Sharding with ProxySQL](https://www.percona.com/blog/2016/08/30/mysql-sharding-with-proxysql/)

[Design Of A Modern Cache](http://highscalability.com/blog/2016/1/25/design-of-a-modern-cache.html)

[Caching for a Global Netflix](https://medium.com/netflix-techblog/caching-for-a-global-netflix-7bcc457012f1)

[An analysis of Facebook photo caching](https://code.fb.com/web/an-analysis-of-facebook-photo-caching/)

[How trivago Reduced Memcached Memory Usage by 50%](https://tech.trivago.com/2017/12/19/how-trivago-reduced-memcached-memory-usage-by-50/)

[Caching Internal Service Calls at Yelp](https://engineeringblog.yelp.com/2018/03/caching-internal-service-calls-at-yelp.html)

[Understanding When to use RabbitMQ or Apache Kafka](https://content.pivotal.io/blog/understanding-when-to-use-rabbitmq-or-apache-kafka)

[Why We Chose Kafka For The Trello Socket Architecture](https://tech.trello.com/why-we-chose-kafka/)

[Running Kafka At Scale](https://engineering.linkedin.com/kafka/running-kafka-scale)

[Billions of Messages a Day - Yelp's Real-time Data Pipeline](https://engineeringblog.yelp.com/2016/07/billions-of-messages-a-day-yelps-real-time-data-pipeline.html)

[Should You Put Several Event Types in the Same Kafka Topic?](https://www.confluent.io/blog/put-several-event-types-kafka-topic/)

[Building Reliable Reprocessing and Dead Letter Queues with Kafka](https://eng.uber.com/reliable-reprocessing/)

[Introducing Chaperone: How Uber Engineering Audits Kafka End-to-End](https://eng.uber.com/chaperone/)

[Publishing with Apache Kafka at The New York Times](https://open.nytimes.com/publishing-with-apache-kafka-at-the-new-york-times-7f0e3b7d2077)

[Kafka Streams on Heroku](https://blog.heroku.com/kafka-streams-on-heroku)

[How Apache Kafka Inspired Our Platform Events Architecture](https://engineering.salesforce.com/how-apache-kafka-inspired-our-platform-events-architecture-2f351fe4cf63)

[Exactly-once Semantics are Possible: Here’s How Kafka Does it](https://www.confluent.io/blog/exactly-once-semantics-are-possible-heres-how-apache-kafka-does-it/)

[Delivering billions of messages exactly once](https://segment.com/blog/exactly-once-delivery/)

[Benchmarking Streaming Computation Engines at Yahoo!](https://yahooeng.tumblr.com/post/135321837876/benchmarking-streaming-computation-engines-at)

[Using logs to build a solid data infrastructure](https://www.confluent.io/blog/using-logs-to-build-a-solid-data-infrastructure-or-why-dual-writes-are-a-bad-idea/)

[Building DistributedLog: High-performance replicated log service](https://blog.twitter.com/engineering/en_us/topics/infrastructure/2015/building-distributedlog-twitter-s-high-performance-replicated-log-servic.html)

[LogDevice: a distributed data store for logs](https://code.fb.com/core-data/logdevice-a-distributed-data-store-for-logs/)

[Latency Is Everywhere And It Costs You Sales - How To Crush It](http://highscalability.com/latency-everywhere-and-it-costs-you-sales-how-crush-it)

[Big List Of 20 Common Bottlenecks](http://highscalability.com/blog/2012/5/16/big-list-of-20-common-bottlenecks.html)

[Performance is a Feature](https://blog.codinghorror.com/performance-is-a-feature/)

[Make Performance Part of Your Workflow](https://codeascraft.com/2014/12/11/make-performance-part-of-your-workflow/)

[How we built rate limiting capable of scaling to millions of domains](https://blog.cloudflare.com/counting-things-a-lot-of-different-things/)

[Readings in distributed systems](https://christophermeiklejohn.com/distributed/systems/2013/07/12/readings-in-distributed-systems.html)

[A Distributed Systems Reading List](https://dancres.github.io/Pages/)

## Arch Design
### API Design Guidelines
[How to Design a Good API](https://www.infoq.com/presentations/effective-api-design)

[Best Practices for a Designing a Pragmatic RESTful API](https://www.vinaysahni.com/best-practices-for-a-pragmatic-restful-api)

[Ideal rest api design](https://betimdrenica.wordpress.com/2015/03/09/ideal-rest-api-design/)

[Heroku Platform API Guidelines](https://github.com/interagent/http-api-design)

[Microsoft REST API Guidelines](https://github.com/Microsoft/api-guidelines/blob/vNext/Guidelines.md)

[Watson Developer Cloud services API Guidelines](https://github.com/watson-developer-cloud/api-guidelines)

[Zalando RESTful API and Event Scheme Guidelines](https://opensource.zalando.com/restful-api-guidelines/)

### Search 
[Instgram: Search Architecture](https://instagram-engineering.com/search-architecture-eeb34a936d3a)

[The Architecture of eBay Search](http://www.cs.otago.ac.nz/homepages/andrew/papers/2017-8.pdf)

[Faster E-commerce Search](https://www.ebayinc.com/stories/blogs/tech/making-e-commerce-search-faster/)

[Introducing LinkedIn’s new search architecture](https://engineering.linkedin.com/search/did-you-mean-galene)

[Search Federation Architecture at LinkedIn](https://engineering.linkedin.com/blog/2018/03/search-federation-architecture-at-linkedin)

[Search at Slack](https://slack.engineering/search-at-slack-431f8c80619e)

[Powering Search & Recommendations at DoorDash](https://blog.doordash.com/powering-search-recommendations-at-doordash-8310c5cfd88c)

[Building a complete Tweet index](https://blog.twitter.com/engineering/en_us/a/2014/building-a-complete-tweet-index.html)

[Manas: A high performing customized search system](https://medium.com/@Pinterest_Engineering/manas-a-high-performing-customized-search-system-cf189f6ca40f)

[Sherlock: Near Real Time Search Indexing](https://tech.flipkart.com/sherlock-near-real-time-search-indexing-95519783859d)

[Nebula as a Storage Platform to Build Airbnb’s Search Backends](https://medium.com/airbnb-engineering/nebula-as-a-storage-platform-to-build-airbnbs-search-backends-ecc577b05f06)

### Micro Service
[Martin Fowler: microservices](https://martinfowler.com/articles/microservices.html)

[Amazon: What are Microservices?](https://aws.amazon.com/cn/microservices/)

[Microsoft: Microservices architecture style](https://docs.microsoft.com/en-us/azure/architecture/guide/architecture-styles/microservices)

[Pivotal: What are Microservices?](https://pivotal.io/microservices)

[Microservices Best Practices for Java](https://www.redbooks.ibm.com/redbooks/pdfs/sg248357.pdf)

[Microservices vs Service-Oriented Architecture](https://www.nginx.com/resources/library/microservices-vs-soa/)

[Microservice Patterns](https://microservices.io/)

[Microservices antipatterns and pitfalls](https://www.oreilly.com/ideas/microservices-antipatterns-and-pitfalls)

[Microservice ARCHITECTURE: ALL THE BEST PRACTICES YOU NEED TO KNOW](https://codingsans.com/blog/microservice-architecture-best-practices)

[Best Practices for Building a Microservice Architecture](https://www.vinaysahni.com/best-practices-for-building-a-microservice-architecture)

[Simplicity by Distributing Complexity](https://time.geekbang.org/column/article/11116)

[Microservices Resource Guide](https://martinfowler.com/microservices/)

[PaaS vs. IaaS for Microservices Architectures: Top 6 Differences](https://www.altoros.com/blog/paas-vs-iaas-for-microservices-architectures-top-6-differences/)

[The Hidden Costs Of Microservices](https://www.stackbuilders.com/news/the-hidden-costs-of-microservices)

[Microservices - Not A Free Lunch!](http://highscalability.com/blog/2014/4/8/microservices-not-a-free-lunch.html)

[Github: Best practices for building a microservice architecture](https://github.com/katopz/best-practices/blob/master/best-practices-for-building-a-microservice-architecture.md)

[Github: Best practices for building a microservice architecture](https://github.com/katopz/best-practices/blob/master/best-practices-for-building-a-microservice-architecture.md)

[Building Microservices: Introduction to Microservices](https://www.nginx.com/blog/introduction-to-microservices/)

[Building Microservices: Using an API Gateway](https://www.nginx.com/blog/building-microservices-using-an-api-gateway/)

[Building Microservices: Inter-Process Communication in a Microservices Architecture](https://www.nginx.com/blog/building-microservices-inter-process-communication/)

[Building Microservices: Service Discovery in a Microservices Architecture](https://www.nginx.com/blog/service-discovery-in-a-microservices-architecture/)

[Building Microservices: Event-Driven Data Management for Microservices](https://www.nginx.com/blog/event-driven-data-management-microservices/)

[Building Microservices: Choosing a Microservices Deployment Strategy](https://www.nginx.com/blog/deploying-microservices/)

[Building Microservices: Refactoring a Monolith into Microservices](https://www.nginx.com/blog/refactoring-a-monolith-into-microservices/)

### Architecture
[Azure Architecture Center]https://docs.microsoft.com/en-us/azure/architecture/

## Container
### Docker
[Docker Documentation](https://docs.docker.com/)

[Docker — 从入门到实践](https://github.com/yeasy/docker_practice)

[Docker 问答录](https://blog.lab99.org/post/docker-2016-07-14-faq.html)

[A container networking overview](https://jvns.ca/blog/2016/12/22/container-networking/)

[Docker networking 101 – User defined networks](http://www.dasblinkenlichten.com/docker-networking-101-user-defined-networks/)

[Understanding CNI (Container Networking Interface)](http://www.dasblinkenlichten.com/understanding-cni-container-networking-interface/)

[Using CNI with Docker](http://www.dasblinkenlichten.com/using-cni-docker/)

[Battlefield: Calico, Flannel, Weave and Docker Overlay Network](http://chunqi.li/2015/11/15/Battlefield-Calico-Flannel-Weave-and-Docker-Overlay-Network/)

[Comparison of Networking Solutions for Kubernetes](http://machinezone.github.io/research/networking-solutions-for-kubernetes/)

[Docker Overlay Networks: Performance analysis in high-latency environments](http://www.delaat.net/rp/2015-2016/p50/report.pdf)

[An Updated Performance Comparison of Virtual Machines and Linux Containers](https://domino.research.ibm.com/library/cyberdig.nsf/papers/0929052195DD819C85257D2300681E7B/$File/rc25482.pdf)

[An Introduction to Docker and Analysis of its Performance](http://paper.ijcsns.org/07_book/201703/20170327.pdf)

[Docker Monitoring with the ELK Stack: A Step-by-Step Guide](https://logz.io/learn/docker-monitoring-elk-stack/)

[Valuable Docker Links](https://www.nkode.io/2014/08/24/valuable-docker-links.html)

[Best practices for writing Dockerfiles](https://docs.docker.com/develop/develop-images/dockerfile_best-practices/)

[Docker Best Practices](https://github.com/FuriKuri/docker-best-practices)

[Container Best Practices](http://docs.projectatomic.io/container-best-practices/)

[Eight Docker Development Patterns](http://hokstad.com/docker/patterns)

[Docker Handbook](https://jimmysong.io/docker-handbook/)

[Container-Networking](https://mozhuli.gitbooks.io/container-networking/)

### Kubernates

[Kubernetes Documentation](https://kubernetes.io/docs/home/?path=users&persona=app-developer&level=foundational)

[Learn Kubernetes Basics](https://kubernetes.io/docs/tutorials/kubernetes-basics/)

[Kubernetes Handbook](https://jimmysong.io/kubernetes-handbook/)

[Kubernetes 指南](https://kubernetes.feisky.xyz/zh/#kubernetes-%E6%8C%87%E5%8D%97)

[Learn Kubernetes using Interactive Browser-Based Scenarios](https://www.katacoda.com/courses/kubernetes)

[Kubernates Bootcamp](https://kubernetesbootcamp.github.io/kubernetes-bootcamp/)

[Kubernetes tips & tricks](https://opsnotice.xyz/kubernetes-tips-tricks/)

[How to Set Up Scalable Jenkins on Top of a Kubernetes Cluster](https://dzone.com/articles/how-to-setup-scalable-jenkins-on-top-of-a-kubernet)

[10 Most Common Reasons Kubernetes Deployments Fail (Part 1)](https://kukulinski.com/10-most-common-reasons-kubernetes-deployments-fail-part-1/)

[10 Most Common Reasons Kubernetes Deployments Fail (Part 2)](https://kukulinski.com/10-most-common-reasons-kubernetes-deployments-fail-part-2/)

[Kubernetes 101 – Networking](http://www.dasblinkenlichten.com/kubernetes-101-networking/)

[Kubernetes networking 101 – Pods](http://www.dasblinkenlichten.com/kubernetes-networking-101-pods/)

[Kubernetes networking 101 – Services](http://www.dasblinkenlichten.com/kubernetes-networking-101-services/)

[Kubernetes networking 101 – (Basic) External access into the cluster](http://www.dasblinkenlichten.com/kubernetes-networking-101-basic-external-access-into-the-cluster/)

[Kubernetes Networking 101 – Ingress resources](http://www.dasblinkenlichten.com/kubernetes-networking-101-ingress-resources/)

[Getting started with Calico on Kubernetes](http://www.dasblinkenlichten.com/getting-started-with-calico-on-kubernetes/)

[Automated Image Builds with Jenkins, Packer, and Kubernetes](https://cloud.google.com/solutions/automated-build-images-with-jenkins-kubernetes#kubernetes_architecture)

[Lab: Build a Continuous Deployment Pipeline with Jenkins and Kubernetes](https://github.com/GoogleCloudPlatform/continuous-deployment-on-kubernetes)

[Awesome Docker](https://github.com/veggiemonk/awesome-docker)

[Awesome-Kubernetes](https://github.com/ramitsurana/awesome-kubernetes)

[The New Stack eBook Series](https://thenewstack.io/ebooks)

## Block Chain
### Bitcoin
[Bitcoin White Paper](http://www.yuxiumin.com/2018/01/16/bitcoin-white-paper/)

[Bitcoin Developer Guide](https://bitcoin.org/en/developer-guide#block-chain)

### Ethereum
[Ethereum White Paper](https://ethfans.org/wikis/%E4%BB%A5%E5%A4%AA%E5%9D%8A%E7%99%BD%E7%9A%AE%E4%B9%A6)

[The Ethereum Wiki](https://theethereum.wiki/w/index.php/Main_Page)

[以太坊设计原理](https://ethfans.org/posts/510)

[Ethereum Design Rationale](https://github.com/ethereum/wiki/wiki/Design-Rationale)

## Documentation
[Google developer documentation style guide](https://developers.google.com/style/)
