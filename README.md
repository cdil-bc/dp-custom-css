# Canvas Custom CSS Manager

A framework for managing Canvas themes and components when using [DesignPLUS by Cidi Labs](https://cidilabs.com/landing/design-tools/) 

This is a lightweight build framework for organizing custom css. It makes it easier to divide large css files into smaller chunks, and it runs a few scripts to manage everything. 

The components directory also has the styles for two components: 
- [a vertical tabs version of the homepage module list](https://github.com/cdil-bc/dp-custom-css/blob/main/src/components/_module-list.css)
- [a sidebar version of the module progress bar](https://github.com/cdil-bc/dp-custom-css/blob/main/src/components/_progress-sidebar.css) 
 
A few people have asked if we could share these after seeing them in the [Boston College Cidilabs Showcase](https://showcase.cidilabs.com/boston-college/), so we're making them available here. 

None of this very currently very well documented or tested outside of our use internally, but if you're brave and want to try it, let us know how it goes. 

Created and maintained by [Tim Lindgren](https://www.bc.edu/content/bc-web/academics/sites/cdil/about/innovation/lindgren.html) in the[Center for Digital Innovation in Learning - Boston College](https://www.bc.edu/content/bc-web/academics/sites/cdil.html) at Boston College. 

--- 

# How To Use 

## Clone or Fork the Repo

Create a local copy for yourself by either cloning the repo or creating a fork (if you want to pull future updates)

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
- **build**: built versions of the styles; uploaded to Canvas when publishing releases
- **src**
  - **archived**: retired themes
  - **base**: utilities used throughout other files
  - **assemble**: file that assemble fragments
  - **custom**: customization to core Canvas css not related to Design Tools
  - **components**: themed Design Tools components and other custom elements
  - **themes**: theme css files

Optional: 
- **design tools**
  - **config**: local copies of the Design Tools configuration pages hosted in the Design Tools Primary Customizations site in each Canvas instance
  - **reference**: copies of default design tools css files for reference
- **dev**: styles.css for local development in Canvas sites, as well as other misc experimental stuff


## Source for NPM Scripts

This repo contains the demo code and files that was used to test NPM scripts for the article [Using Npm Scripts as a Build Tool](https://deliciousbrains.com/npm-build-script/) on [deliciousbrains.com](https://deliciousbrains.com).

