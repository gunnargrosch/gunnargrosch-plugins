# Gunnar Grosch Claude Code Plugins

A marketplace of Claude Code plugins by Gunnar Grosch.

## Installation

Add this marketplace to Claude Code:

```bash
/plugin marketplace add gunnargrosch/gunnargrosch-plugins
```

## Available Plugins

### AWS Serverless Plugin

Build and deploy serverless applications with AWS Lambda, SAM, API Gateway, EventBridge, and Step Functions.

```bash
/plugin install aws-serverless@gunnargrosch-plugins
```

**Features:**

- SAM CLI and CDK integration (init, build, deploy, local testing)
- Web application deployment with Lambda Web Adapter, authentication, and response streaming
- Lambda event sources for S3, SNS, DynamoDB, Kinesis, SQS, Kafka, MQ, DocumentDB
- EventBridge event design, routing, Pipes, and schema registry
- Lambda Durable Functions and Step Functions workflow patterns
- Observability: structured logging, tracing, Application Signals, dashboards, and alarms
- Performance optimization, cost tuning, and troubleshooting guidance
- SAM template validation hook (runs `sam validate` after template edits)

[View plugin repository](https://github.com/gunnargrosch/aws-serverless-plugin)

### AWS AppConfig Plugin

Manage application configuration and feature flags with AWS AppConfig — deployment strategies, safe rollouts, and multi-compute integration.

```bash
/plugin install aws-appconfig@gunnargrosch-plugins
```

**Features:**

- Feature flags with multi-variant support, targeting rules, split operator for A/B testing, and Powertools integration
- Freeform configuration profiles with JSON Schema and Lambda validators
- Deployment strategies with automatic rollback via CloudWatch alarms and 72-hour revert
- Lambda extension, ECS/EKS/Fargate sidecars, AWS Batch, EC2 daemon, and on-premises integration
- Monitoring with rollback notifications, extensions (EventBridge, SNS, SQS, Jira), and CloudTrail auditing
- Symptom-based troubleshooting for common AppConfig issues

[View plugin repository](https://github.com/gunnargrosch/aws-appconfig-plugin)

## License

MIT
