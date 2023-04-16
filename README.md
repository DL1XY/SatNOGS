
# SatNOGS 
[SatNOGS](https://satnogs.org) related stuff 

## postman
Contains Postman collection for DB and network requests, see

### Database API v1.1
https://db.satnogs.org/api/schema/docs/

### Network API v0.0.0 
https://librespacefoundation.gitlab.io/-/satnogs/satnogs-network/-/jobs/3507307553/artifacts/satnogs-network-api-client/html2/index.html#api-_

You should create an Environment in Postman to store your API keys and add the Authorization info for DB and Network individually on their root folder.
Authorization type is OAuth 2.0 and the Header Prefix should be Token instead of Bearer.

As I don't run a SatNOGS station, some requests are not tested yet

## notebooks

Jupyter notebooks to play around with the SatNOGS APIs
