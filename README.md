# Secret scanning: generic password detection - limited beta

Welcome to the beta of generic password detection for secret scanning. We're excited for you to test out and provide feedback as we iterate on the feature. Access to this beta is provided through a waitlist -- [sign up if you're not already a participant](https://github.com/features/preview/security)!  

* [Learn more about generic secret detection](https://docs.github.com/en/code-security/secret-scanning/about-the-detection-of-generic-secrets-with-secret-scanning)

![screenshot of a detected password](https://github.com/courtneycl/cocotests-protected/assets/3474250/a48cf707-fd5e-46c8-b273-b2746ebf6861)

### Getting started  

During the beta, you'll need to [set an enterprise policy](https://docs.github.com/en/enterprise-cloud@latest/admin/policies/enforcing-policies-for-your-enterprise/enforcing-policies-for-code-security-and-analysis-for-your-enterprise#enforcing-a-policy-to-manage-the-use-of-generic-secret-detection-for-secret-scanning-in-your-enterprises-repositories) to manage the use of generic secret detection for secret scanning. Then, you'll need to enable AI detection in the security settings of each individual repository where you'd like to detect passwords. Enabling for all repositories at the organization and enterprise level are to come. 

Once enabled, detected passwords [will appear in the "Other" tab](https://docs.github.com/en/enterprise-cloud@latest/code-security/secret-scanning/managing-alerts-from-secret-scanning#viewing-alerts-for-generic-secrets-detected-using-ai) of your secret scanning alerts. Be sure to resolve alerts with the appropriate reason -- our engineering team will use data on the false positive rate to improve the model and increase precision over time. 

## 🔗 How to Use this Repository

We will be using this repository to centralize **early** feedback on generic password detection for secret scanning.

You can use this repository to file issues to:
- Up-vote a feature or request a new one
- Let us know how the model is performing on your repositories 
- File a bug report

## **[Discussions](https://github.com/github-early-access/secret-scanning-password-detection/discussions)** 

Discussions should be used as much as possible for questions, ideas, and open discussions with other folks in the preview. <!-- Change out repo name in discussions link -->

- 💡 [I have a suggestion](https://github.com/github-early-access/secret-scanning-password-detection/discussions/categories/ideas)
- ❓ [I have a question](https://github.com/github-early-access/secret-scanning-password-detection/discussions/categories/q-a)
- ✏️ [I have something else to discuss](https://github.com/github-early-access/secret-scanning-password-detection/discussions/categories/general)

## **[Issues](https://github.com/github-early-access/secret-scanning-password-detection/issues)**

Issues should be used for bug reports. <!-- Change out repo name in issues link -->

- 🐞 [I found a bug](https://github.com/github-early-access/secret-scanning-password-detection/issues/new?assignees=&labels=bug&template=bug-template.yml)



## 🫂 Code of Conduct

We expect our preview participants to follow our [GitHub Community Code of Conduct](https://docs.github.com/en/site-policy/github-terms/github-community-code-of-conduct) by:

- Engaging with consideration and respect
- Contributing in a positive and constructive way
- Being trustworthy

## 🗒️ Beta Preview Policy

As per [GitHub's Terms of Service](https://docs.github.com/en/github/site-policy/github-terms-of-service#j-beta-previews) we want to remind you that:

> Beta Previews may not be supported or may change at any time. You may receive confidential information through those programs that must remain confidential while the program is private. We'd love your feedback to make our Beta Previews better.



