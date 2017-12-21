In order to get this working you need to use mapping template applied to your API gateway endpoint, as described here: 

http://docs.aws.amazon.com/apigateway/latest/developerguide/api-gateway-mapping-template-reference.html

using $context.identity.sourceIp

It can be hard to locate within api gateway, its under method , integration request, bodymapping templates


