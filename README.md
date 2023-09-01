# Aeroscan

## United Sciences

### Companies
- Kickr Design
- Baires Dev

### Target Architecture
NXP i.MX8M Plus Quad, quad-core ARM Cortex-A53, 1.8GHz  
[Specs Page](https://www.compulab.com/products/computer-on-modules/ucm-imx8m-plus-nxp-i-mx-8m-plus-som-system-on-module-computer/#specs)

## Balena OS
For more information on Balena OS, please refer to the [official documentation](https://balena.io/).

### Balena Setup & Deployment

To get this project up and running, you will need to signup for a balena account [here][signup-page] and set up an application and device. You'll find full details in our [Getting Started tutorial][gettingStarted-link].

Once you have downloaded this project, you can `balena push` it using the [balenaCLI][balena-cli]. This command will package up and push the code to the balena builders, where it will be compiled and built and deployed to every device in the application fleet. When it completes, you'll have your C code running on your device and see some logs on your [balenaCloud dashboard][balena-dashboard].

After downloading, navigate to the directory and run the balena push command using the balena CLI. This command will package up and push the code to the balena builders, where it will be compiled, built and deployed to every device in the fleet.
```bash
balena push jjowers/aeroscan
```

### Contributers
Jason Hejna  
Email: [jhejna@kickrdesign.com](mailto:jhejna@kickrdesign.com)

Feel free to add or modify any sections as needed!

[balena-link]:https://balena.io/
[open-jdk]:https://balena.io/docs/reference/base-images/base-images/#OpenJDK
[signup-page]:https://dashboard.balena-cloud.com/signup
[gettingStarted-link]:http://balena.io/docs/learn/getting-started/
[balena-cli]:https://www.balena.io/docs/reference/cli/
[balena-dashboard]:https://dashboard.balena-cloud.com/