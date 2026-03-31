# DISARM Foundation GitHub

The DISARM Foundation exists to keep the DISARM Frameworks open, protected, promoted and supported — by and for the community of those combatting disinformation.

The framework, STIX and navigator repositories belong together: the framework repo hosts the framework master files and web pages, the STIX repo hosts the STIX generator and bundle, and the navigator repos host the code to present the framework matrix and associated web pages via a fork of the MITRE ATT&CK Navigator. All repositories follow the same **versioning** scheme based on the version of the framework: tools do not have their own independent versions, they track the framework version instead. The Foundation publishes a “dot release” (for example 1.4.0, 1.5.0, 1.6.0, 1.7.0) when it has significant updates to the framework, and “patch releases” (for example 1.4.1) for bug fixes; 1.n.0 is usually the first release of a new version 1.n, which is then stabilised through patches until 1.n.1 becomes the stable release for that version line.

## Legacy (versions 1.0–1.6)

These repositories support the original DISARM 1.x framework releases up to, and including, 1.6.

| Repository         | Purpose (short)                                                                                           | Framework focus |
|--------------------|------------------------------------------------------------------------------------------------------------|-----------------|
| `DISARMframeworks` | Master copies of DISARM 1.x frameworks and generated files for exploration and exports.                   | 1.0–1.6 (core)  |
| `DISARM-STIX2`     | STIX 2 generator and bundle for the DISARM 1.x framework.                                                 | 1.0–1.6         |
| `disarm-navigator` | Web app for navigating and annotating DISARM 1.x matrices (fork of ATT&CK Navigator).                     | 1.0–1.6         |
| `DISARMWordPlugIn` | Microsoft Word plug‑in to tag and analyse documents using DISARM 1.x techniques while writing or coding. | 1.0–1.6         |
| `DISARMexplorer`   | Experimental Flask/Python/D3 site for exploring DISARM framework objects and relationships.              | 1.x (legacy)    |

## Fact Checking (version 1.7)

These repositories capture the DISARM 1.7 update, which added techniques most relevant to fact checkers.

| Repository            | Purpose (short)                                                                                  | Framework focus |
|-----------------------|---------------------------------------------------------------------------------------------------|-----------------|
| `DISARMframeworks-17` | Framework data for DISARM 1.7, including additional techniques for fact checkers.                | 1.7 framework   |
| `disarm-navigator-17` | Navigator app configured for the DISARM 1.7 red framework and fact‑checker update.               | 1.7 navigator   |
| `disarm-stix-17`      | STIX 2 bundle and related code for the DISARM 1.7 framework and fact‑checking use cases.         | 1.7 STIX        |

## Next Generation (version 2.0)

These repositories implement and support prototypes of the DISARM 2.0 Observations framework and navigator support for multiple versions of DISARM including 1.x and 2.x.

| Repository                       | Purpose (short)                                                                                   | Framework focus   |
|----------------------------------|----------------------------------------------------------------------------------------------------|-------------------|
| `DISARMframeworks-20-observable` | Master copies of the DISARM 2.0 Observations framework, plus generated files for exploring the data. | 2.0 Observations |
| `disarm-stix-20-observable`      | STIX 2 bundle and related code for the DISARM 2.0 Observations framework.                        | 2.0 Observations  |
| `disarm-navigator-20-observable` | Navigator web app for navigating and annotating the DISARM 2.0 Observations matrix.              | 2.0 Observations  |
| `disarm-navigator-mv`            | Navigator variant for supporting multiple DISARM framework versions (multi‑version navigator).    | Multi‑version 1.x/2.x |
