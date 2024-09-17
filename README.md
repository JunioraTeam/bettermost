# Bettermost [![CircleCI branch](https://img.shields.io/circleci/project/github/JunioraTeam/bettermost/master.svg)](https://circleci.com/gh/JunioraTeam/bettermost)

This plugin applies some styles to Mattermost.

This repository is based on
[mattermost-plugin-starter-template](https://github.com/mattermost/mattermost-plugin-starter-template).

## Features

- Hide the navigation bar "Free Edition" badge
- Hide "This is the free unsupported edition of Mattermost." message from the main menu in Mattermost Community Edition
- Hide timezone information message from the chat box
- Change user custom status message font to [Vazirmatn](https://github.com/rastikerdar/vazirmatn) (requires [Mattermost Vazirmatn plugin](https://github.com/QueraTeam/mattermost-vazirmatn))

## Installation

Download the plugin file (`ir.juniora.bettermost-*.tar.gz`) from the
[Releases](https://github.com/JunioraTeam/bettermost/releases)
page and upload to your Mattermost  server via **System Console**.

## Development, Build

    make
