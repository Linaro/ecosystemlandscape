---
layout: project
permalink: /:title/
category: cloud

meta:
  keywords: "OpenStack"

project:
  title: "OpenStack"
  type: "Python"
  ci_url: "https://zuul.opendev.org/t/openstack/status"
  url: "OpenStack"
  project_official_url: "https://www.openstack.org/"
  logo: "/assets/images/projects/cloud/openstack/logo.png"
  overview: "OpenStack is a cloud operating system that controls large pools of compute, storage, and networking resources throughout a datacenter, all managed and provisioned through APIs with common authentication mechanisms. Beyond standard infrastructure-as-a-service functionality, additional components provide orchestration, fault management and service management amongst other services to ensure high availability of user applications."

supported_releases:
  - release:
    version: "Queens"
    url: "https://www.openstack.org/software/queens/"
  - release:
    version: "Rocky"
    url: "https://www.openstack.org/software/rocky/"
  - release:
    version: "Stein"
    url: "https://www.openstack.org/software/stein/"
  - release:
    version: "Train"
    url: "https://www.openstack.org/software/train/"
  - release:
    version: "Ussuri"
    url: "https://www.openstack.org/software/ussuri/"
  - release:
    version: "Victoria"
    url: "https://www.openstack.org/software/victoria/"
  - release:
    version: "Wallaby"
    url: "https://www.openstack.org/software/wallaby/"

project_ci:
  - CI:
    title: "OpenStack Upstream AArch64 CI"
    status: "/assets/images/projects/common/CI_status.png"
    url: "https://zuul.opendev.org/t/openstack/builds?pipeline=check-arm64"

work_items:
  - work:
    title: "[Nova] Support Cpu Compararion on Aarch64 Platform"
    url: "https://review.opendev.org/c/openstack/nova/+/763928"
    status: "WIP"

events:
  - event:
    title: "How Arm is becoming a first class citizen in OpenStack"
    type: "Blog"
    url: "https://superuser.openstack.org/articles/arm-interop-openstack/"
    language: "English"
  - event:
    title: "The Progress for Cloud Computing on Arm Architecture"
    type: "Blog"
    url: "https://superuser.openstack.org/articles/the-progress-for-cloud-computing-on-arm-architecture/"
    language: "English"
  - event:
    title: "OpenStack on ARM64 – Deployment"
    type: "Blog"
    url: "https://cloudbase.it/openstack-on-arm64-part-2/"
    language: "English"
---

<p>OpenStack</p>
