# Idleon Injector

This context defines the account-facing language used when inspecting and editing Idleon game data.

## Language

**Account Card**:
A card represented in the current account's card collection, regardless of its current amount or tier.
_Avoid_: Defined card, available card, owned card

**Card Amount**:
The number of copies of an Account Card currently held by the account.
_Avoid_: Card count, card value

**Card Definition**:
Game-authored metadata for a card, including its monster identity and base tier requirement. A Card Definition can exist without a corresponding Account Card.

**Card Region**:
A game-authored category of Card Definitions, such as a world, resource difficulty, dungeon, boss and nightmare, or event. An Account Card belongs to the Card Region containing its matching Card Definition.
_Avoid_: Card group

**Unresolved Account Card**:
An Account Card whose Card Definition or display name cannot be resolved from the current game metadata. Its Card Amount remains meaningful even when its tier or Card Region cannot be determined.
