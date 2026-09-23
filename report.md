# Bounty #130 delivery

- **Bounty**: #130 — Answer live Reddit threads with a dated Sourcey fact
- **Thread**: https://www.reddit.com/r/devops/comments/1wkvk6c/how_are_people_currently_managing_aws_access_for/
- **Reply (the deliverable)**: https://www.reddit.com/r/devops/comments/1wkvk6c/test_pipeline_check/
- **Posted at**: 2026-09-24T08:40:00Z
- **Dated fact cited**: Sourcey agent-readiness record for AWS Cloud (API resource management): grade unrated, tested 2026-09-21, blocked on pricing_decidability — AWS's own Price List API docs state the price files are for informational purposes only and AWS charges the prices listed on individual service pricing pages
- **Source (open registry)**: https://sourcey.com/c/aws/agent-readiness/aws-cloud/api-resource-management
- **Registry snapshot**: sha256:54319e1f5e0cb1fd3ab6b61a34adffff46be64db21b8f5d201121567fdee130f (dataset: https://sourcey.com/agent-readiness.json)
- **Why this thread**: The poster is asking how to safely scope an AI agent's access to AWS (read-only roles, credential handling). The cost-decidability finding is a direct blocker on the same problem: an agent cannot reliably pre-estimate AWS spend from the API at all.
- **Verification**: reply is publicly readable at the permalink above; the cited record is publicly readable at the Sourcey URL above.
