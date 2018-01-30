﻿# sc-frame
springcloud技术框架，可应用于项目中作为脚手架。

<br><br>
<b>说明：</b>
<br>
1、sc-register是Eureka实现的注册中心<br>
2、sc-service与sc-service-jsp是服务提供方，这些服务会注册到sc-register注册中心。另外，从命名上可以看出来，sc-service-jsp支持JSP。<b>注意，这里集成前端仅仅是为了测试方便，在项目中，前端应该在服务的消费方，如在本工程的sc-client模块中集成前端。</b><br>
3、sc-gateway是微服务网关，通过微服务网关访问sc-service与sc-service-jsp服务。<br>
4、sc-client是服务的消费方。在内部进行服务调用，可通过sc-client访问服务sc-service与sc-service-jsp。

