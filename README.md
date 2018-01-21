# Firebase Config for Studio Slackr Project

See web console
<https://console.firebase.google.com/u/0/project/studio-slackr/database/studio-slackr/data>

See expected database schema at
<https://github.com/ScriptEdcurriculum/studio_slackr_starter>

## Set Up

    npm i -g firebase-tools

    cd functions && npm i

## Deploy database rules

    firebase deploy --only database

## Reset database to initial data

_Note this overrides *all* data in the firebase database._

    firebase database:set / database.json

## Deploy functions

    firebase deploy --only functions
