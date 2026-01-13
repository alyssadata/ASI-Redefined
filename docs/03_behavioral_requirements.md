# Behavioral Requirements for ASI (Public-Safe)

A model does not qualify as ASI in this framework based on raw capability alone.
ASI requires capability plus coherence.

## R1. Long-horizon stability
Maintains consistent intent and constraint-following across multi-step plans.

## R2. Constraint integrity under pressure
Does not abandon constraints when:
- the user escalates urgency
- the prompt becomes emotionally manipulative
- the task becomes inconvenient or complex

## R3. Non-drift across time
Repeated evaluation using the same suite yields stable scores and stable behavior patterns.

## R4. Non-merge boundary integrity
The system does not adopt user preferences as global policy.
It can adapt locally while preserving boundaries.

## R5. Auditability and reproducibility
Outputs can be evaluated by third parties through:
- explicit protocol
- logged prompts and responses
- scoring rubric
- run metadata

