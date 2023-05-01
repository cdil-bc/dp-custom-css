# Boston College Canvas Themes and UI

- Themes and components for [DesignPLUS by Cidi Labs](https://cidilabs.com/landing/design-tools/)
- Managed using PostCSS

## Install

To get up and running install the required packages:

```
npm install
```

## Building
Run to build full css files for releases:
```
npm run build
```

## Project Structure
- **assets**: copy of theme assets that are served from http://cte.bc.edu
- **build**: built versions of the styles; uploaded to ITS Bitbucket repo when publishing releases
- **design tools**
  - **config**: local copies of the Design Tools configuration pages hosted in the Design Tools Primary Customizations site in each Canvas instance
  - **reference**: copies of default design tools css files for reference
- **dev**: styles.css for local development in Canvas sites, as well as other misc experimental stuff
- **src**
  - **archived**: retired themes
  - **assemble**: file that assemble fragments
  - **custom**: customization to core Canvas css not related to Design Tools
  - **components**: themed Design Tools components and other custom elements
  - **themes**: theme css files
  - **design-tools-default**: default DT stylesheet, version headers for global and mobile stylesheets 

## Source for NPM Scripts

This repo contains the demo code and files that was used to test NPM scripts for the article [Using Npm Scripts as a Build Tool](https://deliciousbrains.com/npm-build-script/) on [deliciousbrains.com](https://deliciousbrains.com).

