# Galactic Standards

Galactic Standards (GSs) describe standards for the IDEP Network Blockchain, including core protocol specifications, client APIs, and related smart contract standards.

A browsable version of all current and draft GSs can be found on the official GS folder

# Contributing

 1. Fork the repository by clicking "Fork" in the top right.
 2. Add your GS to your fork of the repository. There is a [template GS here](GS-T.md).
 3. Submit a Pull Request to IDEP's [Galactic-Standards repository](https://github.com/IDEP-network/Galactic-Standards).

Your first PR should be a first draft of the final GS. It must meet the formatting criteria enforced by the build (largely, correct metadata in the header).Make sure you include a `discussions-to` header with the URL to a discussion forum or open GitHub issue where people can discuss the GS as a whole.

If your GS requires images, the image files should be included in a subdirectory of the `assets` folder for that GS as follow: `assets/GS-T` (for GS **T**). When linking to an image in the GS, use relative links such as `../assets/GS-T/image.png`.

When you believe your GS is mature and ready to progress past the draft phase, you should do open a PR changing the state of your GS to 'Final'. An editor will review your draft and ask if anyone objects to its being finalised. If the editor decides there is no rough consensus - for instance, because contributors point out significant issues with the GS - they may close the PR and request that you fix the issues in the draft before trying again.

# GS Status Terms

* **Draft** - an GS that is undergoing rapid iteration and changes.
* **Last Call** - an GS that is done with its initial iteration and ready for review by a wide audience.
* **Accepted** - a core GS that has been in Last Call for at least 2 weeks and any technical changes that were requested have been addressed by the author. The process for Core Devs to decide whether to encode an GS into their clients as part of a hard fork is not part of the GS process. If such a decision is made, the GS wil move to final.
* **Final (non-Core)** - an GS that has been in Last Call for at least 2 weeks and any technical changes that were requested have been addressed by the author.
* **Final (Core)** - an GS that the Core Devs have decided to implement and release in a future hard fork or has already been released in a hard fork. 
* **Deferred** - an GS that is not being considered for immediate adoption. May be reconsidered in the future for a subsequent hard fork.
