# FroDaS (front-data-service)

## Overview
This is front-end (Typescript, Javascript) service, that helps to work with a data from a different stores and protocols.

### Data definition
There are different types of data developers works with. We are going to separate data into the groups, by some of attributes(nature, behavior). Currently we separating data by:
- Data store;
- Exchange method;
- Access (data availability);
- Priority.

##### Stores
*Server side*
- **Database**
- **Search index**
- **Filesystem (http)**
- **Third party services**

*Client side*
- **Indexed DB**
- **Local storage**
- **Session storage**
- **Filesystem (local cache)**
- **Runtime memory**

##### Exchange
- Request/response
- Socket (server can initinitiate sending)
- Notifications (datagram distribution)
- Downloading/uploading

##### Access
- Public
- Private
- Users (authenticated users)
- Context (organization, group, folder)

##### Priority
- Normal
- High
- Low

------------