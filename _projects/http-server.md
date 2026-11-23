---
layout: page
title: HTTP Server
description: Multithreaded HTTP/1.1 server with persistent connections and video range requests.
importance: 2
category: systems
---

Built a multithreaded HTTP/1.1 server from scratch using Python sockets, supporting concurrent clients and persistent connections. Implemented HTTP range requests (`206 Partial Content`) for chunked video delivery and seeking, along with request parsing, response generation, MIME type detection, and file-access controls (`200`, `403`, and `404`).
