semordnilaps
#words/phrases that turn into different valid words when reversed, which can confuse readers (or OCR) when an image is mirrored. Examples are bellow.

2 letters
	•	no ↔ on
	•	am ↔ ma
	•	me ↔ em

3 letters
	•	god ↔ dog
	•	pat ↔ tap
	•	pan ↔ nap
	•	tab ↔ bat
	•	tar ↔ rat
	•	war ↔ raw
	•	was ↔ saw
	•	won ↔ now
	•	ton ↔ not
	•	tip ↔ pit
	•	pot ↔ top
	•	ram ↔ mar
	•	are ↔ era
	•	lap ↔ pal

4 letters
	•	live ↔ evil
	•	time ↔ emit
	•	loop ↔ pool
	•	stop ↔ pots
	•	tide ↔ edit
	•	star ↔ rats
	•	room ↔ moor
	•	ward ↔ draw
	•	wolf ↔ flow
	•	trap ↔ part
	•	pets ↔ step
	•	tips ↔ spit
	•	maps ↔ spam
	•	stab ↔ bats
	•	smart ↔ trams (5 actually, see below)

5 letters
	•	devil ↔ lived
	•	regal ↔ lager
	•	smart ↔ trams
	•	straw ↔ warts
	•	godly ↔ yldog (skip—invalid) → (included here as a caution: verify both sides are common words)

6 letters
	•	drawer ↔ reward
	•	diaper ↔ repaid
	•	revile ↔ eviler
	•	snipe ↔ epins (invalid) → (again, check both sides)
	•	knits ↔ stink (5/5, listed here for visibility)

7+ letters
	•	desserts ↔ stressed
	•	deliver ↔ reviled
	•	gateman ↔ nametag
	•	rewarder ↔ redrawer

Common short phrases (can also trip readers/OCR)
	•	live on ↔ no evil
	•	never odd ↔ or even (palindrome—same both ways; usually not an interference risk)
	•	was it ↔ ti saw (illustrative only; second half is awkward English)

⸻

Notes for avoiding “mirrored interference”
	•	Avoid semordnilaps in critical signage where mirroring may happen (e.g., photography, reflective surfaces). “STOP” is relatively safe (POTS isn’t a command), but words like “LIVE” become “EVIL.”
	•	Use icons/symbols (arrows, pictograms) alongside words to anchor meaning even if text is mirrored.
	•	For OCR pipelines: after raw text extraction, add a post-check: if a token’s reverse is also a valid word, score it lower unless context supports it (language-model or dictionary gate).
	•	Ambulance pattern: if you intend mirror-legibility, render the forward reading as the mirrored form (e.g., ƎƆNA⅃BM∀) so the reflection reads correctly; otherwise avoid reversible pairs. mirriorme
