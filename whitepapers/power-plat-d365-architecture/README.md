# US Government Power Platform / D365 Architecture

## US Government Cloud Offerings

![Gov Cloud Overview](files/Slide1.PNG)

## GCC Architecture
![GCC Overview](files/Slide2.PNG)

## US Government Cloud Video Recordings
Below is a presentation recording covering US Gov Cloud specific architecture of Power Platform and D365 at a Meetup group talk.  The video recording can be found below,

[Power Platform / D365 US Government Cloud Overview](https://www.youtube.com/watch?v=027gVhqt1l0&t=101s)

There's also a great video that overviews all of Microsoft's Sovereign Clouds,

[Microsoft Sovereign Clouds - Power CAT Live](https://www.youtube.com/watch?v=DMg3uQ5EFLI)

## US Government Specific Documentation

* [Power Automate US Government Docs](https://docs.microsoft.com/en-us/power-automate/us-govt)
* [Power Apps US Government Docs](https://docs.microsoft.com/en-us/power-platform/admin/powerapps-us-government)
* [D365 US Government Docs](https://docs.microsoft.com/en-us/power-platform/admin/microsoft-dynamics-365-government)

## US Government Feature Parity Documentation

[US Government Power Platform / D365 Feature Matrix](https://aka.ms/BAPFunctionalParity)

### GCC Power Platform Connectors
The list of GCC Power Platform connectors available can be found below,

[GCC Power Platform Connectors List](https://gov.flow.microsoft.us/en-us/connectors/)

### Azure Commercial vs Azure for Government in GCC

Today, for GCC customers, you have the option with certain Azure connectors (e.g., SQL Server) to toggle between Azure for Government or Azure Commercial subscription.  This toggle option will eventually make its way to other Azure connectors in Power Platform GCC.

![GCC SQL Server Connector](files/Slide7.PNG)

Today, some connectors in GCC Power Platform service will assume that the resources you want to use are only Azure for Government resources.

![GCC Connectors](files/Slide5.PNG)

A work around for the listed scenario above is to create a Azure Logic App in Azure Commercial and use that with the Azure commercial connectors to get access to the resources you want to leverage,

![GCC Connector Work Around](files/Slide6.PNG)
