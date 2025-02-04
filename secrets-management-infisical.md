---
title: "Hugging Face secures the future of AI with Infisical" 
thumbnail: /blog/assets/infisical/thumbnail.png
authors:
- user: segudev
---

# Hugging Face secures the future of AI with Infisical

With Artificial Intelligence growing in popularity over the past years, so has usage on Hugging Face, with over 4 million AI builders from academia and industry building and deploying on the Hugging Face Hub. Its product infrastructure and engineering team had to scale rapidly which led to a few key challenges that had to be prioritized:

- Reducing Security Risks: Being at the forefront of AI, Hugging Face must ensure that its security infrastructure exceeds industry standards. This includes maintaining tight access controls, embracing "Security Shift Left", and more.
- Eliminating Manual Secrets Management: As infrastructure complexity increases and Hugging Face undertakes new engineering projects, [secrets sprawl](https://infisical.com/blog/what-is-secret-sprawl) becomes a real problem. The team wanted to automate secrets management, redeployment, and other processes.
- Improving Developer Experience: With a large engineering team, Hugging Face needs to keep developers productive which includes providing self-serve secret management workflows, facilitating developer onboarding, etc.

## Solution

To solve the above problems, Hugging Face partnered with [Infisical](https://infisical.com/) to centralize its secrets management workflows and establish a **single source of truth** for infrastructure credentials. Some of the functionality that the team at Hugging Face is using includes:

- [Web Dashboard](https://infisical.com/docs/documentation/platform/project): Infisical's UI enabled Hugging Face engineers to effortlessly manage secrets in different projects and environments in a self-serve way according to the predefined permissions.
- [Infisical CLI](https://infisical.com/docs/cli/usage): When developing locally, Hugging Face engineers can use Infisical CLI to inject secrets into their local application environments – completely removing the need for .env files and reducing security risks that stem from having secrets on local machines.
- [Kubernetes Operator](https://infisical.com/docs/integrations/platforms/kubernetes): With Hugging Face relying heavily on Kubernetes for managing its infrastructure, the team was able to utilize Infisical's Kubernetes Operator to easily propagate secrets to the right containers and automatically redeploy their applications.
- [References and Imports](https://infisical.com/docs/documentation/platform/secret-reference): Using Infisical's Secret Referencing and Importing functionality, Hugging Face was able to achieve true single source of truth for credentials across infrastructure.
- [Secret Sharing](https://infisical.com/docs/documentation/platform/secret-sharing): Infisical Secret Sharing Infrastructure allows Hugging Face developers to generate encrypted links to share secrets with each other or with stakeholders outside of the organization.

## Results

With the help of Infisical, Hugging Face was able to increase operational efficiency and significantly enhance security posture through centralized secrets management. In addition, achieving central source of truth for secrets enabled Hugging Face developers to move faster and be more productive. As mentioned by the team, “Infisical is a rare developer tool that can both increase productivity and improve security.”

> "Infisical provided all the functionality and security settings we needed to boost our security posture and save engineering time. Whether you're working locally, running kubernetes clusters in production, or operating secrets within CI/CD pipelines, Infisical has a seamless prebuilt workflow."
Adrien Carreira, Head of Infrastructure, Hugging Face

### Improved security posture

Using Infisical, Hugging Face was able to enhance collaboration and built-in security by incorporating a security-first approach to development cycles. Infisical's centralized secrets management platform allowed Hugging Face to maintain tight and granular access controls, track comprehensive audit logs, utilize secure authentication methods, and more.

### Productivity and efficiency gain

In addition, Hugging Face's engineering team was able to automate their secret management workflows:

- Self-serve secret management: With Infisical, engineers at Hugging Face can perform various operations with secrets in accordance with their permissions. This saves developers time and speeds up development iterations.
- Fast developer onboarding: new engineers are now able to immediately get up and running with access to the necessary environments.
- Local developer experience: Hugging Face engineers easily check out the right environment and start their applications locally. As a result, secrets never get out-of-sync with their teammates – saving developers time and allowing them to prioritize more business-critical tasks.
- Automated redeployments: Using Infisical, Hugging Face is able to automatically redeploy their applications based on secret changes in various environments.

### Security Shift Left

Using Infisical to provide self-serve secret management workflows (depending on developers' permissions), Hugging Face is able to encourage developers to act more securely, following responsible coding practices, and sharing secrets via encrypted channels.

*this article was originally published at: https://infisical.com/customers/hugging-face*
