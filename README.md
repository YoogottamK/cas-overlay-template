# CAS
Make sure you are on the 5.3 branch

## How to modify
 - Run it once to generate `/etc/cas` directory
 - Now, copy over the `cas.properties` file
 - **NOTE** All these commands require root
 - `./build.sh`. This will create a `target` directory at the project root
 - Identify which files you need to edit. Copy only those files from `target/cas/WEB-INF/classes/` to `src/main/resources`.
 - css,js files can be found in `target/cas/WEB-INF/classes/static`
 - html files can be found in `target/cas/WEB-INF/classes/templates`
 - Once done with editing, `./build.sh` again

## Other points to note
 - be connected to vpn and add iiit nameserver
