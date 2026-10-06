# IT265 Module 2: Design and Development Journal First Entry

This records design reasoning. Keep your weekly GitHub dev log separately.

## Entry Details

**Date:** Fall 2026

**Working game title:** JoJos Bizarre TCG

**Project stage:** Concept Workshop & Scoping Phase

**Entry type:** Concept Decision & Scoping Journal

## Concept and Decision

**Current concept and intended experience:**
A 1v1 tactical card game where players manage mana/shards to deploy units, arm weapons, and set face-down traps, and once having 6 mana they can attaches a dormant Stand to there leader. Rewarding resource patience and strategic bluffing.

**Design question or decision:**
How do we make the Stand awakening feel powerful while giving both players a fair advantage?

**Selected concept and alternatives kept:**
* **Selected:** JoJos Bizarre TCG due to strong thematic hook and I know more about the anime to help bring concepts and ideas to life.
* **Kept for Later:** The tile-based maze traversal and dynamic hazard mechanics from To the Bottom.

**Peer feedback that affected the decision:**
Classmates and a close friend of mine stated that full TCGs carry severe scope risk due to complex card libraries. This feedback led directly to restricting the initial test to two small, pre-constructed 20–25 card dual-color decks instead of tackling a 50+ card freeform deckbuilder(Too much for just one person).

## Reading Connection

Choose one idea from Chapter 1: Having the Idea, The Treatment, or Feasibility.

**Section and specific idea:**
Feasibility — The principle of reducing a complex systemic game to its smallest testable core loop.

**Relevance today:** Still relevant

**Reason and supporting example:**
TCGs are known for updating and coming out with new sets that create more functions and more ways to play but for one person with an idea taking it down a scale to see the core ideas is best for time and overall idea making the machnics fun before anything.

**Connection to a choice or test for my game:**
This directly inspired cutting out the full 5-color deck construction rule and focusing exclusively on two pre-built dual-color decks to test the 6-mana Stand search/attachment trigger and traps.

## Progress and Evidence

**What I created, changed, tested, or decided:**
* Defined the 6-card face-down life pool mechanism and resource shard curve.
* Designed the "Stand Awakening" rule: upon hitting 6 mana, players can tutor their Stand directly from their deck to attach to their Leader if not yet drawn.
* Implemented face-down trap cards that cost mana upfront to guard against life attacks.
* Established a fail-safe reshuffle rule if all Stand cards are trapped inside life cards(For test make sure that shards are in the deck and not in life only for the test).

**Direct artifact link or specific observation:**
Drafted system mechanics and treatment in [05-one-page-treatment.md](./05-one-page-treatment.md) and concept boundaries in [04-select-and-scope.md](./04-select-and-scope.md).

**What the evidence confirms:**
Having fixed life cards and dedicated mana shard ramp ensures players have a clear countdown towards Stand awakening.

**What remains uncertain:**
Whether the defense capabiltys with a face down traps stall the game to much or does nothing. 
## Rough Gameplay Timing Onion

Describe the nested activities in words or a simple diagram. The table is a starting point; timings are tentative, not measurements unless tested.

| Layer | Player activity or outcome | Tentative timing |
| --- | --- | --- |
| Immediate decision | Draw a card, decide whether to play a mana shard, deploy a unit, set a trap, or declare an attack | 15–30 seconds |
| Larger objective | Mana ramp to 6 shards to search deck, attach Stand to Leader, and penetrate the opponent's 6 life cards | 3–6 minutes |
| Session | Complete a full 1v1 match by depleting opponent's life to zero or winning through deck exhaustion | 10–15 minutes |

Keep the working model in the journal. The treatment needs only the timing context that helps a reader understand play.

## Next Action

**Next prototype, reader test, or design decision:**
Create a physical paper prototype using two sets of 20 index cards with basic handwritten power/cost values.

**Uncertainty it will address:**
Verifying whether drawing mana shards from the main deck feels balanced or not if its to much.
