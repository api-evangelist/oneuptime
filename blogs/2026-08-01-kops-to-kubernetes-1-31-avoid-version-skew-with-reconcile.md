---
title: "kOps to Kubernetes 1.31+: Avoid Version Skew with `reconcile cluster`"
url: "https://oneuptime.com/blog/post/2026-08-01-kops-kubernetes-1-31-reconcile-version-skew/view"
date: "2026-08-01"
author: "nawazdhandala"
feed_url: "https://oneuptime.com/blog/rss.xml"
---
Use `kops reconcile cluster` for Kubernetes 1.31+ upgrades so API servers advance before launch configurations can introduce newer kubelets.
