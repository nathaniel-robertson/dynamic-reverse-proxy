Simple reverse proxy tool to access a host name at a given IP address. Yes, you can simply use curl --resolve, but if you have a need to actually view the page in a browser, this tool makes it possible. This really only will work for the HTML, however, as it will not roxy all of the resources needed like CSS. So it ended up being less useful than hoped.

## Usage

https://<deploymentdomainofproxytool>/example.com/1.2.34
