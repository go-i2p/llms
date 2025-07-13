# LLM CODING ASSISTANT USAGE POLICY

**Effective Date:** 2025-07-12
**Version:** 1.0

## SCOPE
This policy covers the use of LLM coding assistants (GitHub Copilot, ChatGPT, Claude, etc.) for `go-i2p`.
Data handling policies are out-of-scope for this document.

## DATA HANDLING RULE
**If you wouldn't hand the keys to Sam Altman, Elon Musk, or Peter Thiel, then don't give it to the LLM.**

This includes: credentials, API keys, customer data, proprietary algorithms, or any sensitive information.

## ACCEPTABLE USES
- Generating tests
- Generating less than 3 lines of code at a time(code-completion)
- Assistance identifying bugs
- Writing short snippets of documentation
- Explaining code that already exists
- Code audits and optimization suggestions

## UNACCEPTABLE USES
- Generating code without expert review
- Deploying AI-generated code directly to production
- Using generated code without understanding it
- Contributing AI-generated tests that test AI-generated code
- Violating open source licenses

## REQUIREMENTS
1. All LLM-Generated code must be submitted as a pull request regardless of contributor
2. All LLM-generated code must be human-reviewed before merging
3. Mark significant AI-generated portions with comments
4. Test thoroughly - AI code isn't magic

## APPROVED TOOLS
- We do not restrict the choice of tools at this time.

## ENFORCEMENT
Violations will result in warnings, tool access suspension, or termination depending on severity.

**Questions:** Please submit an issue or PR on this repository.

By using LLM assistants, you agree to follow this policy.

**Acknowledged by:** _________________ **Date:** _________________
