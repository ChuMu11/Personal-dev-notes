# Personal dev notes

Notes and configuration for my own development environment.

## Claude Code × Amazon Bedrock

Running [Claude Code](https://code.claude.com/docs) (Anthropic's CLI coding agent)
against Amazon Bedrock, for personal software development.

### Environment
- Claude Code 2.1.312, native Windows install
- Amazon Bedrock, region `us-east-1`
- Anthropic model access enabled through the Bedrock use-case form

### Configuration

```json
{
  "env": {
    "CLAUDE_CODE_USE_BEDROCK": "1",
    "AWS_REGION": "us-east-1",
    "ANTHROPIC_MODEL": "us.anthropic.claude-sonnet-4-6"
  }
}
