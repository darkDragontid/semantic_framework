### System Principles
This set of principles is a tactical development and implementation of the meta-principle of Architectural Distribution of Complexity. They ensure the system's integrity, machine-readability, and practical applicability at the operational level.

#### 1. Fundamental Principles

Principles that define the system's philosophy and form the basis for all other rules.

- 1.1 Principle of Semantic Distribution: Every element of meaning must be consciously placed in the field intended for it.

- 1.2 Principle of Contextual Dependency: The theme and focus fields are not rigid labels and depend on the perspective from which the note is considered.

- 1.3 Principle of Multiple Interpretation: A single note can be assigned several theme/focus pairs, representing different perspectives of its content.

- 1.4 Principle of Permissible Emptiness: If there is insufficient information to fill a field, it must remain empty.

#### 2. Structural Principles

Principles that define the architecture and organization of data.

- 2.1 Principle of Progressive Specification: The movement during tagging should go from general to specific (domain → category → theme/focus).

- 2.2 Principle of Redundant Linking: Key composite tags must be supported by simpler, atomic tags in other fields.

#### 3. Practical Rules (Implementation Instructions)

Instructional rules for consistent and clean system population.

- 3.1 Rule of Sequence: Fields must be filled in a strict order.

- 3.2 Rule of Layer Purity: Mixing meanings between fields is not allowed.

- 3.3 Rule of Relevant Multiplicity: All relevant values must be selected for each field.

- 3.4 Rule of Machine Decomposition: Compound tags must be automatically broken down into words in the components field.
