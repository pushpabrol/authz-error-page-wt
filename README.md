# Simple webtask to show unauthorized error

## Setup

Follow steps within your auth0 dashboard -> Settings -> webtask to init your webtask container using the webtask cli ( webtask.io)
### Create the webtask
- `wt create authz-error.js -p "<webtask profile name>"`
- Note the webtask url after create and use this within the Auth0 rule to redirect User to an unauthorized error page

