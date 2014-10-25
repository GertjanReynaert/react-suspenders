React-Suspenders
======
Project setup to easily start creating a Reactjs component, or app

## Setup

Currently there is no installer available, so just unzip the zip file and rename
the folder to your project name

run `npm install`

run `broccoli serve`

## Contributing
Pull requests are very much welcome

## Folder structure

- app

  contains all js files. these will be concatenated, but not minified, you can
achieve this by adding another build step in the brocfile

  - react

    contains all react files. You can use .js or .jsx file extensions, and they
will both be precompiled to valid javascript, before they get concatenated to
the other js files

- public

  contains all files that just need to be copied, in general assets like images
and fonts, also the index.html

- styles

  contains all styles
  the precompiler will compile and autoprefix all files that are imported in
app.less
  currently LESS support only
