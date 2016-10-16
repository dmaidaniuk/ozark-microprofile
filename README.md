# Java EE MVC 1.0 Demo on MicroProfile

The code in this sample is highly experimental as the work on [JSR-371][1] is ongoing. That means that it may not always build or run on the latest snapshots. 

Java EE MVC is a new action based [MVC framework][2] planned for Java EE 8. The reference implementation of JSR-371 is [Ozark][2]. 

This Demo running on [MicroProfile][4] for next 2 servers:

* [Payara Micro][5]
* [WildFly Swarm][6] **Note:** for Wildfly Swarm you need build my [Ozark fraction][7] first.


[1]: https://jcp.org/en/jsr/detail?id=371
[2]: https://ozark.java.net/index.html
[3]: https://java.net/projects/mvc-spec/pages/Home
[4]: http://microprofile.io/
[5]: http://www.payara.fish/payara_micro
[6]: http://wildfly-swarm.io/
[7]: https://github.com/dmaidaniuk/wildfly-swarm-ozark