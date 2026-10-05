# Scittle: AWS Cost Recovery

Live product: https://scittleme.com

Scittle finds idle and wasted cloud capacity, confirms that reclaiming it is safe, and recovers it automatically. It is commission-based, so customers pay only when money is recovered.

## How it works

1. Detect: continuously maps cloud spend against actual utilization to surface idle capacity, stranded nodes and duplicate workloads.
2. Verify: every candidate is checked against workload dependencies before anything is touched.
3. Recover: safe fixes apply on their own. Anything else is routed to the customer's team with the numbers attached.

## Built with

Serverless AWS (Lambda, API Gateway, DynamoDB, CloudWatch), with automation for scanning and remediation.

## My role

Sole designer, builder and operator: architecture, infrastructure, security and deployment.

Part of UnHidden Holdings LLC. Portfolio: https://admralwalker.github.io
