# Jhon Meza

**Senior Solutions Architect & Technical Lead** · Medellín, Colombia

I design and run AWS platforms for enterprise clients: multi-account architecture, Infrastructure as Code with Terraform, cloud governance and FinOps, and more recently AI agents that operate under the same governance as everything else.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-jhonmezaa-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/jhonmezaa/)
[![Email](https://img.shields.io/badge/Email-jmezariveira%40gmail.com-555?logo=gmail&logoColor=white)](mailto:jmezariveira@gmail.com)

## About

- Working in infrastructure since 2018 and on AWS full-time since 2021, first in migrations and cloud operations, now leading architecture and delivery teams.
- Day to day: AWS Well-Architected designs, Terraform standards across multi-account environments, CI/CD, observability, incident response and cost reviews.
- Current focus: agentic AI on AWS (Amazon Bedrock AgentCore, MCP) with real guardrails: permissions, budgets, human approval and audit.
- I write about cloud and AI in Spanish on [LinkedIn](https://www.linkedin.com/in/jhonmezaa/).

## Certifications

| Certification | Since |
| --- | --- |
| AWS Certified Solutions Architect – Professional | 2024 |
| AWS Certified Solutions Architect – Associate | 2022 |
| AWS Certified Cloud Practitioner | 2021 |

## Projects

### Terraform modules for AWS

21 modules I use as building blocks for AWS landing zones and workloads. Each one is versioned with SemVer tags, has a changelog and ships usage examples. They target Terraform 1.x and the AWS provider 6.x.

| Area | Modules |
| --- | --- |
| Networking | [vpc](https://github.com/jhonmezaa/terraform-aws-vpc) · [transit-gateway](https://github.com/jhonmezaa/terraform-aws-transit-gateway) · [vpn](https://github.com/jhonmezaa/terraform-aws-vpn) · [security-group](https://github.com/jhonmezaa/terraform-aws-security-group) · [route53](https://github.com/jhonmezaa/terraform-aws-route53) |
| Containers | [eks](https://github.com/jhonmezaa/terraform-aws-eks) · [eks-helm-addons](https://github.com/jhonmezaa/terraform-aws-eks-helm-addons) · [ecs](https://github.com/jhonmezaa/terraform-aws-ecs) · [ecr](https://github.com/jhonmezaa/terraform-aws-ecr) |
| Data | [rds](https://github.com/jhonmezaa/terraform-aws-rds) · [dynamodb](https://github.com/jhonmezaa/terraform-aws-dynamodb) · [elasticache](https://github.com/jhonmezaa/terraform-aws-elasticache) · [s3](https://github.com/jhonmezaa/terraform-aws-s3) |
| Edge & delivery | [alb](https://github.com/jhonmezaa/terraform-aws-alb) · [cloudfront](https://github.com/jhonmezaa/terraform-aws-cloudfront) · [waf](https://github.com/jhonmezaa/terraform-aws-waf) · [acm](https://github.com/jhonmezaa/terraform-aws-acm) |
| Identity & secrets | [iam](https://github.com/jhonmezaa/terraform-aws-iam) · [cognito](https://github.com/jhonmezaa/terraform-aws-cognito) · [secrets-manager](https://github.com/jhonmezaa/terraform-aws-secrets-manager) |
| Observability | [cloudwatch](https://github.com/jhonmezaa/terraform-aws-cloudwatch) |

A few worth opening first:

- **eks**: managed node groups, Fargate profiles, access entries, IRSA and Auto Mode, with examples for private, IPv6 and Karpenter-ready clusters.
- **eks-helm-addons**: Karpenter, KEDA, External Secrets, AWS Load Balancer Controller, cert-manager, external-dns, Velero and more, each wired with IRSA.
- **vpc**: seven subnet types, several NAT strategies, IPv6, flow logs and VPC endpoints.
- **rds**: RDS instances and Aurora, including Serverless v2, global clusters and RDS Proxy.

```hcl
module "vpc" {
  source = "github.com/jhonmezaa/terraform-aws-vpc//vpc?ref=v1.1.0"
  # ...
}
```

### Also

- [hookline](https://github.com/jhonmezaa/hookline): a local-first Next.js app that analyses viral Instagram Reels and drafts adapted content ideas with Gemini and Claude.
- [git-desde-cero](https://github.com/jhonmezaa/git-desde-cero): a Git guide in Spanish, from the first commit to Git internals.

## Stack

<p>
  <img src="https://skillicons.dev/icons?i=aws,terraform,kubernetes,docker,githubactions,py,ts,bash,fastapi,react,linux&perline=11" alt="AWS, Terraform, Kubernetes, Docker, GitHub Actions, Python, TypeScript, Bash, FastAPI, React, Linux" />
</p>

| | |
| --- | --- |
| **Cloud** | AWS: Organizations and multi-account, VPC and Transit Gateway, EKS, ECS, Lambda, RDS/Aurora, DynamoDB, CloudFront, WAF, IAM |
| **IaC** | Terraform, AWS CDK, CloudFormation |
| **Kubernetes** | EKS, Helm, Karpenter, KEDA, External Secrets |
| **CI/CD** | GitHub Actions, Azure DevOps |
| **AI** | Amazon Bedrock and AgentCore, MCP, Claude |
| **Security & policy** | Verified Permissions (Cedar), cdk-nag, cfn-guard, Checkov |
| **Languages** | Python, TypeScript, HCL, Bash, PowerShell |

## GitHub activity

<p>
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api?username=jhonmezaa&show_icons=true&hide_rank=true&hide=stars&hide_border=true&theme=github_dark" />
    <img height="165" src="https://github-readme-stats.vercel.app/api?username=jhonmezaa&show_icons=true&hide_rank=true&hide=stars&hide_border=true&theme=default" alt="GitHub stats" />
  </picture>
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=jhonmezaa&layout=compact&langs_count=6&hide_border=true&theme=github_dark" />
    <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=jhonmezaa&layout=compact&langs_count=6&hide_border=true&theme=default" alt="Most used languages" />
  </picture>
</p>
<p>
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://streak-stats.demolab.com/?user=jhonmezaa&hide_border=true&theme=github-dark-blue" />
    <img src="https://streak-stats.demolab.com/?user=jhonmezaa&hide_border=true&theme=default" alt="Contribution streak" />
  </picture>
</p>

## Contact

The fastest way to reach me is [LinkedIn](https://www.linkedin.com/in/jhonmezaa/) or [email](mailto:jmezariveira@gmail.com). Happy to talk about AWS architecture, Terraform, cloud governance or agentic AI.
