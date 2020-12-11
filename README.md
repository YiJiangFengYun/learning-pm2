# learning-pm2

A repository of learning pm2.

## pm2 deploy ecosystem.json production setup

This command used to clone repository to work directory.

## pm2 deploy ecosystem.json production deploy

This command used to sync repository and execute post-deploy (deploy app)

## pm2 deploy ecosystem.json production update

This command used to sync repository and execute post-deploy (deploy app) as deploy command above.
This command will record deploy commit information. Then you can use commands curr, prev and list to
operate on commits that used to deploy.

## pm2 deploy ecosystem.json production exec "pm2 reload all"

Execute command on remote machines
