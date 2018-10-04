# HERE Mobility Platform Overview #

HERE Mobility aims to democratize the mobility ecosystem. We are creating a competitive marketplace powered by intelligent technological solutions for all mobility service providers, businesses, and consumers.

HERE’s central platform is the **HERE Mobility Marketplace**, a hub for supplying and requesting mobility services, for businesses and consumers. The Marketplace enables matching up end users with suppliers who can meet their needs for transportation and delivery.

The HERE Mobility platform offers two APIs: the **Demand API**, for use by client applications serving end users (passengers), and the **Supply API**, for use by applications representing ride suppliers such as taxi dispatching stations.

The **HERE Mobility Demand API** is a REST or GRPC API that enables the calling application to request, book and cancel mobility services. Demand API requests are sent to the HERE Mobility Marketplace, which matches up ride requests with available suppliers, and manages ride information and statuses.

The **HERE Mobility Supply API** is a REST or GRPC API that enables the HERE Mobility Marketplace to request and book rides from suppliers, and enables suppliers to send updates about rides in progress.

## Resources ##

Visit the resources below to learn more about the Supply API and how to use it.

Resource | Description
:--------|:------------
[Supply API Developer Guide](https://github.com/Developers-Here-Mobility/HERE-Mobility-Supply-API-Developer-Guide) | A high-level guide that describes Ride Supply workflows and how to implement them using the Supply API. The guide contains code examples for REST and GRPC calls.
[Supply REST API Reference Guide](https://github.com/Developers-Here-Mobility/Here-Mobility-Supply-API-REST) | A detailed reference guide for the REST Supply API, including all calls, parameters and messages.
[Supply GRPC API Reference Guide](https://github.com/Developers-Here-Mobility/Here-Mobility-Supply-API) | A detailed reference guide for the GRPC Supply API, including all calls, parameters and messages.
