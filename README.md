# CVArchitecture
Denver's high-level conceptual design and architecture for connected vehicle deployments.

## Background
Connected vehicle technology, enabling vehicles to communicate with one another and with city infrastructure, holds the potential to dramatically improve the safety of our streets and reduce congestion. This repository serves to capture Denver's conceptual architecture, and shows our approach to implementing connected vehicle technology.

We welcome comments and recommendations, provided as GitHub issues, on our approach. This repository will be a living space for Denver to refine it's achitecture with community input.

## Values
Our approach is based on a set of values we’ve established with our Denver Smart City program:
*	__Embrace__ emerging smart industry standards as they develop
*	__Co-design__ architecture to support multi-vendor interoperability
*	__Maintain__ local control and ownership of City and County of Denver data
*	__Leverage, Collaborate and Contribute__ to open source community innovation and the exchange of knowledge

These values have carried through into the design and architecture we're proposing:

*	Denver will build on the investments the U.S. Department of Transportation has made in open source technologies, including the [V2I Hub](https://www.itsforge.net/index.php/community/explore-applications#/40/148 "V2I Hub 3.2") and the [@JPO-ODE Operational Data Environment (ODE)](https://github.com/usdot-jpo-ode "Operational Data Environment").
*	Denver will deploy CV applications as plug-ins on the V2I Hub to maintain interoperability across vendors.
*	Denver will develop API endpoints from it’s cloud environment for external stakeholders, developers, and members of the public.
*	Denver will utilize the USDOT Operational Data Environment to build in best practices for privacy and data security into it’s cloud environment.
*	Denver will publish other aspects of its code base to make this technology stack function, including device management platforms.

## Usage 
Denver is providing two diagrams as part of this repository, a _CV Network view_ and a _Data Flow view_ of our CV system. Denver has also produced additional diagrams for internal stakeholders that detail networking and security protocols.


### CV Network View:
![CV Network][ImageCVNetworkView]
Raw XML file for Draw.io: https://github.com/DenverConnectedVehicle/CVArchitecture/blob/master/Denver%20CV%20Network%20Public.xml

---

### Data Flow View:
![Data Flow View][ImageDataFlowView]
Raw XML file for Draw.io: https://github.com/DenverConnectedVehicle/CVArchitecture/blob/master/Denver%20CV%20Data%20Flow%20Public.xml


### Supporting documents on Wiki
Please find additional documentation supporting these diagrams on the Repo's wiki page.

[ImageCVNetworkView]: https://github.com/DenverConnectedVehicle/CVArchitecture/blob/master/Denver%20CV%20Network%20Public.jpg "CV Network"
[ImageDataFlowView]: https://github.com/DenverConnectedVehicle/CVArchitecture/blob/master/Denver%20CV%20Data%20Flow%20Public.jpg "Data Flow View"

## Contributing 
Please provide comments on Denver's diagrams by using GitHub issues. The Denver program team will answer questions, and address suggestions using these issues. 

## Credits
This effort is the result of a tight collaboration across the Denver Smart City program, including colleagues from Public Works, Technology Services, Department of Public Health and Environment and the Mayor’s office, as well as from the Federal Highway Administration (FHWA). This work is made possible by the FHWA Advanced Transportation and Congestion Management Technologies Deployment (ATCMTD) grant.
