# swerve
An OCI / Docker container registry v2 endpoint that redirects (not proxy) to actual registries

# Purpose

The purpose of swerve is to be reused so that uBlue and uBlue-derived custom images can run a vanity domain of their choice while proxying the actual traffic back to a registry (currently only ghcr.io). 

This gives the owner of the domain the freedom to not depend on any one registry. 
