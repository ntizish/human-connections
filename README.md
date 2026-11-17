# Human connections

A little Obsidian-based system for keeping track of the people in your life. The purpose is to keep track and be aware of the meaningful and potentially meaningful connections.

## The 1–5 scale

|     | Name                | What it means                                                                                                                   |
| --- | ------------------- | ------------------------------------------------------------------------------------------------------------------------------- |
| 1   | Shared past         | The connecting context is gone and there's likely no reason to connect in the future. ex. classmates, exes, sports buddies etc. |
| 2   | Loose connection    | Peripheral conncection rather than ongoing. Can be whatever that might feel meaningful. ex. hairdresser, uni professor etc.     |
| 3   | Everyday connection | Not necessarily personally close, but involves regular meetings and conversation. ex. a colleague.                              |
| 4   | Close friend        | Willing to connect outside of forced context. ex. a friend, a gym buddy etc.                                                    |
| 5   | Inner circle        | People you share most personal matters with. ex. family, closest friends etc.                                                   |

## The graph

Open the graph view in Obsidian to see everyone connected to you at once. Each person note links back to `Me.md`, so the graph naturally forms around you as a center.

![Graph view](docs/graph.png)

Filter by `connection_rating:5` to see only your inner circle, or by any other rating to map a slice of your world.

![Filtered by rating](docs/graph-filtered.png)

Exclude `path:Templates` in the graph filter so the template doesn't show up as a person.

## Context hubs

Contexts are the shared settings or chapters behind connections: a family, school, workplace, community, or project. Add a plain Markdown note in `Contexts/` and link to it from the people who belong there. In Obsidian's graph, each context becomes a hub, making shared parts of your life visible alongside the links to `Me`.

For example, `People/Mom.md` links to `[[Contexts/Family|Family]]`, and `People/Alex Liu.md` links to `[[Contexts/School|School]]`. These are fictional examples, not real personal information. The existing graph images above show the original person-to-Me layout; context links add another layer.

A person can link to several contexts, such as `[[Contexts/School|School]]` and `[[Contexts/Family|Family]]`, or none at all. Keep the link to `[[Me]]` either way. Jamie, Chris, and Sam demonstrate notes without a context hub; there is no need to invent one just to complete a field.

Context membership is not a connection rating or proof of intimacy. Sharing a family, school, or workplace does not determine closeness, and people in the same context can have different ratings. Keep choosing `connection_rating` separately using the unchanged 1–5 scale above.

## Files

- `Me.md` — the center of your graph
- `People/` — one Markdown file per person
- `Contexts/` — optional shared-context hubs; `Family.md` and `School.md` are mock examples
- `Templates/Person Template.md` — copy this for each new person
- `Templates/Context Template.md` — copy this when a shared context would be useful

No plugins required.
