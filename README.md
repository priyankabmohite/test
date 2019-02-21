This is the main service which is going to communicate with other service "callme" using Feign.

URL for local environment : http://localhost:8085/swagger-ui.html

Don't forgot to add below property in application.properties file.
callme.url = http://localhost:8088
