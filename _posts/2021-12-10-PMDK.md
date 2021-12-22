---
layout: project
permalink: /:title/
category: storage

meta:
  keywords: "PMDK"

project:
  title: "PMDK"
  type: "C++"
  ci_url: "https://travis-ci.org/github/pmem/pmdk"
  url: "pmdk"
  project_official_url: "https://pmem.io/"
  logo: "/assets/images/projects/storage/pmdk/PMDK.png"
  overview: "The Persistent Memory Development Kit (PMDK) is a collection of libraries and tools for System Administrators and Application Developers to simplify managing and accessing persistent memory devices. All PMDK related libraries are described in detail on pmem.io/pmdk."

supported_releases:
  - release:
    version: "v1.11.0"
    url: "https://github.com/pmem/pmdk/releases/tag/1.11.0"

project_ci:
  - CI:
    title: "PMDK Travis CI - Arm64"
    status: "/assets/images/projects/common/CI_status.png"
    url: "https://travis-ci.org/github/pmem/pmdk"

work_items:
  - work:
    title: "PMDK support on Arm64"
    url: "https://linaro.atlassian.net/browse/STOR-24"
    status: "DONE"
  - work:
    title: "Nvdimm device FS DAX support"
    url: "https://linaro.atlassian.net/browse/STOR-42"
    status: "DONE"
  - work:
    title: "fix insufficient flushing on ARMv8.2+"
    url: "https://github.com/pmem/pmdk/pull/5257"
    status: "DONE"
  - work:
    title: "don't vary cacheline size at runtime in rpmem_basic/TEST22"
    url: "https://github.com/pmem/pmdk/pull/5270"
    status: "DONE"
  - work:
    title: "Add HWCAP_DCPOP if not defined to avoid build failure"
    url: "https://github.com/pmem/pmdk/pull/5290"
    status: "DONE"
  - work:
    title: "Ceph RBD Cache with Pmem Backend Integration on Arm64"
    url: "https://linaro.atlassian.net/browse/STOR-25"
    status: "WIP"
  - work:
    title: "Pmem RPMA library enablement and validation"
    url: "https://linaro.atlassian.net/browse/STOR-39"
    status: "WIP"
  - work:
    title: "No support for dc cvac and dc cvap on Arm64"
    url: "https://bugs.kde.org/show_bug.cgi?id=440095"
    status: "WIP"

events:
  - event:
    title: "Linaro Connect LVC21F-203 The Progress for Distributed Storage on Arm64"
    type: "Online Session"
    url: "https://connect.linaro.org/resources/lvc21f/lvc21f-203/"
    language: "English"
  - event:
    title: "Architectural Support for Persistent Memory Programming"
    type: "Online Session"
    url: "https://www.youtube.com/watch?v=8QAuN8CL5Zg"
    language: "English"

---

<p>PMDK</p>
