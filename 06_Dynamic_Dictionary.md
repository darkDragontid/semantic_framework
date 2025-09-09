### Dynamic Dictionary for theme/focus

The dictionary is designed to ensure consistency and reusability of tags at the theme and focus levels. It solves the problem of synonym conflict—when the same concept can be named by different words (e.g., AI, machine_mind), which leads to semantic blurring and makes machine analysis impossible. It is not rigidly fixed but is dynamically updated, serving as a growing semantic core.

Rigidity and Flexibility: Resolving the Conflict

The system uses two complementary modes to resolve this conflict, ensuring a balance between machine-readability and human convenience:

#### Rigid Canonical Core (For the system):

- What it is: A single, strictly normalized form of a tag that complies with all linguistic rules (e.g., artificial_intelligence).

- Purpose: Ensures machine-readability, consistency, and reusability. Only canonical tags are used for building graphs, analyzing connections, and AI training. This guarantees that the system operates with unified concepts, not disparate text strings.

#### Flexible Input Interface (For the user):

What it is: The ability to use any familiar synonyms and spelling variants (e.g., AI).

- Purpose: Provides cognitive relief and a natural workflow. The user should not have to remember and manually enter long canonical forms. The system handles the work of converting synonyms into a single standard.

- Operating Principle:

  - Population: A new canonical tag form (e.g., artificial_intelligence) and its synonyms (AI) are added to the dictionary.

  - Normalization: When a user enters a synonym, the AI assistant automatically finds and suggests replacing it with the canonical form.

Visualization and Analysis: All operations within the system (search, graphs, analysis) are performed only with canonical forms, ensuring their accuracy and reliability.

Thus, the system resolves the synonym conflict not through prohibition but through intelligent transformation, preserving flexibility for the human and maintaining rigidity and order for the machine.
