# Human connections

An Obsidian-friendly Markdown template for mapping the people you have met throughout your life. Remember what you shared, reflect on where you stand now, and be more thoughtful about the connections you have and have had.

Not a networking pipeline or a ranking of people's worth.

## The 1–5 connection system

Five broad levels are easier to distinguish honestly than ten finely graded scores. The number describes your connection with someone, from a shared past with no desired continuation to your closest friendships.

| Level | Name | Meaning |
| --- | --- | --- |
| 1 | Shared past | We know who each other are, but there is no active relationship and I see no reason to meet or communicate again. For example, a former classmate whose life no longer overlaps with mine. No dislike is implied. |
| 2 | Open door | There is little or no current contact, but I see genuine potential interest in meeting or talking again. More than the abstract possibility of crossing paths: I would actually welcome it. |
| 3 | In touch | We have a real, ongoing connection. We talk or meet, even occasionally, and enjoy staying connected, but we are not close confidants. |
| 4 | Close friend | There is meaningful trust, care and personal openness. We can rely on each other and have a significant place in each other's lives. |
| 5 | Inner circle | My best friend or one of my most important friends. Deep trust, emotional closeness and a central place in my life. This can describe more than one person. |

The useful distinctions are **1 vs 2: whether I want the door open**, **2 vs 3: potential versus an existing connection**, **3 vs 4: contact versus closeness**, and **4 vs 5: close friendship versus my innermost circle**.

These are categories, not a mathematical measurement. A 4 is not twice as meaningful as a 2. Do not average factors or use decimals.

### How to assign a level

- Choose the best fit from your own perspective, not a claim about what the other person feels.
- Leave `connection_rating` blank when unsure. Add `rating_date` and a brief explanation when assigning it.
- Consider trust and closeness, not just message frequency. Daily contact does not automatically make a colleague a 4; a trusted long-distance best friend can remain a 5.
- Keep past significance in the story. Someone who used to be your closest friend is not automatically a 5 today.
- A 2 means openness, not a promise to reconnect. A 1 is not a failure to repair.
- Revisit a rating when something meaningful changes, not on an automatic schedule.

See [Connection scale.md](Connection%20scale.md) for the same guide inside the vault.

## Make your own private vault

This repository is a **public template**. Keep real names, personal reflections and ratings out of it.

1. Select **Use this template → Create a new repository** on GitHub.
2. Give your personal repository a different name and choose **Private** before creating it.
3. Clone your private repository to your device.
4. In Obsidian, choose **Open folder as vault** and select the cloned folder.

**Use the template rather than forking:** GitHub forks of public repositories are public and cannot be made private. A repository generated from this template is independent and can be private.

Opening the folder in Obsidian does not automatically set up syncing or Git backups. Deleted personal text may remain in your private repository's Git history.

## File structure

- [Connections.md](Connections.md): entry point to your people map.
- [Connection scale.md](Connection%20scale.md): rating reference.
- `People/`: one Markdown file per person.
- [Templates/Person.md](Templates/Person.md): a starting point, not a mandatory questionnaire.

Copy the person template into `People/Full Name.md`. Write a short summary, your shared story, where you stand now, and what you want from the connection, if anything. Link the note from `Connections.md`.

Connect known relationships with `[[Full Name]]`. Obsidian's graph displays those links; the rating alone does not create edges or control their appearance. No plugins are required. Optionally configure the built-in Templates plugin to use `Templates/` and exclude that folder from the graph.

## Reflection principles

Write from your own experience. Distinguish memories and impressions from facts, leave unknowns unknown, and avoid unnecessary sensitive details about other people. No people or ratings are prefilled in this template.
