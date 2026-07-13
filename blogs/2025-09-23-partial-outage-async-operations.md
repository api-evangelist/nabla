---
title: "Partial outage: async operations"
url: "https://status.nabla.com/incidents/cmcm5r3md072"
date: "2025-09-23"
feed_url: "https://status.nabla.com/history.atom"
---
Sep 23 , 14:15 UTC Resolved - (As explained in the message above, the situation resolved in under 10' with the end of our deployment). Sep 23 , 14:14 UTC Identified - Our service suffered a partial outage for all async operations during our routine deployment today. Start: 2025-09-23 15:47:41.939 UTC+2 End: 2025-09-23 15:56:09.602 UTC+2 During that time, all endpoints starting async operations (like a note generation) had a chance to immediately fail with an HTTP 500.
