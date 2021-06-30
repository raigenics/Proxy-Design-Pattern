# Proxy-Design-Pattern
The literal meaning of Proxy is – In Place of or Representing somebody or something, or on behalf of somebody.

The Proxy Design Pattern provides an intermediate or a placeholder object for another object that servers the functionality. The Proxy design pattern falls into the Structural Pattern category as defined by the Gang of Four (GoF). 

Features of a Proxy:

- The prime objective of a proxy is to ensure access control and security
- A proxy provides a substitute or a placeholder for another component or object
- The proxy thus can control access to the original component or object and can possess additional validation functionality before or after the component is called.
- These are also known as wrappers or surrogates since they encapsulate the actual functionality and provide an additional layer of abstraction.

Why use the proxy design pattern?

The proxy design pattern can be used in situations where you would like to defer instantiation of a class until the time it is needed. The proxy is an object that can be used to control access to a remote resource or to a more complex object, i.e., an object whose creation or operations would consume more resources.


Type of Proxy:

Remote proxy. Remote proxies encode the request and then send the encoded request to the actual object.

Virtual proxy. Virtual proxies are typically used when the actual object is heavy. To conserve client resources, they defer the instantiation of the actual object until it is truly needed; i.e., instantiation is done only on demand. 

Protection proxy. Protection proxies are used to restrict access to a resource. If the caller of the request lacks the necessary permission to access the resource, then access is denied. 

# For detailed explanation see https://youtu.be/MKlGop_EAZI
