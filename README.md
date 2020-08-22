# micro-iot_gw-service

## 1. Concept
### 1.1. Authenticationauth Management
### 1.1.1. Thing
#### 1.1.1.1. Create certificate for thing.
> > Create certificate for thing.
> > Create outgoing queue for the thing.
#### 1.1.1.2. Delete certificate of thing.
> > Delete certificate of thing.
> > Delete outgoing queue of thing b/f delete thing.

### 1.1.2. Internal Service
#### 1.1.2.1. Create certificate for Internal Service.
> > Create certificate for iot-service.
#### 1.1.2.2. Delete certificate for Internal Service.
> > Delete certificate of iot-service.

### 1.1.3. External Service
#### 1.1.3.1. Create certificate for External Service.
> > Create certificate for external services (ex : micro services).
#### 1.1.3.2. Delete certificate for External Service.
> > Delete certificate of external services (ex : micro services).

### 1.2. Authorization Management
### 1.2.1. Thing
#### 1.2.1.1. Attach policy.
> > attach policy for thing.
#### 1.2.1.2. Detach policy.
> > detach policy of thing.

### 1.3. Event Management
### 1.3.1. Internal Service
#### 1.2.1.1. Acquire Connection Event Queue for things.
> > Create and bind connection event queue for iot-service.
#### 1.2.1.2. Release Connection Event Queue of things
> > Unbind and delete connection event queue for iot-service.

### 1.3.2. External Service
#### 1.3.2.1. Acquire Connection Event Queue for things.
> > Create and bind connection event queue for external services (ex : micro services).
#### 1.3.2.2. Release Connection Event Queue of things
> > Unbind and delete connection event queue of external services (ex : micro services).

### 1.4. Queue Management

#### 1.4.1. Create consumer group queue.
> > Create incoming queue for the things.
> > Incoming queues are mapping to iot-services in Consumer groups.
> > > (https://github.com/solitardj9/micro-iot-service/blob/master/README.md#34-micro-iot-service)
#### 1.4.2. Delete consumer group queue.
> > Delete incoming queue for the things.




