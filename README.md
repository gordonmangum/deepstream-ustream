# Ustream Microservice

## About

This is a meteor microservice connected to from https://github.com/gordonmangum/Deepstream using https://github.com/arunoda/meteor-up

## Setup

Clone the repo. Add a mup.json and a settings.json to the root folder, alter the app path in mup.json to you local configuration.

Run `npm install -g mupx` to install mupx and then you can see what has been happening remotely with `mupx logs`. Remember to pass a `--tail 150` flag to the command to save being overrun with logs.
