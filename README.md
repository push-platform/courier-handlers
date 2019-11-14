# Courier-Handlers

# About

Courier-Handlers is a project designed to the creation of new Channels to Courier, a GoLang service that enables trading
messages in Push Platform as well as RapidPro.

Currently, Courier supports over 36 different channel types, and this project came in clutch to help creating them out.
The goal of Courier is to support the most various channel types that can be used, from SMS to Facebook.

# Configuration

It is recommended that either RapidPro or Push Platform are ready to run in your computer, so there is a link [here](https://rapidpro.github.io/rapidpro/docs/development/) that will guide you on how to run RapidPro locally.

The new channels folder must already be finished and ready to run.

# How to use it

    1. Clone the Courier project (https://github.com/Ilhasoft/courier) to your computer;
    2. Clone the Courier-Handlers project (https://github.com/push-platform/courier-handlers) to the root of Courier;
    3. cd into Courier-Handlers/add-channel-script folder and type the command ./add_channel.sh;
    4. Now, the new channels that you have created should already work with Courier.

This script will only work if you have cloned the new channels to a specific folder in Courier (courier/handlers)