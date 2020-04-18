# myRestTests
Sample project to implement test classes that make REST requests and process response.

## Logstical work
- [x] Install IntelliJ
- [x] Add Maven plugin to IntelliJ
- [x] Add Maven dependencies - Apache HTTP client, Jackson
- [x] Create Maven project and create repo with it on Git Hub (this repo)
- [ ] Install TestNG plugin (or add it as Maven dependency?)

## Develop Java Classes / Methods to be able to do these
- [x] HTTP GET using Aache HTTP Client
- [x] Parse JSON response -- using Jackson
- [ ] Add Authentication to the requests (Digest / Basic)
- [ ] Construct JSON payload (for POST) -- using Jackson
- [ ] Parse multipart Response from the server
- [ ] Add support for POST
- [ ] Add Support for PUT
- [ ] Add Support for Delete
- [ ] Add SSL support (HTTPS)
- [ ] Add Concurrency (min, max users)
- [ ] Write tests that can be executed via TestNG
 
## Test with these APIS
* Management APIs : [http://docs.marklogic.com/REST/management]
* Document Management APIS : [http://docs.marklogic.com/REST/client/management]
* Search APIs : [http://docs.marklogic.com/REST/client/search]