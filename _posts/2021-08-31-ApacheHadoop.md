---
layout: project
permalink: /:title/
category: bigdata

meta:
  keywords: "Apache, Hadoop"

project:
  title: "Apache Hadoop"
  type: "Java"
  ci_url: "https://ci-hadoop.apache.org/view/Hadoop/job/hadoop-qbt-linux-ARM-trunk/"
  url: "ApacheHadoop"
  project_official_url: "http://hadoop.apache.org/"
  logo: "/assets/images/projects/bigdata/hadoop/logo.png"
  overview: "The Apache™ Hadoop® project develops open-source software for reliable, scalable, distributed computing. The Apache Hadoop software library is a framework that allows for the distributed processing of large data sets across clusters of computers using simple programming models. It is designed to scale up from single servers to thousands of machines, each offering local computation and storage. Rather than rely on hardware to deliver high-availability, the library itself is designed to detect and handle failures at the application layer, so delivering a highly-available service on top of a cluster of computers, each of which may be prone to failures."

supported_releases:
  - release:
    version: "3.3.0"
    url: "https://www.apache.org/dyn/closer.cgi/hadoop/common/hadoop-3.3.0/hadoop-3.3.0-aarch64.tar.gz"
  - release:
    version: "3.3.1"
    url: "https://www.apache.org/dyn/closer.cgi/hadoop/common/hadoop-3.3.1/hadoop-3.3.1-aarch64.tar.gz"

project_ci:
  - CI:
    title: "Hadoop Upstream AArch64 CI"
    status: "/assets/images/projects/common/CI_status.png"
    url: "https://ci-hadoop.apache.org/view/Hadoop/job/hadoop-qbt-linux-ARM-trunk/"

user_stories:
  - story:
    logo: "/assets/images/projects/user_story_logos/kunpeng.png"
    title: "Kunpeng BoostKit for Big Data"
    discription: "Kunpeng BoostKit for Big Data addresses issues such as low query efficiency and difficult component performance tuning. It provides open source enablement and tuning guides for major big data components, basic acceleration software packages for smart I/O prefetch and Chinese cryptographic encryption and decryption, application acceleration software packages for machine learning and graph analysis algorithms, and open the openLooKeng cross-source and cross-domain query engine. This improves the big data analysis efficiency and maximizes the computing performance. "
    url: "https://www.hikunpeng.com/en/developer/boostkit/big-data"
  - story:
    logo: "/assets/images/projects/user_story_logos/china-telecom.png"
    title: "Jiangsu Telecom run BigData on Kunpeng"
    discription: "Jiangsu Telecom big data platform carries the operation data, storage and analysis of all production systems of Jiangsu Telecom. It is one of the core business systems and has high requirements for computing performance, concurrent processing capacity and operation stability. After many scheme demonstrations and performance test evaluations, Jiangsu Telecom finally chose Huawei Taishan server based on Kunpeng(Aarch64) processor and open source Hadoop software to build a big data platform. After the platform was launched, it operated stably and significantly improved the business efficiency of Jiangsu Telecom."
    url: "https://www.huawei.com/cn/news/2019/7/jiangsu-telecom-big-data-kunpeng"
    language: "Chinese"

work_items:
  - work:
    title: "[HADOOP-16614] Missing leveldbjni package of aarch64 platform"
    url: "https://issues.apache.org/jira/browse/HADOOP-16614"
    status: "DONE"
  - work:
    title: "[YARN-10042] Upgrade grpc-xxx depdencies to 1.26.0"
    url: "https://issues.apache.org/jira/browse/YARN-10042"
    status: "DONE"
  - work:
    title: "[YARN-9898] Dependency netty-all-4.1.27.Final doesn't support ARM platform"
    url: "https://issues.apache.org/jira/browse/YARN-9898"
    status: "DONE"

events:
  - event:
    title: "Linaro Connect 21: Boosting Application Performance on Arm Data Centers"
    type: "Online Session"
    url: "https://connect.linaro.org/resources/lvc20/lvc20-303"
    language: "English"
  - event:
    title: "Linaro Connect 20: State of Big Data and Data Science on Arm"
    type: "Online Session"
    url: "https://connect.linaro.org/resources/lvc20/lvc20-303"
    language: "English"
---

<p>Apache Hadoop</p>
