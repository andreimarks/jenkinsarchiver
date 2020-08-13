# jenkinsarchiver
Script for archiving Jenkins build information via the Jenkins REST API.

This is a pretty limited purpose script, and a big TODO is for me to write the relevant stuff in Groovy so this doesn't even really have to go through the REST api call by call.

Partially written to archive build data to analyze performance and history of builds at my company. Also partially written to work on my Python since it's not my day job.

# TODO
* Structure like a big boy module.
* Output to sane data format (i.e. a real database)
* Convert relevant parts to Groovy.
