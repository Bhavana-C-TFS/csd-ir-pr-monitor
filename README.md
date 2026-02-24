# Inner Source Template Project

This project is meant to serve as a general template for new inner source repositories, it has all the basic files needed to start.

## Quick start guide

1. Create a new github repository using this repository as template (note the "Use this Template" link at the upper right)
2. Clone your new repository locally

Once the previous steps have been completed, go through the following checklist:

- [ ] Open and update `README-sample.md` with your project's information
	- [ ] Replace `Project Title` with your own and update the projects description.
	- [ ] Update the `Getting Started` section.
	- [ ] Update the `Running the tests` section.
	- [ ] Update the `Coding conventions` section.
	- [ ] Update the `Community` section.
	- [ ] Update the `Deployment` section.
	- [ ] Update the `Built with` section.
	- [ ] Update the `Contributing` section.
	- [ ] Update the `Versioning` section.
	- [ ] Update the `Authors` section.
	- [ ] Update the `Acknoledgements` section.
- [ ] Add the inner-source topic and any other topic labels that might help describe the project to others. This also makes it easier for users to discover your project.
- [ ] Open and update `CHANGELOG.md`, if the project is brand new remember to remove all content from this file until you have your first release. You can find an example of what to put and how to format [here](https://keepachangelog.com/en/1.0.0/)
- [ ] Open and update `CONTRIBUTING.md` with your project's instructions on how to contribute to it.
- [ ] Open and update `CONTRIBUTORS.md` with the names and email addresses of the members of the maintaining team.
- [ ] Open and update `CODE_OF_CONDUCT.md` with the email address to which issues around code of conduct should be sent.
- [ ] Open and update `CODEOWNERS` with the handles of the maintainers from which reviews are required for pull requests (Note: only one reviewer needs to approve). Refer to [About Code Owners](https://docs.github.com/en/enterprise-cloud@latest/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/about-code-owners) for syntax.
- [ ] Open and update [`SECURITY.md`](.github/SECURITY.md) with instructions on how to responsibly report a security vulnerability in your project.
- [ ] Setup a GitHub Actions to build and deploy your product.  Refer to [CIS GitHub Actions](https://thermofisher.sharepoint.com/sites/CIS-DevSecOps/SitePages/GitHub-Actions.aspx) for instructions on setting up a self-hosted runner as needed. Also refer to [DPE GitHub Actions](https://github.com/thermofisher/dpe-gha-workflows) for additional support for Actions.
- [ ] Setup CodeQL static analysis.  Refer to [GitHub](https://docs.github.com/en/enterprise-cloud@latest/code-security/code-scanning/enabling-code-scanning/configuring-default-setup-for-code-scanning) for instructions. NOTE: Dependabot is already configured and running for any new repository within the Thermo Fisher organization. If you also require vulnerability scanning, please refer to [CIS Qualys WAS setup](https://thermofisher.sharepoint.com/sites/CIS-DevSecOps/SitePages/Getting-Started-w--Qualys-WAS-Interface.aspx).

Once you have gone through the checklist delete this file and rename `README-sample.md` to `README.md`

## Prior Art

This repository is an update of the Tijuana team's Inner Source repository created in 2019.  Thanks go to them for their efforts.
