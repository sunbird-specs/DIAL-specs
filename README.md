# DIAL Specs

__DIAL__ stands for ***"Digital Infrastructure for Augmented Learning"***. This repository provides the DIAL URL and Resorce Descriptor Schema specifications for various learning resources that are DIAL coded. This specification is extensively used in [Sunbird-ED](https://ed.sunbird.org/) which is the base for India's widely adopted [DIKSHA platform](https://diksha.gov.in). 

As part of DIKSHA, billions national and state textbook topics are QR coded using these specifications and are available for anyone who is creating learning apps to provide personalized learning experience to the user.

## Introduction

An open source framework for codifying (providing IDs) and linking physical learning resources such as textbooks with online resources in a dynamic and extensible manner using QR codes, AR, Voice navigation, etc. In countries like India, mainstream learning is heavily based on printed textbooks and materials. To provide digital learning experiences to children, it is essential that the physical to digital transition be made seamless and relevant. Current approach is to hard code specific video or learning material link to textbooks through QR codes. This assumes that the content online is not changing and also the content is provided only by that specific provider. This framework solves that problem by decoupling the identity/code of physical items with its metadata and by allowing different applications to respond differently based on the metadata (e.g. when scanning, one application may show related videos while other show practice material).

## Features

1. Flexible codification for easy printing by publishers
2. Ability to use an online code/ID registry with resource descriptor metadata
3. Ability to codify any physical learning resource
4. Ability for any app to scan, obtain metadata, and provide personalized learning experience to users
5. Already massively used across India with billions of DIAL QR codes already in cirulation

