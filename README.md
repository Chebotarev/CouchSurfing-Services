CouchSurfing-Services
=====================

Static Jekyll site for monitoring the status of the services offered by Couch Surfing


Basic File Organization: 

Each of the pages in the site has a layout of "default" which sets up the header and footer of the site.
This layout file is described by /_layouts/default.html

The home page, the page that lists all the services, is described by /index.html

Each service has a layout of "service", which is described by /_layouts/service.html

The services themselves are located in the /services folder, in subfolders with custom names.
They are described by /services/custom-folder-name/index.html and consist entirely of YAML front-matter for ease of use.
