## Overview

This is an upgrade to philippelt's lhubic library that:
>allow access from python 3 to OVH/Hubic file cloud service using the python swiftclient API binding

It provides support for python 2 and some more error management by raising ```HubicAccessFailure``` (signaling and auth failure not related to credentials) in some cases instead of ```HubicAuthFailure``` (wrongfully implying wrong credentials).

Forked from philippelt's lhubic, see https://github.com/philippelt/lhubic for original README.
