# OPC UA .NET Standard stack documentation #

## Overview  ##

Here is a list of available documentation for different topics:

UA Core stack related:
* About [.NET platform](PlatformBuild.md) support, Nuget packages and versioning.
* How X.509 [Certificates](Certificates.md) are used in the certificate stores.
* Using the [Reverse Connect](ReverseConnect.md) for the UA-TCP transport.
* Support for the [TransferSubscriptions](TransferSubscription.md) service set.
* Improved support for [Logging](Logging.md) with `ILogger` and `EventSource`.
* Support for [WellKnownRoles & RoleBasedUserManagement](RoleBasedUserManagement.md).
* Support for [ECC Certificates](Docs/EccProfiles.md).

Reference application related:
* [Reference Client](../Applications/ConsoleReferenceClient/README.md) documentation for configuration of the console reference client using parameters.
* [Reference Server](../Applications/README.md) documentation for running against CTT.
* Using the [Container support](ContainerReferenceServer.md) of the Reference Server in VS2022 and for local testing.

Starting with version 1.5.375.XX the winforms reference client & winforms reference server were moved to the [OPC UA .NET Standard Samples](https://github.com/OPCFoundation/UA-.NETStandard-Samples) repository.

For the PubSub support library:
* The [PubSub](PubSub.md) library with samples.
* The [ConsoleReferencePublisher](../Applications/ConsoleReferencePublisher/README.md) documentation.
* The [ConsoleReferenceSubscriber](../Applications/ConsoleReferenceSubscriber/README.md) documentation.


  
