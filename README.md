WcfServiceCallLogger
====================

lightweight  logger for tracing WCF service invocations. Provides config file based logging of WCF service method invocations. Analyses client side SOAP message content during message despatch pipeline and logs output using NLog

TODOs (pull requests welcome)  

1) Adding Service Side logging functionality  

2) Investigate performance of logging - message.tostring might not perform very well  

3) Investigate processing of json serialized messages  

4) Decouple logging implementation  

5) Replay results facility?


WcfServiceCallLogger is on Nuget

http://nuget.org/packages/WcfServiceCallLogger/
