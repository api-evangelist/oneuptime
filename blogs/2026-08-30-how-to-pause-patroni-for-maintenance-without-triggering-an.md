---
title: "How to Pause Patroni for Maintenance Without Triggering an Accidental Failover"
url: "https://oneuptime.com/blog/post/2026-08-30-how-to-pause-patroni-for-maintenance-without-triggering-an-accidental-failover/view"
date: "2026-08-30"
author: "nawazdhandala"
feed_url: "https://oneuptime.com/blog/rss.xml"
---
Put a Patroni cluster into maintenance mode, verify every expected running member has observed the pause, fence any member that cannot be verified, perform controlled work, and resume safely.
