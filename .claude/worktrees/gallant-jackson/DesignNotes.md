# Hail of Fire: Design Notes

Everything in Hail of Fire is built around two core concepts: Fire and Maneuver, and Fog of War.

You'll give orders to platoons without knowing if they'll follow. You'll fire on enemies without knowing if they're killed. You'll hit an enemy tank and watch it stop, not knowing if the crew is dead or just shaken. This is the game. Embrace the uncertainty. The chaos is where the interesting decisions live.

Some of these mechanisms might work differently than you'd expect coming from other games. What follows is an attempt to explain why the rules work the way they do — what they're meant to represent, and how they should shape the way you play.

---

## Fire Suppresses; Assaults Kill

Small arms fire at range rarely destroyed enemy positions outright. Estimates suggest around 40,000 rounds of ammunition were fired for every soldier killed during WWII. The real power in shooting wasn't lethality — it was suppression. Keeping heads down, disrupting return fire, degrading situational awareness. The real killing happened at close quarters: those last thirty yards where guns, grenades, and bayonets provided the decisive outcome.

British section tactics recognized this explicitly. The section divided into two groups: the Bren group suppressed while the rifle group — sometimes called the "assault group" — closed the distance. Once the Bren had the enemy pinned, the rifle group would throw grenades and make the final assault with the bayonet. U.S. doctrine followed the same logic. FM 7-10 (1942) emphasized that "fires are employed to reduce resistance to a minimum and to permit the attacking echelon to close with the enemy."

This is why hits in Hail of Fire stack Received Fire Points and create suppression rather than immediately killing. Teams in hard cover are very difficult to destroy with fire alone — but the same suppression that keeps them alive makes them vulnerable to assault. Any defender that isn't Ready when contacted is destroyed without fighting back. The lesson: don't try to shoot your way through a position. Suppress it, then assault it.

---

## Fire and Movement

This is the fundamental rhythm of WWII infantry combat. One element suppresses; another advances. Then they swap. Trying to move everyone at once leaves no one suppressing, which means the enemy fires freely. Trying to shoot with everyone means no one closes the distance.

FM 7-5 (1940) describes the attack as "a series of advances by which a force moves from its line of departure to a position from which it assaults the enemy." British doctrine emphasized "fire and movement" at every level — section, platoon, and company. The goal was always the same: maintain fire on the enemy while closing the distance.

In Hail of Fire, this means alternating Fire and Move orders across your units. Keep one squad shooting at that hedgerow while another works around the flank. If you stop advancing to keep shooting, your attack stalls. If you move everyone without suppressing, the enemy shoots back without interference. The trick — the whole game, really — is figuring out how to keep RFPs on enemy teams while still advancing each turn.

---

## The RFP System and Uncertainty

The shooting mechanism simulates the uncertainty a commander faces during a firefight. Rather than firing at an enemy and receiving immediate feedback — learning the exact effectiveness of each shot and the specific status of each enemy soldier — you often won't know how effective your fire was until the enemy shoots back, moves away, or you assault the position and discover their status yourself.

This reflects reality. A unit leader might never have the opportunity to see his enemy. He often only knew whether fire was coming from a specific building or section of hedgerow. Even troops moving across open ground could become impossible to identify once they hit the dirt. After-action reports consistently inflated kills; soldiers reported what they hoped had happened, not what they could verify. A position that received heavy fire might be full of dead, or the defenders might have simply kept their heads down and waited it out.

The RFP system — where the defender allocates hits secretly — recreates this uncertainty. You know you hit *something*, but not whether it mattered. Do you keep firing, or is that position suppressed enough to assault? The attacker makes choices without perfect information, just like the real thing.

The limit of one hit per Fire order per team reflects fire targeting an area rather than specific soldiers within it. Most soldiers rarely saw the men they were shooting at. Fire was directed at a window, a hedgerow, a treeline — not at individual enemies. Additional fire on the same position had diminishing returns until the tactical situation changed.

---

## Random Movement as Overwatch

The random movement rates introduce a kind of "overwatch" to an otherwise I-go-you-go structure. Rather than requiring complicated methods for interrupting your opponent's movement — an especially difficult thing to manage during multiplayer games — teams simply declare their destination and roll to see how far they can move. The shorter the distance, the more likely they'll make it before you have a chance to fire at them in your turn.

This reflects the reality that units under observation couldn't simply sprint across open ground. FM 21-75 (1944) emphasized that movement under enemy observation required bounds from cover to cover. Dashing across short gaps was safer than long sprints in the open — and the mechanics reward that behavior. A team trying to cross a long stretch of open ground will probably come up short, stuck in the open when your turn comes around. A team dashing from one hedgerow to the next will usually make it.

---

## Scout Before You Commit

Against hidden defenders, your first goal is to make them reveal in bad positions before committing your main force.

Consider: a lone rifle team can only receive one hit per Fire order. Is the defender really going to spend a Hero Point to shoot at it? Push scouts forward aggressively to force reveals. Use recon units — they extend the reveal distance to 20" and get a potential free activation when enemies reveal in their line of sight. Once the defender shows their hand, deploy the rest of the platoon where resistance is weakest.

British reconnaissance doctrine emphasized "reconnaissance pull" — letting scouts identify the line of least resistance rather than blindly pushing the main body forward. FM 7-20 (1944) noted that "information of the hostile dispositions and the terrain is essential to the development of a sound plan." Probe, reveal, then concentrate force where they're weak. Keep a reserve to support success.

