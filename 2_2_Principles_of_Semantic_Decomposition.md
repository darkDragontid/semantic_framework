### Principles of Semantic Decomposition

#### I. Fundamental (Immutable) Principles

These principles define the system's philosophy for interacting with meanings and connections, forming the foundation for machine readability and consistency.

1. Principle of Context Independence (Atomicity of Analysis)
- Formulation: Each unit of analysis (note, text) is processed in isolation, without considering the history of previous interactions or global context. Semantic interpretation is derived solely from its own content.
- Goal: To ensure reproducibility and eliminate cascade errors during analysis.
2. Principle of Tolerance for Empty Values
- Formulation: Fields for which the analyzed text provides insufficient information or semantic signals must remain empty. Forcing the filling of all fields is prohibited.
- Goal: To prevent semantic noise and false precision. Data quality takes precedence over data completeness.
3. Principle of Plurality of Perspectives
- Formulation: The same unit of analysis can have multiple equally valid but different semantic interpretations, representing different perspectives (e.g., functional, psychological, ethical).
- Goal: To reflect the multifaceted nature of meaning and to avoid reduction to a single "correct" interpretation.
4. Principle of Contextual Specification (Uniqueness within a Perspective)
5. - Formulation: Within a single interpretive perspective (interpretation), only one value can be assigned to each field of the semantic hierarchy (domain, category, theme, object). This ensures semantic purity and unambiguous interpretation from that specific viewpoint.
-  Goal: To preserve the logical integrity and consistency of an individual view of the text.
5. Principle of Semantic Allocation
- Formulation: Every element of meaning must be consciously placed in the system field intended for that type of semantic information (e.g., an object goes in object, an operation in operation, an explicit mention in keywords).
- Goal: To ensure the purity of data layers and their suitability for machine analysis.

---

#### II. Practical Simplifications

These decisions are tactical simplifications for implementing the system without full automation and professional decomposition, enabling simple semantic tagging without losing its key functional capabilities.

Simplified Implementation of 'Uniqueness within a Perspective':

- Essence: Instead of storing multiple strictly linked sets of fields (perspective_1: {domain, category, theme, object, ...}, perspective_2: {domain, category, theme, object, ...}), the system allows placing all relevant values for a single field at a generalized level (e.g., all theme values in one field).
- Compromise: The strict linkage of theme and object values within a unified interpretive perspective is lost. However, the possibility of multidimensional analysis is retained through the presence of multiple values.
- Justification: This simplification significantly reduces implementation complexity (for both humans and machines).
