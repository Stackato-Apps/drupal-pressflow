# Drupal Demo

This demo installs Drupal Pressflow to HPE Helion Stackato by using 'drush' in
post-staging hooks. The manifest.yml file shows how these are run, and
demonstrates the use of the filesystem service for sharing user content, themes
and modules between application instances.

The 'sites' directory tree is linked to a single mounted filesystem
service, but you can set these up on multiple filesystem services (e.g.
if you wish to share 'sites/all' between multiple sites).

## About Pressflow

Pressflow is a Drupal distribution that provides improved performance and
scalability and which is particularly useful for high traffic sites.

See the [Pressflow Website](http://pressflow.org/) for more details.

## Deploying to HPE Helion Stackato

    stackato push -n

## First Time Setup

    Username: admin
    Password: passwd

## Outgoing Email Support

An external accessible email server is required for full functionality 
of this application. Please see [SMTP Authentication Support Module](http://drupal.org/project/smtp/) 
for more details on configuration.
