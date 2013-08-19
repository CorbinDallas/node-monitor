---
layout: page
title: Getting Started
---

# Getting Started

## Introduction

<img style="float:left; margin-right: 10px; height: 100px; width: 150px; border-radius:8px" src="/img/gauge.png">

Node Monitor is a [Node.JS](http://nodejs.org) webapp for monitoring
and controlling Node.JS application servers.  It hosts components assembled onto [dashboards](/pages/dashboards)
you create for visualizing and controlling your systems in real time.

It has built-in components for monitoring process information, application logs
events, business stats, and objects running within a Node.JS process.  A REPL
console lets you log in and inspect your app servers from your desktop.

Designed for extentsion, Node Monitor allows you to write specialized data probes
and visualizations to suit your needs. Module developers can write add-ons for
monitoring and controlling your Node.JS modules.

Let's get started by playing with it on your local workstation.

## Installing Node Monitor

With [Node.JS installed](http://nodejs.org/install) on your workstation,
enter the following:

    $ npm install monitor
    $ npm start monitor

This installs Node Monitor and starts it on the default port 4200.

Now point your browser to
<a href="http://localhost:4200">localhost:4200</a>

## Dashboards

Each page in the Node Monitor site is a dashboard.  You can have as many
dashboards as you like, and you can group them by URL path.
To create a new dashboard, enter a site URL in your browser.  If the page
doesn't exist, Node Monitor asks if you want to create one at that URL.

Is Node monitor still running on your workstation?  This URL probably doesn't exist yet.  Try it:
<a href="http://localhost:4200/testing/gettingStarted">localhost:4200/testing/gettingStarted</a>

For more on dashboards, head over to the [dashboard overview](/pages/overview/dashboards.html) page.

## Tours

## Apps

## Still Reading?