Docs
http://reportportal.io/docs 

JIRA:
Magadra assignolod a ticketet.
Ha elkezted tedd in-progressbe.
A develop branchről csinálj egy feature branchet a JIRA ticket nevével.
Ha kész vagy, akkor nyiss egy PR-t vissza a developba, a JIRA ticketet pedig tedd Testingbe. FONTOS, hogy add hozzá a DNT labelt és a ticket title-jébe is tedd be a [DNT] prefixet (Do Not Test).
Ha megvan a code review, és visszamegy a PR, utána levesszük a DNT dolgokat és letesztelik.

React app: 
https://github.com/reportportal/service-ui/tree/develop/app


BackBone app:
/service-ui/src/main/resources/public

Travis:
https://travis-ci.org/reportportal/service-ui

.env:
PROXY_PATH=http://dev.epm-rpp.projects.epam.com:8080/


