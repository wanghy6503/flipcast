# Flipcast
FlipCast is a scalable, multitenant, customizable push notification platform for mobile, devices & web.
FlipCast is built on high performance, high throughput fault tolerant infrastructure components like
spray.io, akka.io which can leverage modern multi-core hardware to support high concurrency.
Support for MongoDB datasource is provided out-of-the-box.

## Releases
| Release | Date | Description |
|:------------|:----------------|:------------|
| Version 1.0    | April 2014      |   Initial OSS release

## Changelog
Changelog can be viewed in [CHANGELOG.md](https://github.com/Flipkart/flipcast/blob/master/CHANGELOG.md) file

## Supported mobile platforms:
* iOS
* Android
* Windows Phone 8

## Supported Features:
* Device register/unregister API
* Configurable push message payloads
* Automatic housekeeping for invalid devices
* Automatic/Transparent retry and sidelining
* Message history management
* Pluggable data source (Default: MongoDB)
* Automatic backpressure management
* Unicast, Multicast & Broadcast Push API
* Auto Batching for multicast & broadcast push

## Library Dependencies
--------------------
* [spray](http://spray.io) 1.2.0
* [Scala](http://www.scala-lang.org) 2.10.2
* [akka.io](http://akka.io) 2.2.4
* [amqp-client](https://github.com/sstone/amqp-client) - 1.3-ML4
* [java-apns](https://github.com/notnoop/java-apns) - 0.2.3
* [casbah](http://mongodb.github.io/casbah) - 2.6.5
* [hazelcast](http://hazelcast.org) - 3.1.2

## Infrastructure Dependencies
* [RabbitMQ](https://www.rabbitmq.com)
* [MongoDB] (https://www.mongodb.org)

## Documentation
Please refer to [Wiki](https://github.com/Flipkart/flipcast/wiki) for FlipCast documentation

## License
FlipCast is licensed under : The Apache Software License, Version 2.0. Here is a copy of the license (http://www.apache.org/licenses/LICENSE-2.0.txt)

## Core contributors
* Phaneesh Nagaraja ([@phaneeshn](http://twitter.com/phaneeshn))

