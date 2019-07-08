# About this Repo

This is a fork of the repo for the official Docker image for [nginx](https://registry.hub.docker.com/_/nginx/). See the Hub page for the full readme on how to use the Docker image and for information regarding contributing and issues.

The only difference is in the `mainline/alpine` version that has added a redirect to https if the header `X-Forwarded-Proto:http` is sent with the request.