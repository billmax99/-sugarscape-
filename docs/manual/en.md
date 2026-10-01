# Sugarscape: Life Restart — Experiment Manual (English)

> A "rebirth simulator": watch wealth inequality grow by itself in a world nobody manages.
> Gameplay: roll a life → survive → read your death report → roll again.
> This manual explains the principle, what this program implements, how to play, and how to read the results. Written for everyone.

---

## 1. The Principle (where does it come from?)

In 1996, Joshua Epstein and Robert Axtell ran a famous computer experiment called **Sugarscape**.

They wrote no storyline. They only did three things:

1. Drew a map with two **sugar mountains** (some cells hold lots of sugar, others none);
2. Dropped in **agents** that can do exactly one thing: **walk toward visible food, eat, burn it**;
3. Pressed play and watched.

**The startling findings:** with such dumb rules, the world produced —
- **A wealth gap**: some agents grew rich while others starved, though **nobody ever designed "rich" and "poor"**;
- **Class settlement**: the strong occupied fertile land, the weak were pushed to the margins;
- **Self-sustaining inequality**: even from perfect equality, the gap grows and does not heal itself.

**In one sentence: massive inequality needs no villains and no conspiracy — just "uneven resources + everyone foraging for themselves". That is the experiment's deepest lesson.**

Later researchers added spice (a second food) growing on separate mountains; agents had to **trade** to live well — and **markets and prices emerged spontaneously**.

## 2. What this program implements

![Main UI (god view)](../images/main.jpg)

| What the experiment observes | Status | Where to see it |
|---|---|---|
| Wealth gap grows by itself | ✅ full | Gini chart (bottom), 📈 Live stats |
| Poor-many / rich-few pyramid | ✅ full | Face colors: gray→yellow→brown-orange→orange-red→crimson |
| Does birthplace decide fate? | ✅ full | Birth card "fates of same-birth people", 📊 Mobility |
| How much can effort change? | ✅ beyond the original | 🏆 Local Champion, schooling, migration, "outlived AI by X turns" |
| Would perfect equality be better? | ✅ full | 🧪 A/B experiment: random vs identical talents |
| Markets & prices emerge | ✅ full | Spice ON, watch the sugar-price chart |
| Inheritance passes class down | ✅ full | Well-fed adults birth children inheriting ¼ wealth |
| Territorial war | ✅ (toggle) | ⚙ enable Culture + War |
| Ecological pressure | ✅ full | The poverty ring around mountains; overcrowding plague |

Three layers: **world simulator** (map, resources, agents), **your life** (rebirth, walking, trading, study), **observation** (charts, panels, reports).

## 3. How to play (30 seconds)

1. **Roll a life** — birthplace, talents, lifespan, starting food are all drawn. Dislike it? Reroll, pick a spot, or choose poor/middle/rich class.

2. **Live** — press "▶ Start This Life", click cells to walk (auto-harvest), study when you can afford it (+1 vision), trade happens next to neighbors.
3. **Face death** — the report shows highlights, limits, world events during your life, and (blind mode) your revealed talent cards. Every life enters the 📚 Book of Lives — click any row to replay the summary.

4. **Three ways to go again** — roll a new life; 👻 possess any living agent after death; or restart the whole world.

## 4. Classic experiments (play like a researcher)

- **Birthplace A/B**: 10 lives, 5 on the mountain, 5 in the wasteland — compare lifespans.
- **Schooling A/B**: same start, one studies, one doesn't.
- **Equality experiment**: 🧪 runs two worlds for 300 turns — random talents vs identical talents. Frequent verdict: *the equal-talent world can end up MORE unequal — inequality comes mostly from position and luck.*

- **Mobility tracking**: 📊 paints birth-class rings on the map — watch who climbs the mountain.

- **Rule switches** (⚙): redistribution tax, free education, tribal war, overcrowding plague, pure-sugar world (no trade)…
- **👁 Demo mode**: auto-plays lives with captions — perfect for showing someone.

## 5. Reading the numbers

- **Gini index**: 0 = everyone equally poor, 1 = one owner of everything. **Normal here: climbs from 0 to 0.2–0.4 and stabilizes.** A climbing curve *is* the core finding — inequality emerging without a designer.
- **Population**: stable 100–400; below 50 triggers migration.
- **Sugar price**: oscillates near 1; nobody sets it — agents haggle it into existence.
- **Wealth share**: top 10% holding 30–60% is the norm; near 100% = extreme monopoly.
- **Poverty→middle climb rate**: typically 30–50% — *effort works, but there is a ceiling.*

## 6. For kids

Imagine a playground where the teacher piles candy in only two corners and walks away. Kids standing nearby eat well; kids far away run their legs off for scraps. Nobody decided who is "poor" — the ones who can't reach the candy simply become poor. This game lets you be one of those kids and try: **if you can't choose where you start, how do you live the best life you can?**

Then you understand: **fairness is not natural — someone has to see the gap (the Gini chart), then change the rules (the ⚙ parameters).**
