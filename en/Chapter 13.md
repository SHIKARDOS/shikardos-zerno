# CHAPTER 13. PRACTICAL APPLICATION OF THE METHODOLOGY TO SHIKARDOS TASKS AND COMPARATIVE EVALUATION OF RESULTS

## 13.1. SHIKARDOS as a practical proving ground for the method

The verification of a methodology requires real tasks. Such a proving ground in the present work is the SHIKARDOS project — a music player created as "honest sound", without marketing embellishment and without fictitious "enhancers".

The choice of this proving ground is not accidental. The project arose from a conviction that shares the original intuition of the Grain Principle: a good solution grows out of an honest study of what has already been done, and not out of a promise to invent everything anew. The player was built from the very start as a result of collection and synthesis, long before this process received a name.

The present chapter shows how the stages of the method — collection, map, synthesis, birth, verification — show through in the real history of the player's creation, and evaluates what this experience gives for the verification of the methodology.

## 13.2. Task definition: honest sound

The starting point was a task definition formulated by the project's founder: to create a player that gives crystal-clear sound without deception — without advertising "improvements", without fake visualizations, without collecting user data.

In the terms of the Grain Principle this definition at once set the target function — honest, technically deep sound reproduction — and the constraints — the rejection of everything that contradicts honesty. The definition determined what exactly would be collected and what would be rejected in advance.

It is important that the definition was formulated before collection, and not after the fact. This corresponds to the first contour of the method: the task precedes the search and directs it.

## 13.3. Collection: studying the experience of predecessors

The collection stage expressed itself in the systematic study of what people had asked of players over many years. Large forum topics devoted to competing players were read in full: the Poweramp topic (thousands of pages of discussion over a decade and a half), the USB Audio Player PRO topic, the AIMP topic.

Such collection corresponds to all three directions of the method. The historical direction gave an understanding of how user requests developed and which solutions accumulated over the years. The horizontal direction transferred principles between different players and approaches. The abstract direction ascended from concrete requests to general functions — navigation, amplification, equalization, stability of playback.

Collection was conducted by the blind-bee rule: not only obvious wishes were recorded, but also those that contradicted the initial notions of a "correct" player. The discarded was written down with reasons, and did not disappear silently.

## 13.4. The Grain Map: one hundred functions

The result of collection was reduced to a Grain Map — an ordered list of the functions people expect from a player, with an honest mark on the state of each: whether it is implemented in the project, implemented partially, or absent.

The map was kept by the rule fixed in Chapter 8: each record is a function, not an outward form, and each has evidence in the code — a concrete file and line where the function is implemented. A record without evidence was not considered confirmed.

This manner of keeping the map performed two tasks of the method at once. First, it translated scattered user requests into the language of functions, making them comparable. Second, it separated the claimed from the actually done: the map records not "what we promise" but "what is verified by the code".

## 13.5. Synthesis and birth: one's own engine and one's own equalizer

From the map grew concrete solutions in which synthesis and birth showed through most distinctly.

The first is one's own sound engine, outputting the signal to an external digital-to-analog converter bypassing the system path. This solution assembled several grains: accuracy of transmission (bit for bit), direct control of the device, bypassing intermediaries. Synthesis joined them into a structure; birth gave a working mechanism possessing a property absent from the source grains separately — a clean path independent of the operating system.

The second is an equalizer built on one's own model of the interconnections of sound parameters. Here horizontal collection transferred principles from different representations of equalization, and synthesis arranged them into a single control system where one point leads several sides of the sound by a given model.

Both cases are united by a common feature: the result is not reducible to a list of borrowed functions but forms a whole that differs from any of the predecessors. This is the emergent quality recorded by the criterion of wholeness.

## 13.6. Verification and comparative evaluation

Verification in the project was conducted by criteria close to those introduced in Chapter 11. Novelty was established by comparison with competitors; functional usefulness by real use on devices; wholeness by the absence of critical contradictions; realizability by working builds.

An honest evaluation requires acknowledging the boundaries as well. The SHIKARDOS experience is not a controlled experiment in the strict sense: the comparison with an alternative method was not conducted by a pre-fixed protocol with independent evaluators. Therefore the results of this chapter should be treated as an illustration of the applicability of the method, and not as strict proof of its superiority.

Nevertheless the experience gives ground for a cautious conclusion: the consistent application of collection, functional map, synthesis, and verification allowed the project to accumulate solutions reproducibly and not to lose what was achieved. This agrees with the working hypothesis, though it does not fully confirm it.

The full experimental verification of the methodology on independent tasks, with a formal protocol and control, constitutes the subject of further research and is separated from the illustrative application presented in this chapter.

---

*First authorial edition. Eley, 26.11.2026.*
