# ZVChain Improvement Proposals (ZIPs)

ZVChain Improvement Proposals (ZIPs) describe standards for the ZVChain platform, including core protocol specifications, client APIs, and contract standards.

# Contributing
 1. Fork the repository by clicking "Fork" in the top right.
 2. Add your ZIP to your fork of the repository. There is a [template ZIP here](template.md).
 3. Submit a Pull Request to ZVChain's [ZIPs repository](https://github.com/zvchain/ZIPs).

Your first PR should be a first draft of the final ZIP. It must meet the formatting criteria enforced by the build (largely, correct metadata in the header). An editor will manually review the first PR for a new ZIP and assign it a number before merging it. Make sure you include a `discussions-to` header with the URL to a discussion forum or open GitHub issue where people can discuss the ZIP as a whole.

If your ZIP requires images, the image files should be included in a subdirectory of the `assets` folder for that ZIP as follows: `assets/zip-N` (where **N** is to be replaced with the ZIP number). When linking to an image in the ZIP, use relative links such as `../assets/zip-1/image.png`.

Once your first PR is merged, we have a bot that helps out by automatically merging PRs to draft ZIPs. For this to work, it has to be able to tell that you own the draft being edited. Make sure that the 'author' line of your ZIP contains either your Github username or your email address inside <triangular brackets>. If you use your email address, that address must be the one publicly shown on [your GitHub profile](https://github.com/settings/profile).

When you believe your ZIP is mature and ready to progress past the draft phase, you should do one of two things:

 - **For a Standards Track ZIP of type Core**, ask to have your issue added to [the agenda of an upcoming All Core Devs meeting](https://github.com/zvchain/ZIPs/issues), where it can be discussed for inclusion in a future hard fork. If implementers agree to include it, the ZIP editors will update the state of your ZIP to 'Accepted'.
 - **For all other ZIPs**, open a PR changing the state of your ZIP to 'Final'. An editor will review your draft and ask if anyone objects to its being finalised. If the editor decides there is no rough consensus - for instance, because contributors point out significant issues with the ZIP - they may close the PR and request that you fix the issues in the draft before trying again.

# ZIP Status Terms

* **Draft** - an ZIP that is undergoing rapid iteration and changes.
* **Last Call** - an ZIP that is done with its initial iteration and ready for review by a wide audience.
* **Accepted** - a core ZIP that has been in Last Call for at least 2 weeks and any technical changes that were requested have been addressed by the author. The process for Core Devs to decide whether to encode an ZIP into their clients as part of a hard fork is not part of the ZIP process. If such a decision is made, the ZIP will move to final.
* **Final (non-Core)** - an ZIP that has been in Last Call for at least 2 weeks and any technical changes that were requested have been addressed by the author.
* **Final (Core)** - an ZIP that the Core Devs have decided to implement and release in a future hard fork or has already been released in a hard fork. 

# Validation

ZIPs must pass some validation tests.  

