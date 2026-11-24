# Faizan Parvez

I build cloud and DevOps experiments you can run in a browser. My latest two started with questions I wanted to test for myself. How can a checkout dashboard look healthy when shoppers are waiting? When should a rollout stop sending traffic to a new release?

Based in Greater Noida and open to early-career cloud and DevOps roles.

## Slip 025

**All 100 checkouts succeeded. Order 025 took 639 ms.** Four slow orders slipped past the overall p95. Open order 025 and follow its trace into shipping to see where 624 ms went. Switch to recovery to see the same route complete in about 30 ms.

[Investigate order 025](https://checkout-incident-lab.vercel.app/) / [Slip 025 code and setup](https://github.com/Faizan00parvez/checkout-incident-lab)

## Holdpoint

**Would you stop a rollout after its first error?** I sent every fifth request to a new version and gave the router a rule to follow. In the faulty run, 3 of the first 20 responses from that version failed. Step ahead to request 105 to see which version handled it after the router stopped the rollout.

[Replay the rollout](https://faizan00parvez.github.io/holdpoint/) / [Holdpoint code and setup](https://github.com/Faizan00parvez/holdpoint)

## More of my work

- **PulseDeck** checks service uptime on a schedule and keeps the results in Git. [Live status](https://faizanxbuilds-status.vercel.app/) / [Probe and incident workflow](https://github.com/Faizan00parvez/pulsedeck)
- **DeployWatch** uses GitHub Actions, Helm and Argo CD to deliver changes to Kubernetes. [Explore the delivery pipeline](https://github.com/faizanxbuilds/DeployWatch)
- **CloudForge** provisions AWS networking, compute, storage and monitoring with Terraform. [Explore the infrastructure modules](https://github.com/Faizan00parvez/cloudforge-aws-infra)
- **Cloud scheduling research** compares how three algorithms distribute work across a cluster. [Read the paper on IEEE Xplore](https://ieeexplore.ieee.org/document/11389684)

## Credentials

- [AWS Certified Cloud Practitioner](https://www.credly.com/badges/dcd999c2-ef93-4405-88f2-8c0108ddb70d/public_url)
- [AWS Academy Cloud Architecting](https://www.credly.com/badges/630ed6cf-18c4-40dc-96a4-c0848406f34e/public_url)
- [AWS Academy Microservices and CI/CD](https://www.credly.com/badges/a558f4fc-4857-49ab-a140-5329b259ea10/public_url)

## Find me

I share experiments in progress on [X](https://x.com/faizanxbuilds). For my background or opportunities, visit my [portfolio](https://faizan00parvez.github.io/) or connect on [LinkedIn](https://www.linkedin.com/in/faizan-parvez-59b8a91b9/).
