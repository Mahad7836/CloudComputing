# API Management on Google Cloud

## What is an API?
* **Definition:** Application Programming Interface. A well-defined interface that allows services to communicate.
* **Versioning:** Underlying implementations can change without breaking the interface if versions are managed correctly.
* **REST:** A style/set of constraints for building web services (Representational State Transfer).

## Management Tools

### 1. Cloud Endpoints
* **Description:** Distributed API management system.
* **Features:** Provides an API console, hosting, logging, and monitoring.
* **Benefit:** Makes deploying and managing APIs easier within Google Cloud.

### 2. Apigee
* **Description:** Full lifecycle API management platform.
* **Focus:** Business problems and monetization (selling software services to other companies).
* **Benefit:** Backend services do not need to be in Google Cloud.

## Messaging
# Pub/Sub – Notes

## Overview
- Google Cloud Pub/Sub is a **messaging service**
- Used in the **early stage of data ingestion**
- Data may **not come from a single database**
- **IoT data** is a common example

## Challenges
- Data can be streamed from **many devices**
- Hard to send or distribute data to the **right subscribers**
- Data can arrive **quickly and in high volume**
- Need to ensure **reliable services**

## Publisher–Subscriber Model
- Uses a **publisher–subscriber** pattern
- Publishers send messages
- Subscribers receive messages

## Core Concepts
- **Topic** is the central element of Pub/Sub
- Ensures **at-least-once delivery**

## Features
- **No provisioning required**
- **Open APIs**
- **Global by default**
- Supports: **ingest → read → ingest → visualize**
- Good solution to **buffer changes**
