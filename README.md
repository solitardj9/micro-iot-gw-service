# micro-iot_gw-service

## 1. Concept
### 1.1. Authenticationauth Management
### > > 1.1.1. about thing
#### > > > 1.1.1.1. Create certificate for thing.
> > > > - Create outgoing queue for the thing.
#### > > > 1.1.1.2. Delete certificate of thing.
> > > > - Delete outgoing queue of thing b/f delete thing.

2. Authorization Management

3. Event Management


Create certificate for iot-service.
Delete certificate for iot-service.
Create certificate for external services (ex : micro services).
Delete certificate for micro services (ex : micro services).
Attach policy.
Detach policy.
Create Consumer Group Queue. (Create incoming queue for consumer group of iot-service)
Create and Bind Connection Event Queue. (Internal)
Create and Bind Connection Event Queue. (External)




## 2. System Architecture

## 3. Build a System
### 3.1 Message Middleware (RabbitMQ)
#### Installation
<pre>
<code>
In this case, just use single node.
If you want to cluster(In local), need to install LB(HA Proxy : http://www.haproxy.org/) and VIP(Keepalived : https://www.keepalived.org/)
Then, configure RabbitMQ.conf.
</code>
</pre>

rabbitMQ.conf
SSL
Auth
> > rabbitmq-auth-backend-http

### 3.2 Im-Memory Storage (Hazelcast)
#### Installation
<pre>
<code>
In this case, just use single node.
If you want to cluster(In local), need to install LB(HA Proxy : http://www.haproxy.org/) and VIP(Keepalived : https://www.keepalived.org/)
Then, configure hazelcast.xml.
</code>
</pre>
