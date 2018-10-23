# WebConnex
As an employee of a private university foundation, I work with WebConnex GivingFuel.  GivingFuel is a modern lightweight giving platform for managing donations.

To expand on the features of the built in functionality of GivingFuel, I've created PHP and JavaScript extensions.  This repository is dedicated to housing some of these extensions.

## Important Disclaimer
Before using any extensions, please note that GivingFuel's platform is hosted in a secure, PCI compliant environment. I highly suggest any external code (including these extensions) be hosted in a similar secure environment.

Introducing third-party and/or offsite programming onto a GivingFuel page introduces risks:
1. A hacked third-party host could lead to malicious scripts that could be used to steal CC info.
2. A third-party host that goes offline may lead to extensions not working and breaking components on the page.

It is recommended that you conduct an independent audit before deploying any code in this respository. In the event you discover a security issue, please file a bug.

## Notes
I primarily write these extensions for the benefit of my organization. I attempt to write code as generic as possible so that it can be reused. However, it's certainly possible you may have trouble implementing for your site.

I am not interested in developing a "framework" or using X design methodology. I am open to suggestions, but I prefer keeping the code simple and easy to copy and paste as needed.  Also note that I may be wrong in my approach to "keeping it simple" in some cases, so definitely correct me.
