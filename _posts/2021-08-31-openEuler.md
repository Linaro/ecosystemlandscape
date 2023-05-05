---
layout: project
permalink: /:title/
category: os

meta:
  keywords: "openEuler"

project:
  title: "openEuler"
  type: "C"
  ci_url: "https://openeulerjenkins.osinfra.cn/job/multiarch/job/openeuler"
  url: "https://www.openeuler.org/"
  project_official_url: "https://www.openeuler.org/"
  logo: "/assets/images/projects/os/openeuler/logo.png"
  overview: "The openEuler kernel is the core of the openEuler OS, serving as the foundation of system performance and stability and a bridge between processors, devices, and services."

supported_releases:
  - release:
    version: "openEuler 22.09"
    url: "https://repo.openeuler.org/openEuler-22.09/"
  - release:
    version: "openEuler 21.09"
    url: "https://repo.openeuler.org/openEuler-21.09/"
  - release:
    version: "openEuler 21.03"
    url: "https://repo.openeuler.org/openEuler-21.03/"
  - release:
    version: "openEuler 20.09"
    url: "https://repo.openeuler.org/openEuler-20.09/"

project_ci:
  - CI:
    title: "openEuler aarch64 CI"
    status: "/assets/images/projects/common/CI_status.png"
    url: "https://openeulerjenkins.osinfra.cn/job/multiarch/job/openeuler/job/aarch64/job/kernel/"

work_items:
  - work:
    title: "Support the feature of querying stats"
    url: "https://gitee.com/openeuler/kernel/pulls/427"
    status: "WIP"
  - work:
    title: "ACPI: Add Platform Runtime Mechanism(PRM) feature support"
    url: "https://gitee.com/openeuler/kernel/pulls/413/files"
    status: "DONE"

events:
  - event:
    title: "openEuler TechDay Invitation"
    type: "Blog"
    url: "https://www.openeuler.org/en/blog/openeuler-techday/openEuler%20TechDay%20Invitation.html"
    language: "English"
  - event:
    title: "TBOX Installation and Operation on openEuler"
    type: "Blog"
    url: "https://www.openeuler.org/en/blog/zihao/TBOX%20Installation%20and%20Operation%20on%20openEuler.html"
    language: "English"
---

<p>openEuler</p>
