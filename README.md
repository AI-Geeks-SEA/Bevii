# Bevii
repositories for open source development related to Bevii social media platform

## MVP1

## Introduction
Bevii is a social media platform that enables you to control the flow of information and doesn’t act as an arbitrator.

Bevii’s approach to the problem is giving the control back to you rather than being a tech-based moderation. Instead of moderating the content ourselves, we provide the right tools to you to moderate your content.

Using AI, Bevii tags people, persons, organizations, and places associated with various color sentiments.

## web-server
The web-server work is derived from Miguel Grinberg's Microblog work.(https://github.com/miguelgrinberg/microblog)
Please see the HLD documentation in repository to proposed changes. 
Repository: https://github.com/AI-Geeks-SEA/bevii-app

## AI services
The services required to tag images and text and generate image vector. The code is made serverless using fn-project framework. 

## Elastic Search server
Index file required for elastic search is mentioned in HLD. Instructions to setup ElasticSearch will be provided shortly.

## Redis
Every post is sent to Redis queue to call tagging and vector generation API. Thus,  tags will be appear with delay. This compromise is essential to maintain performance.

## MVP2

## Flutter code
The flutter code is to be developed from scratch based on mockup (https://dev.bevii.co/public_htmml/preview.html)

