# LittleFSConfig

## Introduction

LittleFSConfig is an Arduino library for reading settings from a configuration file on LittleFS filesystem.

It is based in SDConfigFile library by Bradford Needham (https://github.com/bneedhamia/sdconfigfile)

Given a configuration file with settings whose format is:

    # for comments
    setting=value

    # this is an example

    # for any string
    setting1=some_string
    # able to be parsed as a boolean
    setting2=true
    # able to be parsed as an integer
    setting3=123
    # able to be parsed as an IP address
    setting4=10.1.1.2

It is necessary to specify the configuration file name (i.e. **config.cfg**) to load its contents through the library methods.
