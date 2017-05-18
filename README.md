# fcm-webpush-test

## Overview

This repository contains the demonstration of Web Push via Firebase Cloud Messaging and encryption of payloads.

## Web Push payload encryption

Encryption library uses [MartijnDwars/web-push](https://github.com/MartijnDwars/web-push).

## Running the examples

**Set up FCM server key**

```setup shell
(fcm-webpush-test) $ sh ./setup.sh <GCM_SENDER_ID> <FCM_SERVER_KEY>
```

**Run containerss**

```docker-compose shell
(fcm-webpush-test) $ docker-compose up -d
```

**Confirm web server**

Navigate to `http://localhost` and try web push.

## Other

Only latest chrome version(58) has tested. firefox has tested not yet.
