# node-load-tweet
## Dependencies
    npm install ntwitter
## Configure
* Rename cofig_example.js to config.js
* Add your Twitter keys to the conf.js file
* Populate (or not) exports.prepend_status_content and exports.append_status_content
## Usage
* I like to use forever with some logging to keep it up and running

    forever start -l forever.log -ao out.log -ae err.log app.js