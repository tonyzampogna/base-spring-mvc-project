#Spring Example

This project is a basic spring project (setup for Tomcat 7.0 and Eclipse 4.3).

There is one controller that handles all reaquests from the base URL.

## Gliches
1. One problem that I ran into is that static content should be excluded from the root request mapping. In order to do this, I added the <mvc:resources> tag, but that gave me a 404 error in the Spring controller. After a little googling, I found [this article](http://stackoverflow.com/questions/4057529/using-mvcresources-in-spring-3-causes-all-other-views-to-stop-working)

2. Another issue is that going to the default url is adding a "/" (forward slash) to the end of the URL.

