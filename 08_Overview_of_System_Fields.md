### Overview of System Fields

***domain (domain)***

Purpose: The largest sphere of activity or knowledge to which the note belongs.

Boundaries: Selected from a predefined list. Multiple values can be specified.

Requirements: Only values from the list.

Values: Fixed set:
- _Experience_: Everything related to personal, subjective experience: internal states, experiences, biographical events, self-observation.
- _Society_: Social structures, groups, institutions, norms, culture, communication between people.
- _Science_: Objective cognition, research of patterns, work with data, theories, hypotheses.
- _Creativity_: Creating new things: art, design, innovation, narratives, expressing ideas in form.
- _Technology_: Creation and application of tools, programs, systems, engineering solutions, process optimization.
- _Management_: Organization of resources, projects, processes, people, and oneself to achieve goals.
- _System_: Design and analysis of complex structures, rules, interconnections, and abstract models.
- _Collection_: A sphere responsible for the storage format: collections, lists, catalogs, archives (NOT thematic!).



****category (category)***

Purpose: The type of activity or material.

Boundaries: Not a thematic tag. Defines the format of interaction with information.

Requirements: Only values from the list.

Values: Fixed list (see Appendix). Example: "Reflection", "Project", "Quote".

***theme (object)***

Purpose: A broad phenomenon, problem, or object of consideration.

Boundaries: Not a specific event, name, or emotion.

Requirements: Prepositions, verbs, abbreviations are prohibited.

Values: Composite tags in the format Adj_Noun or Noun_Noun (e.g., artificial_intelligence).

***focus (subject)***

Purpose: A specific aspect or angle within the theme.

Boundaries: Always used in pair with theme. Not an independent concept.

Requirements: Prepositions, verbs are prohibited.

Values: Composite tags in the format Adj_Noun or Noun_Noun (e.g., AI_ethics).

***Meta-Layer interpretations***
A higher level of abstraction in the system, intended to manage not the content of the note, but its interpretations.
If the main fields (theme, focus, related) answer the question "What does this mean?", the meta-layer answers the question: "In what different ways can this be interpreted?".
This is the layer that:

Groups various theme/focus pairs under different perspectives (perspective).

Manages ontological rules (e.g., which category is allowed for which domain).

Describes the process of meaning creation itself, not its result.

Simply put, it is the "interface" for managing the multidimensionality of a single note's meaning.

***keywords (keywords)***

Purpose: Names, terms, objects explicitly mentioned in the text.

Boundaries: Only concepts directly mentioned in the text.

Requirements: Set phrases and prepositions are allowed.

Values: Nouns, proper names, terms (e.g., Lomonosov, Python, black_hole).

***operation (operation)***

Purpose: The type of mental operation performed on the information.

Boundaries: Not a thematic tag or emotion.

Requirements: Only single-word tags.

Values: Atomic tags: analysis, comparison, synthesis, question.

***emotion (emotion)***

Purpose: The emotion or mood conveyed by the text.

Boundaries: Only emotions, not operations or objects.

Requirements: Only single-word tags.

Values: Atomic tags: anxiety, curiosity, calm.

***context (context)***

Purpose: The circumstances, time, or place discussed in the note.

Boundaries: The context of the content, not of the note's creation (that is meta_context).

Requirements: Prepositions and complex forms are allowed.

Values: Set phrases: covid_pandemic, office, summer_2015.

***related (connections)***

Purpose: Fundamental concepts not explicitly named but critical for understanding.

Boundaries: Only implicit concepts. Does not duplicate keywords.

Requirements: Prepositions and verbs are prohibited.

Values: Composite tags in the format Adj_Noun or Noun_Noun (e.g., digital_immortality).

***meta_context (meta-context)***

Purpose: The circumstances of the note's creation (where, when, how it was created).

Boundaries: Only the creation context, not the content.

Requirements: Any practically useful formats are allowed.

Values: Arbitrary formats: 2024_09_26, conversation_with_Anna, nocturnal_insight.


***action (action)***

Purpose: Utilitarian notes for managing tasks related to the note.

Boundaries: Does not carry semantic load about the content.

Requirements: Maximum pragmatism, any formats.

Values: Arbitrary formats: urgent, to_read, draft.

***created_date***

Purpose: A strict, machine-readable timestamp of the exact moment a note was created. Used for building precise timelines and analyzing the evolution of thoughts and ideas.

Boundaries:

- Set once at the moment of note creation and never changed.

- Contains only the timestamp. All subjective context (e.g., "late_night", "inspiration") remains in the meta_context field.

Requirements:

- Must be populated automatically by the system or editor upon file creation.

- The format is mandatory for machine readability.

Values: Date and time in ISO 8601 (UTC) format: YYYY-MM-DDThh:mm:ssZ.

_Example: 2024-05-27T19:32:45Z (May 27, 2024, 19:32:45 UTC)._

