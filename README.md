# APIOps Design and Maintenance Model

![](https://raw.githubusercontent.com/APIOps/apiops-design-process/master/images/apiops-design-process.png)


## Joint open design process

API design first approach focuses on involving service and API developers and marketing to same process of co-creating API description. API description is a communication tool, it is not code, at best it is browser-based graphical userface in which all participants collaborate and contribute. Process involves 3rd party service developers into the development since they are endusers of APIs and know best the needs. Obviously the product owner of service utilizing APIs is involved. During the process all work together; sometimes intensively and occasionally there might be total silence. The  team uses f2f meetings and online environments as well as instant messaging tools to communicate. In other words, there is no written rule or need to necessary to be all the time in the  space/room. This phase produces shared version controlled understanding of:
* API features
* API consumer needs
* Machine readable description of API or multiple APIs


## Speed up development with code generation

In the  second phase APIOps (API developer) uses the machine readable  description file to configure code generation toolchain. Toolchain automatically generates both API server skeleton and client side development kits (SDK) for plethora of operating systems including mobile platforms such as iOS, Android, Windows. 

Generating API server code kicks the development at full speed right from the start. API developer needs to adjust and fine tune actual code a lot less compared to other approaches. The SDKs are important since they lower the barrier to utilize newly created APIs. Having top notch API is nice, but widely utilized and liked API is golden. 


## Service Development Platform as online hub

Eventually API server code is launched at production server and attached to API management, which is part of Developer Portal (DP). DP enables service developers' easy access to APIs, API documentation, SDKs, code examples and community. In Developer Portal  API provider can limit the usage of APIs, see metrics and even retire entire API. In portal, API developers and consumers can exchange ideas and use documented comments as feedback for the next cycle which begins from the Joint open design process.  

All this should take plane inside planned roadmap and business plan. Internet of Things (IoT) is something  which in common terms connects devices to each other to exchange data.  IoT relies heavily on web APIs which in fact enable us to connect  services and objects with each other. Without reliable, easily implemented backends and front-end support, new services build on top of  IoT, will not succeed.
