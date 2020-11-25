# JMeter-Rabbit-AMQP #
======================

A [JMeter](http://jmeter.apache.org/) plugin to publish & consume messages from [RabbitMQ](http://www.rabbitmq.com/) or any [AMQP](http://www.amqp.org/) message broker.


JMeter Runtime Dependencies
---------------------------

Prior to building or installing this JMeter plugin, ensure that the RabbitMQ client library (amqp-client-3.x.x.jar) is installed in JMeter's lib/ directory.


Build Dependencies
------------------

Build dependencies are managed by Maven.


Building
--------

The project is built using Ant. To execute the build script, just execute:
`mvn clean package`


Installing
----------

To install the plugin, build the project and copy the generated JMeter-Rabbit-AMQP-xxx.jar file from target/ to JMeter's lib/ext/ directory.

