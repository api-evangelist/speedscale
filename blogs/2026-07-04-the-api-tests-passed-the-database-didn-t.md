---
title: "The API tests passed. The database didn't."
url: "https://speedscale.com/blog/compare-sql-between-runs/"
date: "2026-07-04"
author: "Matthew LeRay"
feed_url: "https://speedscale.com/rss.xml"
---
Our v2 release looked clean in HTTP tests until we diffed the SQL workload — an N+1 loop, a startup migration, and 70 ms of extra DB time hiding in plain sight. Here's how to compare two releases without database access.
