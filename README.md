# swerve
An OCI / Docker container registry v2 endpoint that redirects (not proxy) to actual registries

# Purpose

The purpose of swerve is to be reused so that you uBlue and uBlue-derived custom images can run a vanity domain of their choice while proxying the actual traffic back to github. This also allows the owner of the domain to not have to depend on a single registry. 
