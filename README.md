# getting-started

The repositories and contents in this org are to assist you on getting started with GitHub Enterprise trial or production service. 
You can also leverage the template repositories, and tryout various features of GitHub Enterprise. 
Don't forget to checkout the Onboarding Guides and FAQ if you have any questions. 

## Template repositories


## Onboarding Guide
- [Getting started with GitHub Enterprise](https://resources.github.com/enterprise-onboarding/)
- [Migrate to GitHub Enterprise from other VCS](https://github.github.com/enterprise-migrations/#/)
- [GitHub Enterprise Onboarding: Workflow Strategies](https://vimeo.com/333784745)
- [Organizing people for successful collaboration](https://vimeo.com/333786093)
- [GitHub Enterprise Onboarding: Managing Projects](https://vimeo.com/333785072)

## Onboarding FAQ


  - I have multiple GitHub Enterprise Cloud Orgs, Can I combine these one billing entity? 
  
     -  An [enterprise account](https://docs.github.com/en/github/setting-up-and-managing-your-enterprise/about-enterprise-accounts) allows you to manage multiple GitHub organizations and GitHub Enterprise Server instances. Your enterprise account must have a handle, like an organization or personal account on GitHub.
     
  - How can I start trial for GitHub Enterprise Cloud or GitHub Enterprise Server?
  
     - **GitHub Enterprise Cloud**: You can set up a 14-day trial to evaluate GitHub Enterprise Cloud on a new organization account. Your trial includes 50 seats. If you need more seats to evaluate GitHub Enterprise Cloud, contact [GitHub's Sales team](https://enterprise.github.com/contact). To start trial, you must have an existing user account or [create a new user account](https://docs.github.com/en/articles/signing-up-for-a-new-github-account). Then you can submit a [trial request](https://github.com/account/organizations/new?plan=business_plus&ref_cta=Start+a+free+trial&ref_loc=hero&ref_page=%2Fenterprise).
     
     - **GitHub Enterprise Server**: You can request a 45-day trial to evaluate GitHub Enterprise Server. Your trial will be installed as a virtual appliance, with options for on-premises or cloud deployment. Determine the best person in your organization to set up a virtual machine, and ask that person to submit a [trial request](https://enterprise.github.com/trial). 
     
  - What’s the difference between GHEC and GHES?
  
     - _GitHub Enterprise Cloud_ is SaaS offering of GitHub Enterprise on GitHub’s datacenter. With a 99.95% uptime SLA and access to GitHub’s built-in security features, Enterprise Cloud is an appealing offering. It allows you to restrict user access based on a user’s network and add SAML sign-on, but it removes your need to maintain potentially expensive infrastructure.
     
     -  _GitHub Enterprise Server_ is the on-premises git repository hosting offering from GitHub. Large organizations commonly run GitHub Enterprise Server for improved control and security over their code repositories. With Enterprise Server, you can limit access to a private network, set rules for creating and accessing repositories, use SAML for single sign-on across your organization, and get access to premium GitHub support. You can also migrate to different hardware as your team and repositories grow, so there’s a lot of power in GitHub Enterprise Server.
     
  - Is there a GitHub roadmap that I can refer to?
     - [GitHub Public Roadmap](https://github.com/github/roadmap/projects/1) is the GitHub publicized roadmap.
     
  - Can I use SAML integration?
     - You can configure Security Assertion Markup Language (SAML) single sign-on (SSO) to protect your organization's resources on GitHub. Github support [various identity providers](https://docs.github.com/en/organizations/managing-saml-single-sign-on-for-your-organization/about-identity-and-access-management-with-saml-single-sign-on#supported-saml-services). You can enable SAML for your [organization](https://docs.github.com/en/organizations/managing-saml-single-sign-on-for-your-organization/enabling-and-testing-saml-single-sign-on-for-your-organization), or  for your [Enterprise account](https://docs.github.com/en/github/setting-up-and-managing-your-enterprise/enabling-saml-single-sign-on-for-organizations-in-your-enterprise-account#about-saml-single-sign-on-for-enterprise-accounts). 
     - You can also configure SAML for [GitHub Enterprise Server](https://docs.github.com/en/enterprise-server@3.1/admin/authentication/using-saml#supported-saml-services). 
     - You can implement [SCIM](https://docs.github.com/en/organizations/managing-saml-single-sign-on-for-your-organization/about-scim) to add, manage, and remove organization members' access to GitHub. For example, an administrator can deprovision an organization member using SCIM and automatically remove the member from the organization.
  
  - How can company allow only the users from inside a company?

    -  Enterprise owners can restrict access to assets owned by organizations in an enterprise account by configuring an allow list for specific IP addresses. For example, you can allow access from only the IP address of your office network. The allow list for IP addresses will block access via the web, API, and Git from any IP addresses that are not on the allow list.
    -  IP allow list can be either set on [Enterprse Account level](https://docs.github.com/en/github/setting-up-and-managing-your-enterprise/enforcing-security-settings-in-your-enterprise-account), or per [Organization level](https://docs.github.com/en/organizations/keeping-your-organization-secure/managing-allowed-ip-addresses-for-your-organization#about-allowed-ip-addresses). 
 
  - How can I download the license for my GitHub Enterprise Instance?
     - When you purchase or renew GitHub Enterprise, you receive a license file to validate your application. A license file has an expiration date and controls the number of user licenses you can add to GitHub Enterprise. You now can download your new license file, then upload the file to GitHub Enterprise Server to [unlock your new user licenses](https://docs.github.com/en/enterprise-server@3.1/admin/overview/managing-your-github-enterprise-license#uploading-a-new-license-to-github-enterprise-server).
     - You can [connect your GitHub Enterprise Server instance to GitHub Enterprise Cloud](https://docs.github.com/en/enterprise-server@3.1/admin/configuration/enabling-automatic-user-license-sync-between-github-enterprise-server-and-github-enterprise-cloud) and allow GitHub Enterprise Server to upload user license information to your enterprise account on GitHub.com. Site administrators for GitHub Enterprise Server who are also owners of the connected GitHub Enterprise Cloud organization or enterprise account can enable automatic user license synchronization.
 
  - What’re the supported virtual infrastructures that GHES can be deployed?
     - GitHub Enterprise Server instance can be deployed on various virtual platforms and infrastructures.
     - Cloud Services: [Azure](https://docs.github.com/en/enterprise-server@3.1/admin/installation/installing-github-enterprise-server-on-azure), [AWS](https://docs.github.com/en/enterprise-server@3.1/admin/installation/installing-github-enterprise-server-on-aws), [GCP](https://docs.github.com/en/enterprise-server@3.1/admin/installation/installing-github-enterprise-server-on-google-cloud-platform)
     - Virtual platforms : [Hyper-V](https://docs.github.com/en/enterprise-server@3.1/admin/installation/installing-github-enterprise-server-on-hyper-v), [OpenStack KVM](https://docs.github.com/en/enterprise-server@3.1/admin/installation/installing-github-enterprise-server-on-openstack-kvm), [VMware](https://docs.github.com/en/enterprise-server@3.1/admin/installation/installing-github-enterprise-server-on-vmware), [XenServer](https://docs.github.com/en/enterprise-server@3.1/admin/installation/installing-github-enterprise-server-on-xenserver)
     - Please also refer to the minumum requrements on Hardware for each virtual platform






