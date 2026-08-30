---
title: "How to Split Read and Write Traffic Safely in a Patroni Cluster"
url: "https://oneuptime.com/blog/post/2026-08-30-how-to-split-read-and-write-traffic-in-a-patroni-cluster-without-sending-writes-to-a-replica/view"
date: "2026-08-30"
author: "nawazdhandala"
feed_url: "https://oneuptime.com/blog/rss.xml"
---
Expose separate Patroni-aware PostgreSQL write and read endpoints, enforce role checks, and keep replica lag and read-after-write behavior explicit.
