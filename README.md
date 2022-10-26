# Course Outline Mapping and Management System (COMMS)

# Release Notes

## v2.3.0
Date Released: 2018-03-15

Production Ruild: 290

Production Release: Release-4

- External Course Outline Viewer added. Course outlines can now be searched and retrieved from external web sites by embedding this viewer.
- Rollover Management added to Administrator functions. Customer Administrators can now manage their own rollovers.
- Support Staff role updated for usability. Support staff are super users that can perform administrative functions without having access to certain top-level admin functions.
- Some REST API features added to assist with future integrations; currently in ALPHA.
- Now using automated build and release strategy in VSTS.
- Source control now uses Git.
- Infrastructure reorganized into independent app services for each major customer. Remaining customer instances (colleges piloting comms) move to single app service commsglobal.
- There are now only 3 primary databases, Development, Test, and Production.
- Various bugfixes.