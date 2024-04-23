# Configuration
### with  browser
astro login

### Browserless
astro login -t 
https://cloud.astronomer.io/token
astro login -l retrieve url
curl -u <user-email>:<password> <returned-url>

### Changing domains

- list
astro context list

- reauth
astro login <basedomain> 

- switch
astro context switch <basedomain>
