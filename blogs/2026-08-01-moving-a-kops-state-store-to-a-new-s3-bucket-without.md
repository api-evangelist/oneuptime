---
title: "Moving a kOps State Store to a New S3 Bucket Without Stranding Existing Nodes"
url: "https://oneuptime.com/blog/post/2026-08-01-move-kops-state-store-new-s3-bucket/view"
date: "2026-08-01"
author: "nawazdhandala"
feed_url: "https://oneuptime.com/blog/rss.xml"
---
Move a kOps cluster to a new S3 state bucket by copying its complete prefix, changing `configBase`, updating cloud resources, and retaining a tested rollback path.
