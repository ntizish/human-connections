# Human connections

An Obsidian-friendly Markdown template for mapping the people you have met throughout your life. Remember what you shared, reflect on where you stand now, and be more thoughtful about the connections you have and have had.

Not a networking pipeline or a ranking of people's worth.

## The 1–5 connection system

Five broad levels are easier to distinguish honestly than ten finely graded scores. The number describes your connection with someone, from a shared past with no remaining reason to connect to your closest people.

| Level | Name | Meaning and examples |
| --- | --- | --- |
| 1 | Shared past | We know of each other, but the context that connected us is gone. Nothing meaningful connects us now, and I see no emotional, sexual or practical reason to reconnect. No dislike is implied. (Old classmates, former acquaintances.) |
| 2 | Loose connection | Something still connects us, or there is a genuine reason or interest to meet or communicate again, but the connection is peripheral rather than solid and ongoing. (Occasional acquaintances, old contacts with a remaining shared interest.) |
| 3 | Everyday connection | We have a solid, ongoing connection through regular interaction or a shared part of life, even when the contact comes with the setting rather than a deliberate choice. We are not necessarily personally close. (Colleagues, people from shared activities.) |
| 4 | Close friend | There is personal closeness, trust and care beyond simply sharing a setting. We choose to spend time together and can rely on each other. (Close friends, friends outside work.) |
| 5 | Inner circle | One of my closest and most important people, whom I trust with most things in my life. Deep emotional closeness and a central place in my life. (Best friend, partner, mum or another close family member.) |

The useful distinctions are **1 vs 2: an ended connection versus a remaining thread**, **2 vs 3: peripheral contact versus a solid ongoing connection**, **3 vs 4: shared context versus personal closeness**, and **4 vs 5: close friendship versus my innermost circle**.

These are categories, not a mathematical measurement. A 4 is not twice as meaningful as a 2. Do not average factors or use decimals. Examples are parallels, not automatic assignments: not every colleague is a 3, every friend a 4, or every partner or parent a 5.

### How to assign a level

- Choose the best fit from your own perspective, not a claim about what the other person feels.
- Leave `connection_rating` blank when unsure. Add `rating_date` and a brief explanation when assigning it.
- Consider trust and closeness, not just message frequency. Daily contact does not automatically make a colleague a 4; a trusted long-distance best friend can remain a 5.
- Keep past significance in the story. Someone who used to be your closest friend is not automatically a 5 today.
- A 2 is not a promise to reconnect. A 1 is not a failure to repair.
- Revisit a rating when something meaningful changes, not on an automatic schedule.

## Make your own private vault

This repository is a **public template**. Keep real names, personal reflections and ratings out of it.

1. Select **Use this template → Create a new repository** on GitHub.
2. Give your personal repository a different name and choose **Private** before creating it.
3. Clone your private repository to your device.
4. In Obsidian, choose **Open folder as vault** and select the cloned folder.

**Use the template rather than forking:** GitHub forks of public repositories are public and cannot be made private. A repository generated from this template is independent and can be private.

Opening the folder in Obsidian does not automatically set up syncing or Git backups. Deleted personal text may remain in your private repository's Git history.

## File structure

- (Me.md): the central node of your personal graph. No biography is required.
- `People/`: one Markdown file per person.
- [Templates/Person.md](Templates/Person.md): a starting point, not a mandatory questionnaire.

Copy the person template into `People/Full Name.md`. Write a short summary, your shared story, where you stand now, and what you want from the connection, if anything.

### The Me point in Obsidian

Every person note created from the template includes `Connected to: [[Me]]`. That link creates an edge from the person to `Me.md`; the Me note itself can remain almost empty. You do not need to maintain a second list of links inside it.

Open **Me → Local graph** at depth **1** to see the central Me point and all person notes linking to it. Exclude `path:Templates` using the graph's filter so the template itself does not appear as a person. No people are prefilled, so the graph will acquire its connections as you add real notes in your private copy.

Connect people to each other with `[[Full Name]]` only when their relationship is known. The global graph shows those links too, alongside documentation notes. The rating alone does not create graph edges or control their appearance.

No plugins are required. Optionally configure the built-in Templates plugin to use `Templates/`.

## Reflection principles

Write from your own experience. Distinguish memories and impressions from facts, leave unknowns unknown, and avoid unnecessary sensitive details about other people. No people or ratings are prefilled in this template.
