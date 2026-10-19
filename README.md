# Awesome AI employees

Open source. A curated list of open-source projects for running an AI employee, a role-based agent
with its own instructions, tools, memory and review rules, instead of renting one from a vendor.

Maintained with [Kortix](https://kortix.com), the open-source AI Operating System, and the list behind
[opensourceaiemployee.com](https://opensourceaiemployee.com). The definition behind this list is set
out at [what is an AI employee](https://opensourceaiemployee.com/what-is-an-ai-employee).

## The platform

- [Kortix](https://github.com/kortix-ai/suna): the open-source AI Operating System. An AI employee
  is an agent with a role file, a connector grant and a `kortix.yaml` policy that sets every call to
  allow, require approval or block. Self-hosted, VPC or on-prem, any model. Docs:
  <https://kortix.com/docs>.

## Role packs and templates

- [markfulton/ai-employees](https://github.com/markfulton/ai-employees): eight business roles as
  folders of scheduled routines that run on the agent harness you already use.
- [OpenLabor/openlabor](https://github.com/OpenLabor/openlabor): roles, skills and missions as
  Markdown files, built for an agent that reads the repo.
- [joyozhang333-lgtm/awesome-ai-organization](https://github.com/joyozhang333-lgtm/awesome-ai-organization):
  a collection of frameworks, role templates and playbooks for running an organisation with AI employees.

## Platforms that package the role

- [zeenie-ai/OpenCompany](https://github.com/zeenie-ai/OpenCompany): self-improving AI employees
  with their own workspace.
- [ruh-ai/openclaw-ruh](https://github.com/ruh-ai/openclaw-ruh): an agent builder with Docker-native
  sandboxes and a lifecycle for each employee.
- [h4dex/opc-nexus](https://github.com/h4dex/opc-nexus): a local-first desktop manager for a
  one-person company's digital employees.

## How to choose one

1. **Where does the role live?** A markdown file in your repo beats a record in a vendor's database.
2. **What happens before a risky call?** Look for a rule per tool, and per argument, not a checkbox.
3. **Where does memory go when you change model vendors?** Files you own, or nothing to move.
4. **Who can read the audit trail?** You, without a support ticket.

The longer version is in [docs/01-what-makes-an-ai-employee.md](docs/01-what-makes-an-ai-employee.md)
and the policy comparison in [docs/02-approval-models.md](docs/02-approval-models.md).

## Contributing

One entry per pull request: the project's name, its repository URL, one sentence on what it is, and
why it belongs in the list. Projects must be open source and runnable by the reader.

## More

- The site this list supports: <https://opensourceaiemployee.com>
- Product and docs: <https://kortix.com> · <https://kortix.com/docs>
