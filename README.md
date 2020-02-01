# obis-issues

The OBIS Issues repo is used for capturing and tracking all types of issues that arise in the regular operation of OBIS, from the portal and web site to the map tool, API, R package, and other tools in the OBIS ecosystem of capabilities. OBIS issues are the responsibility of the OBIS community, including the OBIS Executive Committee, OBIS Steering Group, OBIS Secretariat (data management and software engineering), and our community at large. Anyone can post issues and comment, and we encourage both direct contribution and capture of issues from meetings, training, and other activities.

We make use of labels on issues to help determine what kind of action is appropriate and assignments to individuals within our community who need to comment and close issues or articulate how issues need to be taken to action in engineering the system. The following guidelines should be used in creating and managing issues in this repo.

## Labeling

* API - Features needed in the API
* bug - Inappropriate behavior in the application indicating a bug
* data quality - Issues associated with the quality/completeness of datasets and records
* data rescue - Datasets identified for potential rescue operations
* data standards - Issues associated with the Darwin Core or other standards employed that have not yet been assigned
* Dead Letter - Issues that have rotted in the system for too long and can't be acted on without further detail
* duplicate - Duplicate of another issue; comment should point to the preferred issue to be resolved
* harvesting - Issues associated with the OBIS harvesting pipeline process and codebase
* mapper - Mapper.obis.org map tool
* metadata portal - metadata.obis.org application for managing internal connections
* OBIS EC - Issues that need to be addressed by the OBIS EC and passed on to appropriate assignments
* OBIS Manual - Requested documentation changes to the OBIS manual
* Processing Pipeline - Issues associated with the data processing pipeline and properties added in processing
* smalldata - smalldata.obis.org application for submitting individual records to the OBIS database
* website - Static text and informational aspects of the OBIS.org web site

## Level of Detail and "Issue Rot"

Some issues are really obvious without much detail needed while others require additional details before any action can be taken. The longer an issue sits in the repo without any action being taken, the more likely it will be that the issue will require additional work just to figure out what's really going on and what might be needed to deal with it. Submitters are encouraged to provide sufficient detail, URL pointers to relevant pages or parts of the system, screen shots or other images, and overall enough information so that we can decide how best to proceed. Issues that sit in the system for too long without someone being able to figure out how to proceed are labeled with "Dead Letter" and closed unless and until someone raises them again and puts in more details.

## Engineering Actionable

Many issues that come up can't really have anything done on them from a software engineering standpoint until some fundamental decisions are made or background work is done by someone in the OBIS community through our task teams. Almost anything we do or build into the system will involve a technical implementation of some kind but also documentation at multiple levels explaining a feature, providing guidance in the OBIS Manual, explaining an API route, and other aspects of communication. When laying out an issue and pursuing it toward action, we can accelerate the development process by keeping the communication/documentation aspect in mind and starting to fill that information in while building toward the new technical feature.

## OBIS EC Issues

The OBIS Executive Team, made up of the OBIS Steering Group Co-chairs and Task Team Leads, helps to guide the overall OBIS effort on a more real time basis throughout the year through monthly meetings. When issues come up over time, the OBIS EC can be assigned items that need some consideration to determine how to proceed. Many times this will include figuring out if an existing Task Team can be pulled in to work on some further exploration, background work, and documentation before some engineering work can be done. The OBIS EC may also help determine that an issue really is not appropriate to deal with at a point in time or that it needs to be further debated to determine action.

## Links to Other Repos

The obis-issues repo was set up as a clearinghouse and central location to manage all manner of issues that come up in the operation of OBIS. Many of the items that arise will eventually be taken care of in the various components of the OBIS technical infrastructure that are based in their own repos, some of which are not public (at least not yet). When an issue gets to the point where it is "engineering actionable," a comment will link it to one or more issues in another repo where software engineering is going on.
