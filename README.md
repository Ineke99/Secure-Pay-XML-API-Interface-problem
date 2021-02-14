# Secure-Pay-XML-API-Interface-problem
SecurePay XML API Interface problem. I crash on the line $function with an IIS error 405.
Well, the $(function problem is resolved as the jquery.min.js was not loaded as that was a not-allowed link on the server.
The links https://test.api.securepay.com.au/antifraud/payment and https://api.securepay.com.au/antifraud/payment also need to be allowed links in the Tools --> internet Settings --> Security tag.
I'm now at the stage of not crashing but also not getting a reply from the secure pay site.
