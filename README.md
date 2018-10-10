This site keeps track of the currently supported Kubernetes version(s) across notable distributions. We try to update it at least after every minor Kubernetes upstream release, that is, for example, 1.11 to 1.12. Note that if you happen to be responsible for one of the below listed distributions and spot an inaccuracy, please PR this page or raise an issue so that we can get it fixed. Also, new additions are welcome.

> The current Kubernetes version, as of 2018-09-27, is [1.12](https://github.com/kubernetes/kubernetes/releases/tag/v1.12.0).

In alphabetical order, the current supported version in the Kubernetes distributions—with `SLO` being the _Service Level Objective_, put in other words the goal to hit and `Type` as per CNCF's [Certified Kubernetes Conformance Program](https://github.com/cncf/k8s-conformance/blob/master/instructions.md)—are:

Distribution  | Current  | Valid as of  | SLO      | Type
------------- | -------- | ------------ | -------- | --------
Azure Kubernetes Service [AKS](https://docs.microsoft.com/en-us/azure/aks/supported-kubernetes-versions) | 1.9 (1.10)<sup>A</sup>  | 2018-09-21 | 30 days after upstream, subject to the stability of the release | hosted
Amazon Elastic Container Service for Kubernetes [EKS](https://docs.aws.amazon.com/eks/latest/userguide/platform-versions.html) | 1.10 |  ?  | No SLO or public plans re upgrades | hosted
Google Kubernetes Engine [GKE](https://cloud.google.com/kubernetes-engine/release-notes) |  1.10 (1.11)<sup>B</sup> | 2018-09-18 | See [versioning and upgrades](https://cloud.google.com/kubernetes-engine/versioning-and-upgrades) docs | hosted
[OKD](https://docs.okd.io/latest/welcome/index.html) | 1.11 | 2018-10-10 | bound to upstream release cycle, one version behind to fix known post-release issues | vendor
Red Hat [OpenShift Online Starter](https://www.openshift.com/products/online/) | 1.11 | 2018-10-05 | same as OKD | hosted

Notes:

(A) While 1.9 is the default, 1.10 is available via a safe, staged rolling upgrade.
(B) While 1.10 is the default, 1.11 is available for whitelisted early-access users.

For a complete list, covering all certified Kubernetes distributions, see the [Kubernetes Distributions & Platforms](https://docs.google.com/spreadsheets/d/1LxSqBzjOxfGx3cmtZ4EbB_BGCxT_wlxW_xgHVVa23es/) list maintained by CNCF.

_You might be wondering why the FQDN of this site is `sup.kubernetes.sh` … well, the cool kids these day don't say "What's up" but "sup", for short. Since this site is all about what's currently up (and available) in Kubernetes distros, I thought this is an appropriate name. Yeah, I know, Michael should really not be allowed to name things ;)_