---
title: Installation
---
Installing Bolt
===============

This page explains the various ways of installing Bolt. You can either use the
command-line or your FTP-client to install it. There are different methods to
install Bolt, but we recommend **Composer-based distribution**, as the fastest way to get an
installation of Bolt up and running.

<a href="composer-based-distribution" class="button large expand docsintro">
Composer-based distribution <br> <small>Quickly set up a Bolt installation,
making use of the command line and the official distribution files</small> </a>

Additionally, there are several installation options that suit any preferred workflow:

  - **The traditional way**: Downloading the distribution file, in order to
    manually extract and upload [using (S)FTP][sftp].
  - **The 'Create Project' way**: Using `composer create-project` or by creating
    your own `composer.json` file. See [Composer create-project][create-project].
  - **Integrating in your project**: To bootstrap the Bolt application in code,
    integrating it completely in an existing project, see [Creating your own
    Bootstrap][custom-bootstrap].

Use one of the four methods described above to get the Bolt source files, and
set them up on your web server. After you've done this, skip to the section for
[Setting up Bolt ][configuration].

[sftp]: install-sftp
[create-project]: composer-create-project/install-composer
[custom-bootstrap]: ../extensions/custom-bootstrapping
[configuration]: ../configuration/introduction
