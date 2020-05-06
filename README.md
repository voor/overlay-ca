# Overlay CA Certificate into existing containers.

This is a simple POC to show how you can use `ytt` to overlay a Certificate Authority bundle into an existing application.  

**This overrides the current bundle in the container, so you must make sure to contain public trust certs in this bundle.**

