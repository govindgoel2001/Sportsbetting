# WC2026 FINAL â€” Argentina vs Spain

**MetLife Stadium, East Rutherford NJ â€” Sunday July 19, 2026, 3:00 PM ET**
Model: `worldcup-ledger-v1` (Dixon-Coles + Elo + Monte Carlo + adaptive form ensemble)
Locked prediction run: `595ba571-f061-4d04-a3c8-a731e2ddad8c` (2026-07-19, pre-match)

---

## 1. Model track record this tournament

Ledger convention: knockout scores counted after extra time; shootout games count as draws (that's how the results feed records them). Every pick below was locked pre-match with market odds attached.

### All games since the tournament started

| Stage | Picks | Correct | Hit % |
|---|---|---|---|
| Group stage (72 games) | 72 | 42 | 58.3% |
| Round of 32 | 16 | 13 | 81.3% |
| Round of 16 | 8 | 6 | 75.0% |
| Quarterfinals (2 picks locked) | 2 | 2 | 100% |
| Semifinal (Franceâ€“Spain) | 1 | 1 | 100% |
| **Total** | **99** | **64** | **64.6%** |

- On **decisive games only** (no 90/120-min draw): **64/75 = 85.3%**.
- The model's one systemic weakness is unchanged all tournament: it predicted **zero draws** while 26% of games ended level. Every group-stage miss but a handful was a draw it refused to see coming.

### Knockout rounds only

| Basis | Record | Hit % |
|---|---|---|
| 3-way result picks (draws count as misses) | 22/27 | **81.5%** |
| "Who advanced" basis | 23/27 | **85.2%** |

The four advancement misses: Paraguay over Germany (pens), Egypt over Australia (pens), **Norway over Brazil** (the shock of the round of 16), and Switzerland over Colombia (pens). The model called Morocco past the Netherlands on the night it went to pens, so that one flips to a hit on advancement.

Late-round picks just settled, all three hits:
- **QF:** England over Norway (52.3%) â†’ Norway 1â€“2 England (AET) âœ…
- **QF:** Argentina over Switzerland (56.0%) â†’ Argentina 3â€“1 Switzerland (AET) âœ…
- **SF:** Spain over France (39.0% vs 32.8% â€” model disagreed with the market, which had France) â†’ France 0â€“2 Spain âœ…

---

## 2. The road to the final

### Argentina â€” played 7, won 7 (19 scored, 7 conceded)
3â€“0 Algeria Â· 2â€“0 Austria Â· 3â€“1 Jordan Â· **R32** 3â€“2 Cape Verde Â· **R16** 3â€“2 Egypt Â· **QF** 3â€“1 Switzerland (AET, 1â€“1 at 90) Â· **SF** 2â€“1 England (down 0â€“1 at 84', Enzo FernÃ¡ndez 85', Lautaro MartÃ­nez 90+2 â€” both assisted by Messi)

Pattern: they score in bunches, they concede more than a champion should, and **they own the last 15 minutes**. Two straight knockout games decided after the 85th minute. Messi has 8 goals, tied with MbappÃ© for the Golden Boot, plus the two semifinal assists.

### Spain â€” played 7, won 6 drew 1 (13 scored, 1 conceded)
0â€“0 Cape Verde (their only blemish) Â· 4â€“0 Saudi Arabia Â· 1â€“0 Uruguay Â· **R32** 3â€“0 Austria Â· **R16** 1â€“0 Portugal Â· **QF** 2â€“1 Belgium Â· **SF** 2â€“0 France

Pattern: **one goal conceded in seven games.** They strangle you with possession, defend with the ball, and have not trailed for a single minute of this World Cup.

---

## 3. Model output for the final (locked)

Inputs after settling all results through the semifinals: Elo **Spain 2252 vs Argentina 2217** Â· adjusted scoring priors Spain 2.27/0.75 vs Argentina 1.97/0.67 Â· xG proxy 1.62 vs 1.59 Â· H2H 6Wâ€“2Dâ€“6W across 14 meetings (dead even).

### 90-minute probabilities

| Outcome | Model | Market (devig, FD +125/+200/+260) | Edge |
|---|---|---|---|
| **Spain win** | **38.3%** | 33.6% | **+4.7%** |
| Draw | 29.7% | 33.3% | âˆ’3.6% |
| Argentina win | 32.0% | 33.1% | âˆ’1.1% |

Expected goals: **Spain 1.12 â€“ 1.09 Argentina**. Most likely scorelines: **1â€“1 (15.1%)**, 0â€“0 (12.7%), 1â€“0 (10.5%), 0â€“1 (10.2%), 2â€“1 (7.5%), 1â€“2 (7.3%).

### To lift the trophy
Splitting the 29.7% draw branch through extra time and penalties â€” where Argentina get the edge (two ET wins this tournament, the deepest bench of super-subs, and Dibu MartÃ­nez, the best shootout keeper of his era) â€” the trophy probabilities land at roughly:

> **Spain â‰ˆ 52% â€” Argentina â‰ˆ 48%**

This is a genuine coin flip with a Spain lean in regulation and an Argentina lean the longer it goes. Betting note: the model's only positive edge is Spain 90-min ML (+4.7%), but distribution confidence is just 11.2, so **Kelly stake = 0%. No bet.** This is a watch-the-game final, not a bet-the-game final.

### On the pre-tournament Argentina call
The model picked Argentina to win it all before the group stage. That call is still live at ~48% â€” one game from being right. But honest revision is the whole point of the ledger: with Spain's defensive record (1 goal conceded), the higher Elo, and France dispatched 2â€“0, the updated numbers make **Spain the narrow favorite in 90 minutes**. If Argentina lift it, the most likely route is exactly the one they've been rehearsing: level deep into the second half, then Messi and the bench win it late.

---

## 4. How the final unfolds â€” minute by minute

**Expected setups.** Spain (de la Fuente, 4-3-3): Unai SimÃ³n; Carvajal, Le Normand, CubarsÃ­, Cucurella; Rodri, FabiÃ¡n Ruiz, Pedri; Lamine Yamal, Oyarzabal, Nico Williams. Argentina (Scaloni, 4-4-2 out of possession / 4-3-3 with the ball): Dibu MartÃ­nez; Molina, Romero, Otamendi, Tagliafico; De Paul, Enzo FernÃ¡ndez, Mac Allister; Messi free behind JuliÃ¡n Ãlvarez.

**0â€“10' â€” The feeling-out.** Spain will have 65%+ of the ball inside five minutes; that's been true in every game they've played. Argentina drop into their compact mid-block, front two screening Rodri. The one Argentine wrinkle: they've scored inside 12 minutes twice this knockout stage (Mac Allister 10' vs Switzerland) â€” watch the first set piece and the first De Paul long diagonal for Ãlvarez in behind Cucurella.

**10â€“25' â€” The Yamal problem.** The tournament's defining individual matchup: **Lamine Yamal vs Tagliafico**, with Mac Allister forced to double. Every time Argentina double the right, Pedri switches to Nico Williams 1v1 on Molina. This is how Spain broke France. If Argentina's fullbacks survive this window without a card, the game plan is intact. Probable first hydration break ~22' in the July heat â€” Scaloni uses these like extra timeouts.

**25â€“45' â€” Spain's kill window.** Spain have scored the bulk of their goals between 25' and half-time, when the opponent's block gets tired of chasing. Rodri starts finding third-line passes; FabiÃ¡n Ruiz arrives late in the box. Model says ~55% chance at least one goal before the break, and it's more likely Spanish. Argentina's counter-threat: Messi drifting into the right half-space, where Cucurella has to choose between him and Yamal's rest-defense duties.

**HT â€” The adjustment.** If Spain lead: de la Fuente changes nothing; Spain have never trailed and will simply pass you to death. If level or behind: Scaloni is the best in-game manager in international football â€” expect a shape change (back three vs Yamal has been his away-day answer) before any personnel move.

**45â€“60' â€” Argentina's press raise.** Argentina come out for the second half pressing higher â€” they did it against England (Gordon's goal at 55' came against the run of that press, but it also created the territory that won the game). Ãlvarez's channel running at CubarsÃ­ (21, magnificent, but final-debut nerves are real) is the target.

**60â€“75' â€” The bench war.** Scaloni's wave: **Lautaro MartÃ­nez ~70'** (3 goals as a sub this tournament, including the QF sealer and the SF winner), Paredes to lock midfield. De la Fuente counters with Dani Olmo and fresh wingers. Model has this as the highest-variance window: legs go, the block stretches, and both teams' xG per minute roughly doubles from here to the end.

**75â€“90' â€” Argentina's kingdom.** The numbers say it plainly: Enzo 85' and Lautaro 90+2 beat England; Ãlvarez 112' beat Switzerland. Spain have conceded exactly one goal all tournament â€” but they haven't defended a one-goal lead against Messi with the World Cup on the line. **The model gives a 30% chance we're level at 90.** If Spain lead by one here, expect seven-plus minutes of stoppage, Dibu up for corners, and Romero playing striker.

**ET (probability ~30%) â€” Advantage Argentina.** Two extra-time wins in this tournament, a deeper bench, and a squad that has made peace with chaos. Spain's possession game gets harder with tired legs and a stretched pitch â€” exactly when Messi's walking playmaker mode is most lethal.

**Penalties (~12% of all outcomes) â€” Advantage Argentina, decisively.** Emiliano MartÃ­nez: 2022 final shootout, 2024 Copa, a career built for this. If it reaches spot kicks, the pre-tournament Argentina pick probably gets its vindication.

**Behaviour to expect:** a cagey, tactical first hour, not a shootout (model total xG 2.2); Argentine game-management "dark arts" from the 60th minute if level or ahead; cards for the Argentine fullbacks dealing with Yamal/Williams; heavy emotional weight â€” this is very likely **Messi's last World Cup match**, against the 19-year-old (Yamal) the sport has anointed as next. Legacy game.

---

## 5. Verdict

**Model pick (90 min): Spain, 38.3% â€” the narrowest favorite call of the tournament.**
**Trophy: Spain ~52 / Argentina ~48.** The deeper into the night it goes, the more Argentine it gets.
**Score most likely: 1â€“1 at 90.** From there: extra time, and either Lautaro off the bench or Dibu in the shootout â€” or Spain's one moment of Yamal magic settles it inside regulation and the ledger closes at 65% for the tournament.

*Settled through the semifinals. Bronze final (Franceâ€“England, Jul 18) pending in the data feed â€” England led 2â€“0 (Rice 3', Konsa 18') in the last live snapshot; no pick was locked on it. Ledger updates after tonight's final.*
