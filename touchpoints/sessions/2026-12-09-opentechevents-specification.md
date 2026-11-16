# OpenTechEvents Specification

- **Speaker:** Raul Jimenez Ortega, Esri Inc.
- **Date:** Wednesday, December 9, 2026, 13:00 UTC
- **Format:** Show and tell, 15 minutes
- **GitHub:** [@hhkaos](https://github.com/hhkaos)

## Abstract

### The problem
There are **more platforms, more directories and more tools** than ever for creating and announcing events, and building custom tooling keeps getting easier. That is a good thing in principle, but it comes with a serious downside:

- **Events are increasingly diluted and scattered.** The information lives fragmented across Meetup, Eventbrite, LinkedIn, the organisers' own websites, GitHub repositories, third-party forms, and so on.
- **For whoever attends**, keeping up means monitoring many different platforms and directories so as not to miss anything.
- **For whoever organises**, getting the word out is increasingly complex: the same event has to be submitted to multiple platforms, in different formats, which multiplies both the effort and the maintenance

There is no shortage of information: what is missing is interoperability.

### The proposal

From Community Builders, a community of over 90 community leaders in Spain, we are designing a standard specification that makes it possible to:

1. **Describe an event once**, in a single, well-defined format.
2. **Automate its distribution** to multiple directories and platforms at the same time.
3. **Transform that data** into already established standards (RSS, iCalendar…) so it is compatible, with no friction, with the tools people already use.

The idea: a community publishes its data once and an ecosystem of tools takes care of the rest — ingesting, exporting, transforming and publishing to each destination.

### Downstream effects

If this specification were adopted more widely, it would become straightforward to build tools that enable devrel teams to design effective conference-attendance strategies, scaling the internal support needed to help our colleagues on engineering teams find the right match between their experiences and interests when participating in events.

I'm building a conference attendance framework tool that I would be happy to share. But it would be a different demo.

## Links

- <https://opentechevents.org/>
- <https://github.com/OpenTechEvents/ote-tools/tree/main/skills>
