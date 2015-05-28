# plushu-nginx-apps

This plugin handles the general bureaucratic management for Nginx
configurations around *changes* to an app, like its renaming or deletion.

This plugin does not handle any actual *creation* of Nginx configurations for
apps. Configurations for apps are created and updated in plugins like
plushu/plushu-app-nginx-servers (writing Nginx server definitions for an app's
defined domains) or plushu/plushu-app-nginx-upstream-docker (linking an app's
defined Nginx servers to the local Docker container for that app).
