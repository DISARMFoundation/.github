# DISARM Foundation GitHub

The framework, STIX and navigator repositories belong together: the framework repo hosts the framework master files and web pages, the STIX repo hosts the STIX generator and bundle, and the navigator repos host the code to present the framework matrix and associated web pages via a fork of the MITRE ATT&CK Navigator. 

All repositories follow the same **versioning** scheme based on the version of the framework: tools do not have their own independent versions, they track the framework version instead. The Foundation publishes a “dot version” (for example v1.n) when it has significant updates to the framework, and “patch commits” for bug fixes; v1.n.0 is the first release of version 1.n, which is then stabilised through patch commits until v1.n.1 becomes the stable release for that version.

---

## Legacy (versions 1.0–1.6)

These repositories support the original DISARM 1.x framework releases up to, and including, 1.6.

| Repository | Purpose (short) | Framework focus |
|-----------|-----------------|-----------------|
| [`DISARMframeworks`](https://github.com/DISARMFoundation/DISARMframeworks) | Master copies of DISARM 1.x frameworks and generated files for exploration and exports. | 1.0–1.6 (core) |
| [`DISARM-STIX2`](https://github.com/DISARMFoundation/DISARM-STIX2) | STIX 2 generator and bundle for the DISARM 1.x framework. | 1.0–1.3 (legacy) |
| [`disarm-navigator`](https://github.com/DISARMFoundation/disarm-navigator) | Web app for navigating and annotating DISARM 1.x matrices (fork of ATT&CK Navigator). | 1.0–1.6 |
| [`DISARMWordPlugIn`](https://github.com/DISARMFoundation/DISARMWordPlugIn) | Experimental Microsoft Word plug‑in written in VBA to tag reports using DISARM 1.x. | 1.2–1.4 (legacy) |
| [`DISARM Add-In for Word`](https://github.com/Digiqal-development/disarm-dev) | Official DISARM Add-In for Microsoft Word written in JavaScript to tag reports using DISARM 1.x. Available in the [Microsoft Office Store](https://marketplace.microsoft.com/et-ee/product/saas/wa200008045)  | 1.2–1.6 |
| [`DISARMexplorer`](https://github.com/DISARMFoundation/DISARMexplorer) | Experimental Flask/Python/D3 site for exploring DISARM framework objects and relationships. | 1.0-1.2 (legacy) |

---

## Fact Checking (version 1.7)

These repositories capture the DISARM 1.7 update, which added techniques most relevant to fact checkers.

| Repository | Purpose (short) | Framework focus |
|-----------|-----------------|-----------------|
| [`DISARMframeworks-17`](https://github.com/DISARMFoundation/DISARMframeworks-17) | Framework data for DISARM 1.7, including additional techniques for fact checkers. | 1.7 framework |
| [`disarm-stix-17`](https://github.com/DISARMFoundation/disarm-stix-17) | STIX 2 bundle and related code for the DISARM 1.7 framework and fact‑checking use cases. | 1.7 STIX |
| [`disarm-navigator-17`](https://github.com/DISARMFoundation/disarm-navigator-17) | Navigator app configured for the DISARM 1.7 red framework and fact‑checker update. | 1.7 navigator |


---

## Next Generation (version 2.0)

These repositories implement and support prototypes of the DISARM 2.0 Observations framework and navigator support for multiple versions of DISARM including 1.x and 2.x.

| Repository | Purpose (short) | Framework focus |
|-----------|-----------------|-----------------|
| [`DISARMframeworks-20-observable`](https://github.com/DISARMFoundation/DISARMframeworks-20-observable) | Master copies of the DISARM 2.0 Observations framework, plus generated files for exploring the data. | 2.0 Observations |
| [`disarm-stix-20-observable`](https://github.com/DISARMFoundation/disarm-stix-20-observable) | STIX 2 bundle and related code for the DISARM 2.0 Observations framework. | 2.0 Observations |
| [`disarm-navigator-20-observable`](https://github.com/DISARMFoundation/disarm-navigator-20-observable) | Navigator web app for navigating and annotating the DISARM 2.0 Observations matrix. | 2.0 Observations |
| [`disarm-navigator-mv`](https://github.com/DISARMFoundation/disarm-navigator-mv) | Navigator variant for supporting multiple DISARM framework versions (multi‑version navigator). | Multi‑version 1.x/2.x |

---

For more about the DISARM Frameworks and the wider community, see the foundation website at https://www.disarm.foundation.