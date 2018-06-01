# nuxtjs-node6
Re-packaged nuxt.js for running in a node6 environment

see https://nuxtjs.org/

Install this instead of nuxt.js, using the equivalent version number
and then your nuxt commands will run on node6.

This is particularly useful for running in AWS Lambda, which currently
only support node 6.10 as its most recent supported version

# NOTE

The latest build of nuxt-edge supports Node 6.x again by automatically falling back to legacy dist. Useful for Google Cloud Functions users. 
