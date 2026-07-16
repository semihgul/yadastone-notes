# NPC Rumor System

NPCs make the kingdom feel alive and turn player actions into social consequences. They are sources, witnesses, voters, and amplifiers—not perfect surveillance cameras.

## NPC types

- citizens: public support and local sentiment
- servants: palace routines and private access
- guards: security and suspicious behavior
- nobles: interests, leverage, and legitimacy
- priests: moral judgment and church support
- merchants: tax, wealth, and trade disruption

```mermaid
flowchart LR
    A[Event observed] --> B[Witness interprets event]
    B --> C[Rumor with confidence and bias]
    C --> D[Spread through social links]
    D --> E[Player verifies, suppresses, or weaponizes it]
    E --> F[Opinion and behavior change]
```

## Rules

- Rumors can be incomplete or false, but retain a traceable source.
- Confidence depends on perception, personality, relationships, and evidence.
- Players can bribe, intimidate, persuade, or protect sources.
- MVP uses authored, limited rumor chains before large-scale simulation.

## Related pages

[[Evidence and Trial]] · [[Power Economy]] · [[World Overview]]

