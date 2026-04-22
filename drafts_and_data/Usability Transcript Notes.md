# Usability Transcript Notes

These notes summarize the auto-generated transcripts extracted from the interview audio archive. The questionnaire PDF is still the cleanest source for direct quotes, but the transcripts are useful for observing task flow, hesitation, failed navigation paths, and think-aloud reactions during testing.

## Transcript Files

- `transcripts/Arya_usability_audio.txt`
- `transcripts/brian_usability_audio.txt`
- `transcripts/daniel_usability_audio.txt`
- `transcripts/krish_usability_testing.txt`
- `transcripts/silas_usability_audio.txt`

## How To Use These

- Use the questionnaire PDF for polished direct quotes.
- Use the transcripts for task-by-task evidence about confusion, dead ends, and navigation behavior.
- Treat transcript wording as approximate, since the speech-to-text output has some noise and repeated filler words in places.

## Cross-Participant Patterns

1. Search and navigation were inconsistent.
Participants often relied on search, top navigation, or trial-and-error rather than following a clear path. Several users only succeeded after scanning multiple menus or pages.

2. The air quality task was especially confusing.
Users struggled to connect county-level search results to the air quality index and were often redirected to a different page or external site with little context.

3. Reporting a storm hazard was hard to discover.
Participants expected an obvious "report" action, but instead had to guess through search or unrelated menu labels.

4. The hourly forecast graph existed but was hard to interpret.
Even when users reached the graph, they still had to parse a dense technical display to answer a basic question like the 6 AM forecast.

5. Users repeatedly described the site as cluttered, old, or overloaded.
That reaction appeared both during tasks and in post-test reflections, which strengthens the case that the issue was not isolated to one screen.

## Participant Notes

### Arya / Nick

- Immediately noticed multiple search areas and chose the one that "seems more intuitive."
- Found the hottest-temperature task only after digging into a Georgia observations page.
- Reached air quality by following an `Additional Information` link, then had to guess geographically on a separate page.
- Said reporting a storm was not obvious and eventually had to search for it directly.
- Reached the hourly graph, but called it "very technical at first" and had to interpret multiple charts to answer the question.

Useful evidence:
- Search affordances are unclear.
- Important tasks are possible, but usually after extra scanning and guesswork.
- The hourly forecast view exposes too much technical information for a simple everyday task.

### Brian / Ivan

- Struggled to locate thunderstorm forecast information through normal browsing.
- Could not confidently determine county-level air quality through the site flow.
- Found volunteer information more easily than other tasks.
- Needed help or very specific paths for some forecasting tasks.
- Described the website as "more like a scavenger hunt rather than an education service."

Useful evidence:
- Core tasks were harder than secondary informational tasks.
- Discoverability is a bigger issue than lack of information.
- The site structure forces users to hunt for the first correct click.

### Daniel / Vinicius

- Tried using `Command + F`, which suggests the page was too dense to scan normally.
- Could not complete the thunderstorm forecast task cleanly.
- Failed the county air quality task.
- Could not find a clear reporting workflow.
- Said the site was "horrible in an emergency" and that users might need Google or another outside resource instead.

Useful evidence:
- The site performs especially poorly under time pressure.
- Emergency and high-priority tasks are not surfaced well enough.
- Heavy text and menu density push users toward external search behavior.

### Krish / Tyler

- Needed prompting for some task paths, especially for the hourly graph.
- Could identify some weather pages, but still had difficulty narrowing to the right view.
- Said the website was "really bad" if a user did not already know it.
- Explicitly said the reporting task was not easy and that the closest path still did not feel correct.

Useful evidence:
- Prior knowledge heavily affects success.
- The site is less learnable for first-time users.
- The reporting workflow does not match user expectations.

### Silas / Participant 1

- Could often finish tasks, but mostly by brute-force scanning and repeated menu exploration.
- Needed to compare many Georgia temperatures manually to answer a simple hottest-city question.
- Described some tasks as "not obvious."
- Reached the hourly forecast answer only after digging through multiple linked views.
- Said the homepage map was not useful for someone who is "not in all places at once."

Useful evidence:
- Task completion does not necessarily mean the interface is efficient.
- Even successful users took indirect routes that reveal weak prioritization.
- The homepage emphasizes national alert context over the common local forecast use case.

## Best Uses In The Report

- `Findings`: support claims about hidden navigation, poor prioritization, and excessive complexity.
- `Analysis`: connect each observed failure path to a redesign decision, especially homepage simplification, navigation cleanup, and stronger forecast-first information hierarchy.
- `Visuals`: combine transcript observations with the CSV by charting which tasks caused the most hesitation, longest routes, or failed completions.