---

## Use Smoke

Smoke blocks line of sight completely. Even the scariest units are effectively neutralized when behind it. Your troops can cross open ground safely, enemy fire support gets blinded, and you can reposition without taking fire.

British and U.S. doctrine both emphasized smoke as an essential tool for the attack. FM 7-10 (1942) describes smoke as used to "blind observation posts and weapons" and to "screen the movement of attacking troops." It was considered so important that rifle companies were issued smoke grenades and platoon mortars carried smoke rounds as standard.

Don't overlook it.

---

## Leaders as Force Multipliers

Your Platoon Leader doesn't shoot, but they're invaluable. In addition to activating their entire unit with one Order Point, they can direct a team's fire (+1 RoF), attempt to rally a suppressed team, add three inches of movement to help a team reach cover, or grant re-rolls on failed Assault Checks.

S.L.A. Marshall's central observation in *Men Against Fire* (1947) — however contested his specific statistics — was that combat effectiveness depended enormously on junior leaders. An NCO moving along a hedgerow, checking on men, directing fire, simply being visible — this kept soldiers fighting when they might otherwise have gone to ground and stayed there.

Use your leader's ability every time you activate. It costs nothing. A squad without its sergeant is half a squad — losing a leader doesn't destroy a unit, but it makes recovery much harder.

---

## Assaults Require Fire Support

Defenders who aren't Ready are destroyed without fighting back. Each RFP on an assaulted team is a massive swing in your favor.

Either have a supporting platoon fire at the target the same turn you assault, or split your platoon's orders — leaving some teams behind to fire while the rest move into contact. An assault against Ready defenders is a coin flip. An assault against suppressed defenders with RFPs stacked on them is a massacre.

British doctrine emphasized that the gap between covering fire and assault had to be "small to non-existent, so as not to allow the enemy to re-emerge and fire on the attackers before they closed in." FM 7-20 (1944) noted that "supporting fires are lifted or shifted at the last possible moment." The mechanics enforce this: if you assault without fire support, you're gambling. If you coordinate your fire and movement, you're fighting.

---

## Hard Cover and Suppression

Teams in hard cover are very difficult to kill with fire alone. The RFP resolution table shows why: in hard cover, only a roll of 1 kills; 2-3 suppresses; 4+ is Ready. You can pour fire into a position all day and the defenders will probably survive.

But here's the thing: suppressed teams can't fire back effectively, can't move toward enemies, and can't rally themselves while under fire. And when you assault them, they have to pass their status checks to respond — with each RFP potentially making them Killed or Suppressed instead of Ready.

The order of operations when activating is important. Any suppressed team with at least one RFP can't attempt to rally on its own. This represents how, while a certain amount of fire is necessary to "win the firefight" and suppress an enemy, less fire is needed to keep them that way. If you maintain even a single RFP on a suppressed team, they'll never rally without either a leader's help or retreating out of line of sight and giving up their ground.

Hard cover keeps you alive. Suppression gets you killed in assault.

---

## Artillery: The First Seconds Matter Most

Artillery caused the majority of WWII casualties — estimates range from 50-70% depending on theater and phase of the war. But the way artillery fire is portrayed in these rules reflects how the most effective portion of a barrage was often in the first few seconds.

Once those first rounds hit, everyone immediately takes whatever cover they can in order to make themselves as survivable as possible. In doing so, however, they also become completely ineffective for as long as they stay that way. Troops may attempt to move or shoot during the barrage — but doing so immediately exposes them to the same dangers as those first moments.

FM 6-20 (1944) noted that "surprise is essential to obtain maximum effect" from artillery fire. The initial shock was often more valuable than sustained bombardment. This is why barrages in Hail of Fire hit hard on the first turn, then become a suppression tool — dangerous to anyone who tries to act, but survivable for those who stay down.

---

## Vehicle Uncertainty

The RFP mechanism reproduces an important effect with vehicles: a tank has been hit, but it's not obviously destroyed. Many times during WWII, a tank could take several minutes after being hit before black smoke began to billow or ammunition started to cook off. Until the vehicle's status became evident, the enemy had to decide whether to hit it again to ensure it was no longer a threat, or address other immediate dangers.

This uncertainty is part of the game. You hit the Panzer, it stopped moving — is it dead? Suppressed? Playing possum? You won't know until it activates again, and by then you might have other problems.

---

## Summary

These rules cover a lot of the same familiar ground as most other WWII games, but sometimes present them in unconventional ways that can take a game or two to click. The mechanisms are specific and intentional — designed to reward the tactics that worked in WWII and punish the ones that got men killed.

If players find themselves using fire and movement, suppressing before assaulting, scouting before committing, and cursing when their sergeant gets hit, the game is doing its job.

**Fire to suppress, assault to destroy.**

**Scout first, commit second.**

**Smoke changes everything.**

**Keep fire on the assault target — always.**

**Hard cover keeps you alive; suppression gets you killed in assault.**

---

## Sources

**Primary:** FM 7-5 (1940), FM 7-10 (1942), FM 7-20 (1944), FM 6-20 (1944), FM 21-75 (1944); British *Infantry Training Part VIII* (1944).

**Secondary:** Marshall, *Men Against Fire* (1947); English, *On Infantry* (1984); Doubler, *Closing with the Enemy* (1994).
