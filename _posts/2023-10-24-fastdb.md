---
layout: project
permalink: /:title/
category: database

meta:
  keywords: "fastdb"

project:
  title: "fastdb"
  type: "C++"
  ci_url: ""
  url: "https://sourceforge.net/projects/fastdb/"
  project_official_url: "http://www.garret.ru/fastdb.html"
  logo: "/assets/images/projects/database/fastdb/fastdb_logo.png"
  overview: "FastDB is a highly efficient main memory database system with realtime capabilities and convenient C++ interface. FastDB doesn't support a client-server architecture and all applications using a FastDB database should run at the same host. FastDB is optimized for applications with dominated read access pattern. High speed of query execution is provided by the elimination of data transfer overhead and a very effective locking implementation. The Database file is mapped to the virtual memory space of each application working with the database. So the query is executed in the context of the application, requiring no context switching and data transfer. Synchronization of concurrent database access is implemented in FastDB by means of atomic instructions, adding almost no overhead to query processing. FastDB assumes that the whole database is present in RAM and optimizes the search algorithms and structures according to this assumption. Moreover, FastDB has no overhead caused by database buffer management and needs no data transfer between a database file and buffer pool. That is why FastDB will work significantly faster than a traditional database with all data cached in buffers pool."

supported_releases:
  - release:
    version: "3.76"
    url: "http://www.garret.ru/fastdb-3.76.tar.gz"
  - release:
    version: "3.75"
    url: "https://sourceforge.net/projects/fastdb/files/fastdb/3.75/fastdb-3.75.tar.gz/download"
  - release:
    version: "3.74"
    url: "https://sourceforge.net/projects/fastdb/files/fastdb/3.74/fastdb-3.74.tar.gz/download"

---

<p>fastdb</p>
