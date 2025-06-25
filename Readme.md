# Show Saver!

Show saver is a peice of software for those who want to make sure it is always on site, in multiple places, and secure.

## The Architecture

Show saver is built on GIT, and uses it's version control in order to easily clone, recreate and back up revisions of show files.

Using a fairly stripped down git server, wrapped in a custom frontend and backend, gives you not only a lot of control over how your show files are handled, but also allows you to link it to some of my other in progress apps.

## The Deployment
At the moment, this is prodominently desgined as a docker deployed app. In this repo will be a docker compose, everything inside is explained in the comments.

It will be possible using configuration to specifiy remote servers, for example using a github server and a standalone remote. This would give you both local syncs and offsite backups.
