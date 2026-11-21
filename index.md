# Skills index

A skill is a set of instructions that helps an AI agent approach a particular kind of task. These skills are optional; you don't need them to complete setup.

## Interview me

Use this when you have an idea but aren't sure what to build. The agent asks questions one at a time to help you clarify what you want.

Try: **“Interview me about my idea for a trivia app.”**

[Read the interview-me skill](skills/interview-me/SKILL.md)

## Handoff

Use this when you're stopping work and want another agent or session to pick up where you left off. Review the handoff for accuracy and remove any private information before sharing it.

Try: **“Create a handoff so I can continue building my app in a new session.”**

The original skill directs the agent to save the handoff in a temporary directory, not in your project. Temporary files may not be kept permanently.

[Read the handoff skill](skills/handoff/SKILL.md)

## Setup Matt Pocock's skills

Use this to configure a project for Matt Pocock's engineering skills. It asks about your issue tracker, issue labels, and where project terminology and decision records live. Review its proposed changes before approving them.

Try: **“Run setup-matt-pocock-skills for this project.”**

[Read the setup skill](skills/setup-matt-pocock-skills/SKILL.md)

## To spec

Use this after discussing an idea to turn the conversation into a specification and publish it to the project's configured issue tracker. It requires the setup above, checks testing decisions with you, and uses an extensive user-story list.

Try: **“Use to-spec to turn our discussion into a spec.”**

[Read the to-spec skill](skills/to-spec/SKILL.md)

## Wait, what?

Use this when the agent's last explanation didn't make sense. It asks the agent to explain again with context and simpler technical language.

Try: **“Use wait-what to explain that again.”**

[Read the wait-what skill](skills/wait-what/SKILL.md)

These examples describe what to ask after the skills are available to your agent; simply reading this page doesn't install them. Installation in the course Codespace is still to be tested.
