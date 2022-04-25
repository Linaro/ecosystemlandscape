---
layout: project
permalink: /:title/
category: bigdata

meta:
  keywords: "Apache, Hive"

project:
  title: "Apache Hive"
  type: "Java"
  ci_url: "https://ci-hadoop.apache.org/view/Hadoop/job/Hive-trunk-linux-ARM/"
  url: "ApacheHive"
  project_official_url: "http://hive.apache.org/"
  logo: "/assets/images/projects/bigdata/hive/logo.png"
  overview: "The Apache Hive ™ data warehouse software facilitates reading, writing, and managing large datasets residing in distributed storage using SQL. Structure can be projected onto data already in storage. A command line tool and JDBC driver are provided to connect users to Hive."

project_ci:
  - CI:
    title: "Hive Upstream AArch64 CI"
    status: "/assets/images/projects/common/CI_status.png"
    url: "https://ci-hadoop.apache.org/view/Hive/job/Hive-trunk-linux-ARM/"

work_items:
  - work:
    title: "[HIVE-21939] protoc:2.5.0 dependence has broken building on aarch64"
    url: "https://issues.apache.org/jira/browse/HIVE-21939"
    status: "DONE"
  - work:
    title: "[HIVE-23028] Should not use group parameter when run tests in standalone-metastore-common"
    url: "https://issues.apache.org/jira/browse/HIVE-23028"
    status: "DONE"
  - work:
    title: "[HIVE-23163] Class TrustDomainAuthenticationTest should be abstract"
    url: "https://issues.apache.org/jira/browse/HIVE-23163"
    status: "DONE"
  - work:
    title: "[HIVE-23133] Numeric operations can have different result across hardware archs"
    url: "https://issues.apache.org/jira/browse/HIVE-23133"
    status: "DONE"
  - work:
    title: "[HIVE-23134] Hive & Kudu interaction not available on ARM"
    url: "https://issues.apache.org/jira/browse/HIVE-23134"
    status: "DONE"
  - work:
    title: "[HIVE-23233] Using default operation logs location cause hive service session testing failed"
    url: "https://issues.apache.org/jira/browse/HIVE-23233"
    status: "DONE"

---

<p>Apache Hive</p>
