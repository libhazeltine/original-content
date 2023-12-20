# CIDS

> **IMPORTANT:** This is an archived document (rev. 23J29) and does not reflect current intentions, designs, or implementations.

Construct Infrastructure Development Service is a system of energy capture and construct operation networks to be installed in various locations in southern california. It is modeled in purpose, but not in design, after “cloud computing” software platforms in which large amounts of hardware infrastructure is used to run many different services for a wide variety of different use cases.

Unlike cloud computing, CIDS operates on a distributed model, where each “service” (program) gets its own “site” (physical location) rather than deploying all services to a single site with hundreds of other services.

Sites are sourced from a database of over five hundred possible locations across 15 different areas of Southern California. New sites are added to the system only as new constructs are created. 

Services are deployed to “networks” of individual “nodes” (constructs) both at and around its respective site. A network consists of one primary node at the site, for both running the service and storing excess energy gathered by several capture nodes, which are deployed in a chain-like layout going from the main site, to more busy public locations close by, such as a bus stop, or strip mall. Capture nodes cannot be more than 600ft apart from one another.

When a new construct is ready to be deployed, a site location is selected from the database and studied for possible sites of capture nodes. When time is available, a physical visit is made to the site for installation of anchors, which are physical objects that bind the construct to the location. 

Constructs require both an authentic signature of the sysadmin and physical presence at the location in order to issue administrative commands. However, they can still be destroyed by any individual with physical access to the anchor. For this reason, all site locations, as well as the anchor binding procedure, is not shared with anyone, including trusted partners. This greatly reduces the potential for unwanted destruction by adversaries or compromised partners. Additionally, if an anchor is destroyed, any remaining energy is used to telepathically ping the sysadmin who can install a new anchor at the site.

```
Document Path: //libhazeltine/original-content/projects/support-framework/ARCHIVE-cids.md
Document Revision Tag: hazelsupportframeworkadditionaldocumentationcidsspec.23L20.internal
Document Archival Date: 20th December, 2023
Document Planned Publication Date: 21st December, 2023
Original Document Creation Date: 29th October, 2023
Original Document Location: x-apple-cloudkit://com.apple.Notes/Notes/Hazel%20CIDS#231029
Project Name: hazelsupportframeworkadditionaldocumentation.internal
```

```
Project Hazel - Support Framework Additional Documentation
Copyright 2023-present, Jordan Silver (github.com/libhazeltine)
```