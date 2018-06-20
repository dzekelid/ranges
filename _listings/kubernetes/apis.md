---
name: Kubernetes
x-slug: kubernetes
description: Manage a cluster of Linux containers as a single system to accelerate
  Dev and simplify Ops. Kubernetes is an open source orchestration system for Docker
  containers. It handles scheduling onto nodes in a compute cluster and actively manages
  workloads to ensure that their state matches the users declared intentions. Using
  the concepts of labels and pods, it groups the containers which make up an application
  into logical units for easy management and discovery.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/kubernetes-logo.png
x-kinRank: "8"
x-alexaRank: "0"
tags: Ranges
created: "2018-06-20"
modified: "2018-06-20"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/ranges/master/_listings/kubernetes/apis.md
specificationVersion: "0.14"
apis:
- name: Kubernetes Get Limitranges
  x-api-slug: kubernetes
  description: List objects of kind limitrange.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/kubernetes-logo.png
  humanURL: http://kubernetes.io/
  baseURL: :///api/v1beta3/127.0.0.1:6443//api/v1beta3/limitranges
  tags: Limitranges
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/ranges/master/_listings/kubernetes/apiv1beta3limitranges-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/ranges/master/_listings/kubernetes/apiv1beta3limitranges-get-openapi.md
- name: Kubernetes Get Namespaces Limitranges
  x-api-slug: kubernetes
  description: List objects of kind limitrange.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/kubernetes-logo.png
  humanURL: http://kubernetes.io/
  baseURL: :///api/v1beta3/127.0.0.1:6443//api/v1beta3/namespaces/{namespaces}/limitranges
  tags: Namespaces,Limitranges
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/ranges/master/_listings/kubernetes/apiv1beta3namespacesnamespaceslimitranges-get-openapi.md
- name: Kubernetes Post Namespaces Limitranges
  x-api-slug: kubernetes
  description: Create a limitrange.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/kubernetes-logo.png
  humanURL: http://kubernetes.io/
  baseURL: :///api/v1beta3/127.0.0.1:6443//api/v1beta3/namespaces/{namespaces}/limitranges
  tags: Namespaces,Limitranges
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/ranges/master/_listings/kubernetes/apiv1beta3namespacesnamespaceslimitranges-post-openapi.md
- name: Kubernetes Delete Namespaces Limitranges Name
  x-api-slug: kubernetes
  description: Delete a limitrange.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/kubernetes-logo.png
  humanURL: http://kubernetes.io/
  baseURL: :///api/v1beta3/127.0.0.1:6443//api/v1beta3/namespaces/{namespaces}/limitranges/{name}
  tags: Namespaces,Limitranges,Name
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/ranges/master/_listings/kubernetes/apiv1beta3namespacesnamespaceslimitrangesname-delete-openapi.md
- name: Kubernetes Get Namespaces Limitranges Name
  x-api-slug: kubernetes
  description: Read the specified limitrange.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/kubernetes-logo.png
  humanURL: http://kubernetes.io/
  baseURL: :///api/v1beta3/127.0.0.1:6443//api/v1beta3/namespaces/{namespaces}/limitranges/{name}
  tags: Namespaces,Limitranges,Name
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/ranges/master/_listings/kubernetes/apiv1beta3namespacesnamespaceslimitrangesname-get-openapi.md
- name: Kubernetes Put Namespaces Limitranges Name
  x-api-slug: kubernetes
  description: Update the specified limitrange.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/kubernetes-logo.png
  humanURL: http://kubernetes.io/
  baseURL: :///api/v1beta3/127.0.0.1:6443//api/v1beta3/namespaces/{namespaces}/limitranges/{name}
  tags: Namespaces,Limitranges,Name
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/ranges/master/_listings/kubernetes/apiv1beta3namespacesnamespaceslimitrangesname-put-openapi.md
- name: Kubernetes Get Watch Limitranges
  x-api-slug: kubernetes
  description: Watch a list of limitrange.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/kubernetes-logo.png
  humanURL: http://kubernetes.io/
  baseURL: :///api/v1beta3/127.0.0.1:6443//api/v1beta3/watch/limitranges
  tags: Watch,Limitranges
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/ranges/master/_listings/kubernetes/apiv1beta3watchlimitranges-get-openapi.md
- name: Kubernetes Get Watch Namespaces Limitranges
  x-api-slug: kubernetes
  description: Watch a list of limitrange.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/kubernetes-logo.png
  humanURL: http://kubernetes.io/
  baseURL: :///api/v1beta3/127.0.0.1:6443//api/v1beta3/watch/namespaces/{namespaces}/limitranges
  tags: Watch,Namespaces,Limitranges
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/ranges/master/_listings/kubernetes/apiv1beta3watchnamespacesnamespaceslimitranges-get-openapi.md
- name: Kubernetes Get Watch Namespaces Limitranges Name
  x-api-slug: kubernetes
  description: Watch a particular limitrange.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/kubernetes-logo.png
  humanURL: http://kubernetes.io/
  baseURL: :///api/v1beta3/127.0.0.1:6443//api/v1beta3/watch/namespaces/{namespaces}/limitranges/{name}
  tags: Watch,Namespaces,Limitranges,Name
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/ranges/master/_listings/kubernetes/apiv1beta3watchnamespacesnamespaceslimitrangesname-get-openapi.md
- name: Kubernetes
  x-api-slug: kubernetes
  description: Manage a cluster of Linux containers as a single system to accelerate
    Dev and simplify Ops. Kubernetes is an open source orchestration system for Docker
    containers. It handles scheduling onto nodes in a compute cluster and actively
    manages workloads to ensure that their state matches the users declared intentions.
    Using the concepts of labels and pods, it groups the containers which make up
    an application into logical units for easy management and discovery.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/kubernetes-logo.png
  humanURL: http://kubernetes.io/
  baseURL: :///api/v1beta3/127.0.0.1:6443
  tags: Ranges
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/ranges/master/_listings/kubernetes/openapi.md
x-common:
- type: x-blog
  url: http://blog.kubernetes.io/
- type: x-blog-rss
  url: http://blog.kubernetes.io/feeds/posts/default
- type: x-github
  url: https://github.com/kubernetes
- type: x-twitter
  url: https://twitter.com/kubernetesio
- type: x-website
  url: http://kubernetes.io/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---