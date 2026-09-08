# Unemployment as an Equilibrium Object: Accumulation, Effort and the Employment Rate in a Two-Class Differential Game
Carlos Galindo Escajeda
2026-09-01

# Abstract

Accumulation is normally thought to absorb unemployment. It can also
manufacture it: where investment raises the capital–labour ratio faster
than it raises employment, the pool of unemployed workers is an output
of growth rather than a residue left over from it, and its size is what
bounds the wage. Goodwin made that a cycle; Lancaster made distributive
conflict between workers and capitalists a differential game; Mehrling
joined the two. This paper makes the unemployment rate the equilibrium
object of such a game. Two organised classes contest the wage share and
the effort extracted from the hours they hire over an economy whose only
scarce factor is labour, whose technology mechanises faster the tighter
employment is, and in which a share of every unit of accumulation
displaces labour. The state is the employment rate.

Three results follow from the structure before any regime question is
asked. First, a separation theorem: when each class values what happens
to its whole class, the strategic compromise over accumulation and the
wage share does not depend on the mechanisation law at all; the
compromise is fixed by extraction, the capital–output ratio and
impatience, and the unemployment pool is what absorbs it afterwards.
Second, the compromise is a quadratic: above a fold in extractable
effort, given in closed form, there are two interior stationary
equilibria — provided labour’s wage bounds exclude neither — an
accumulationist one with a low wage share and a distributionist one with
a high wage share, and below the fold there is none; and wherever the
accumulationist compromise still leaves an unemployment pool, both
classes, labour included, are strictly better off in it than in any
other interior equilibrium of the game, switching schedules between the
two included, although all of them remain equilibria. Third, whether the
unemployment pool persists is decided by a closed-form threshold on the
accumulation share that rises with the labour-displacing share of
accumulation, so the same economy falls into one of three cases: both
compromises leave permanent unemployment, only the distributionist one
does, or neither does. Where accumulation only absorbs labour the
mechanism is Goodwin’s and unemployment persists under slow
accumulation; where accumulation displaces as much labour as it hires
the threshold reaches one and no compromise absorbs the unemployment
pool at all — the limit in which growth manufactures unemployment as
fast as it absorbs it. A compromise that accumulates past the threshold
takes the economy to full employment in finite time, and there the game
needs a boundary law this paper does not supply. Joining that to the
ranking gives the paper’s sharpest case: where the two compromises
straddle the threshold, the one both classes prefer is exactly the one
that exhausts the unemployment pool, and so destroys the conditions
under which it was computed. Where the unemployment pool regulates the
wage, rather than being regulated by the compromise, is where organised
labour counts only its employed members or where the unemployment pool
bounds what labour can enforce; that regime is where the second half of
the mechanism lives, and it is left open.

# 1. Introduction

If accumulation employs labour, why does an economy that grows for
decades never run out of unemployed workers? One long-standing answer is
that the process manufactures its own surplus of labour, and that the
surplus is what holds the wage down. The claim has two halves.
Accumulation, by mechanising, throws labour off faster than it takes it
on; and the pool of workers thrown off regulates what the employed can
demand. Goodwin (1967) gave the second half a Phillips curve and
obtained a cycle. Lancaster (1973) made the conflict over distribution a
game between two classes and found it dynamically inefficient. Mehrling
(1986) put the two together and derived steady states indexed by how
well each class is organised. In Goodwin and in Lancaster the size of
the unemployment pool is not what the game determines. Neither is it an
instrument in Mehrling, whose players choose the wage level and the
investment level; what his game determines about it could not be
established, so Section 8 states that boundary rather than guessing
across it.

This paper shows that once the employment rate is the state of a
two-class differential game, and once the classes are organised enough
to value what happens to their members as a whole, the mechanism splits
into a separation theorem and a fold. The separation theorem says the
class compromise over the accumulation rate and the wage share is
decided without reference to how fast machinery displaces labour; the
mechanisation law then decides how large an unemployment pool the
compromise leaves behind. The fold says there are two such interior
compromises, or none: above a threshold in how much effort capital can
extract from an hour hired, an accumulationist equilibrium and a
distributionist one coexist, unless a bound on the wage share excludes
one of them; below the threshold no interior compromise exists. Where
the accumulationist compromise still leaves an unemployment pool, both
classes are strictly better off in it than in any other interior
equilibrium, and nothing in the model makes them choose it. Whether the
unemployment pool persists is then a closed-form question about the
accumulation share of the compromise the economy is in, not about its
parameters alone — and the two questions meet, because the case in which
the classes disagree most sharply with the model is the one where the
compromise they both prefer is the one that exhausts the unemployment
pool and so ends the description that priced it.

In words, the paper’s central sentence is this: *unemployment is the
residual of a bargain that never looks at it.* That is a strong form of
the first half above and a denial of the second half inside one
structure. The second half, that unemployment regulates the wage,
returns exactly where the organisation assumption fails: when labour’s
organisation values only the wage of its employed members, the shadow
price of employment collapses to what mechanisation alone gives it, and
labour pushes to whatever ceiling the unemployment pool allows. That
regime, with ceilings that move with the unemployment pool, is the
programme this paper opens and does not close.

**Contribution statement.** The model adds three primitives to the
Lancaster–Goodwin lineage: the margin between the hours a firm hires and
the effort it actually gets from them, as an instrument of capital
bounded by what the other class will bear; the employment rate rather
than the capital stock as the state, so that labour is always limiting;
and an induced mechanisation law as the stabiliser in place of a wage
Phillips curve. It solves the game in the class of linear-state
differential games. There the *constant* open-loop equilibria are Markov
perfect, verified directly rather than imported, so every constant
equilibrium object below is a closed form in the primitives; the
date-wise switching profiles that are also open-loop equilibria are not
claimed to be Markov perfect, and nothing below rests on their being so.
**Attribution boundary.** The dynamic inefficiency of the class
compromise is Lancaster’s; steady-state multiplicity indexed by class
organisation is Mehrling’s; ownership of the accumulation asset as the
seat of power is Bowles and Gintis’s; the persistence of exploitation
under accumulation is Veneziani’s. None of those is claimed here. What
is claimed is the separation, the fold, the split of persistence across
equilibria, the ranking of the whole equilibrium set where the preferred
compromise is sustainable, and the case in which it is not.

So what? A policy that reduces the unemployment pool by speeding
accumulation is, in this model, a policy about which equilibrium the
economy occupies, not about a parameter; and a policy on hours or on
permitted work intensity moves the fold, not the compromise. Section 7
returns to this.

# 2. The model

Time is continuous. Two classes act as organised players: capital, $C$,
which owns the capital stock and hires labour, and labour, $W$, which
sells it.

**Technology.** Production uses fixed coefficients. A worker hired for a
unit of time delivers $e$ units of labour, where $e$ is effort per
period, the intensity and length of work combined, and produces $a e$
units of output; $a$ is labour productivity per unit of labour
delivered. Capital per employed worker is $\kappa a$, so the
output–capital ratio is $e/\kappa$ and the capital–output ratio at unit
effort is $\kappa$. Productivity grows at the mechanisation rate $m$.

**Numbers.** The labour force $N$ grows at the exogenous rate $n$.
Employment is $L$; the employment rate is $v = L/N \in (0,1]$; the
unemployment rate is $1 - v$, and the pool of unemployed workers is what
that rate counts. There is no fertility map: numbers move through
employment rather than through demography, which is deliberate — the
question here is what the labour market does to the labour force, not
what the labour force does to itself.

**Distribution.** The wage per hour hired is $\omega a$, so $\omega$ is
the wage share per unit of effort delivered; the wage bill is
$\omega a L$ and profit is $(e - \omega) a L$. The profit rate is $$
r = \frac{e - \omega}{\kappa},
$$ and the profit–wage ratio per unit of effort is $(e-\omega)/\omega$.
Distribution is a residual: nothing here is a marginal product.

**Instruments.** Capital chooses the accumulation share $s \in (0,1)$ of
profit reinvested and the extraction $e \in [e_{\text{lo}}, \bar e]$.
Labour chooses the wage share
$\omega \in [\omega_{\text{lo}}, \bar\omega]$, with $\omega_{\text{lo}}$
a reservation floor below which labour is not supplied. The bounds are
compatible, $\bar\omega < e_{\text{lo}}$, so profit is positive on the
whole action set. In the core of the paper the bounds are constants;
Section 6 states the regime in which they move with the unemployment
pool. An equilibrium is *interior* when labour’s share lies strictly
inside its bounds; equilibria in which a bound on $\omega$ binds are not
classified in this paper.

**States.** Capital accumulates at $\dot K/K = s(e-\omega)/\kappa$. With
$K = \kappa a L$, employment grows at
$\dot L/L = s(e-\omega)/\kappa - m$, so with $x \equiv \ln v$ and
$y \equiv \ln a$, $$
\dot x = \frac{s(e-\omega)}{\kappa} - m(v) - n, \qquad \dot y = m(v).
$$ Mechanisation has two sources. Machinery is introduced faster where
labour is scarce, so $m$ is increasing in $v$; and a share $c \in [0,1)$
of every unit of accumulation is itself labour-displacing, which carries
a rising capital–labour ratio embodied in new investment as a parameter.
The closed forms below use $$
m = m_0 + b\ln v + c\,\frac{s(e-\omega)}{\kappa}, \qquad b \ge 0,
$$ so that $\dot x = (1-c)\,s(e-\omega)/\kappa - m_0 - b x - n$. At
$c = 0$ this is Goodwin’s supply side, in which accumulation only
absorbs labour; as $c \to 1$ accumulation displaces as much labour as it
hires. Every statement that does not need the linear form says so.

**Objectives.** Each class discounts at $\rho > 0$ and values the
logarithm of its class consumption. Capital consumes
$(1-s)(e-\omega) a L$ and may in addition value the capital it commands,
with weight $\lambda \ge 0$: accumulation for its own sake. Labour
consumes the wage bill $\omega a L$ and bears the disutility of the
effort extracted, $\theta e$. Up to terms that depend on neither state
nor control, $$
U_C = \ln(1-s) + \ln(e-\omega) + (1+\lambda)(x+y), \qquad
U_W = \ln\omega + a_W x + y - \theta e .
$$ The parameter $a_W \in \{0,1\}$ indexes labour’s organisation. With
$a_W = 1$ labour’s organisation values the wage bill of the whole class,
unemployed included; with $a_W = 0$ it values the wage per employed
member only, the insider case. In the core, where extraction is
capital’s instrument and the bounds are constant, the effort-disutility
weight $\theta$ moves no equilibrium object; it matters only where
labour influences $e$ or the bounds move, which is the regime of Section
6.

**Equilibrium.** A Nash equilibrium in open-loop strategies. In the core
the game is linear-state in the sense of Dockner, Jørgensen, Long and
Sorger (2000, §7.2): the state enters the dynamics and the payoffs
affinely and there is no multiplicative interaction between states and
controls, which are their conditions (7.35) and (7.36). Open-loop Nash
equilibria of such a game are Markov perfect. That property is stated in
the text of their §7.2 and not as a numbered theorem, so it is cited as
placement and verified directly here in Appendix A.3; nothing is lost by
the open-loop restriction in the core.

**Domain.** $\bar e \ge e > \omega > 0$ with
$\bar\omega < e_{\text{lo}}$, $\kappa, \rho > 0$, $b \ge 0$,
$\lambda, m_0, n, \theta \ge 0$, $v \in (0,1]$. Every statement below is
claimed on this domain and nowhere else. Full employment, $v = 1$, is
the boundary of the state space; the core’s equations describe the
economy strictly inside it, and Proposition 5 says when a path reaches
it.

What these primitives buy is worth stating before the results. Because
the payoffs are logarithmic and the technology is linear, every payoff
is affine in the two states, and the game falls into the class where an
open-loop equilibrium can be verified directly rather than approximated.
That is why the compromise, the fold, the unemployment rate it leaves
and the ranking between compromises are all closed forms in the
primitives, and why a claim about any of them can be checked rather than
simulated.

# 3. What is true at any rest point, whatever anyone maximises

The first layer needs no objective.

**Proposition 1 (stationary incidence).** At any rest point of the
employment rate, the profit rate equals the growth requirement per unit
of accumulation, $$
r^* = \frac{m(v^*) + n}{s},
$$ and the profit–wage ratio is $\kappa\,(m(v^*)+n)/(s\,\omega)$.

In words, the profit rate a stationary class structure must deliver is
pinned by growth and the accumulation share alone; the struggle over $e$
and $\omega$ decides how that rate is composed, not what it is. This is
the classical accumulation identity, and it is written here because
everything in Section 4 has to be consistent with it.

# 4. The linear-state core

Fix the control bounds as constants.

**Proposition 2 (separation).** Suppose a player’s payoff weights on $x$
and $y$ coincide. Then that player’s problem depends on the single state
$z \equiv x + y = \ln(av)$, whose law of motion $$
\dot z = \frac{s(e-\omega)}{\kappa} - n
$$ contains no mechanisation term, and its costate is the constant
$a/\rho$, for *any* mechanisation law $m(\cdot)$. Capital always
satisfies the hypothesis; labour satisfies it when $a_W = 1$.

In words, an organised class that values its whole class is indifferent
to how fast machinery displaces labour, because what displacement takes
from employment it gives back to productivity one for one inside the
class’s own consumption. The compromise is then decided on $z$ alone,
and the mechanisation law is handed the unemployment pool to settle
afterwards. Read the other way, the theorem is a reduction:
$z = \ln(K/\kappa N)$ is the log of capital per member of the labour
force, so the core is a game on Lancaster’s state with logarithmic
payoffs and a linear technology, and the employment rate is recovered
from that game by the mechanisation law. Nothing in Propositions 3 and 4
below would surprise a reader of that lineage; what the reduction buys
is Propositions 5 and 5$'$, which the lineage could not state because it
had no employment rate to place.

**Proposition 3 (the compromise is a static game).** With $a_W = 1$, and
on any horizon over which the induced employment path stays inside the
state space, a profile is an open-loop Nash equilibrium if and only if
at almost every date it is a Nash equilibrium of the static game with
payoffs $$
\ln(1-s) + \ln(e-\omega) + \frac{1+\lambda}{\rho}\,\frac{s(e-\omega)}{\kappa}, \qquad
\ln\omega + \frac{1}{\rho}\,\frac{s(e-\omega)}{\kappa}.
$$ Every constant profile that is a Nash equilibrium of this static game
is an open-loop equilibrium and is Markov perfect. Capital extracts the
ceiling, $e = \bar e$. Labour’s interior share is
$\omega = \kappa\rho/s$. Capital’s accumulation share solves $$
\bar e\, s^2 - s\Big(\bar e + \frac{\lambda}{1+\lambda}\,Q\Big) + Q = 0, \qquad Q \equiv \kappa\rho .
$$

In words, labour asks for a share equal to its impatience times the
capital–output ratio, divided by how much of profit capital reinvests;
capital reinvests what leaves it just indifferent between consuming and
employing. The response $b$ of mechanisation to the employment rate
appears in neither condition. The Markov-perfection claim needs no
imported theorem: the value functions are affine in the two states, and
the Hamilton–Jacobi–Bellman equation is verified directly (Appendix
A.3); the linear-state literature is placement. Because the equilibrium
condition is pointwise, constancy is a property of *some* equilibria and
not of all: where the static game has two equilibria, a schedule that
switches between them at arbitrary dates is also an open-loop
equilibrium, so the multiplicity of Proposition 4 is richer than two
points, and Section 6’s selection problem is correspondingly harder.

**Proposition 4 (the fold).** The static game’s first-order conditions
have two solutions with $s \in (0,1)$ and $\kappa\rho/s < \bar e$ if and
only if $$
\bar e > \kappa\rho\Big(1 + \frac{1}{\sqrt{1+\lambda}}\Big)^2 ,
$$ one at equality, and none below; the interior equilibria are those
solutions whose share $\kappa\rho/s$ lies strictly inside
$[\omega_{\text{lo}}, \bar\omega]$, so the wage bounds can exclude
either. At $\lambda = 0$ the fold is $\bar e = 4\kappa\rho$ and the two
solutions are $$
s_\pm = \frac{1 \pm \sqrt{1 - 4\kappa\rho/\bar e}}{2}, \qquad \omega_\pm = \frac{\kappa\rho}{s_\pm}.
$$ Since $\omega_\pm$ falls as $s_\pm$ rises, $\omega_+ < \omega_-$: the
accumulationist equilibrium $(s_+, \omega_+)$ has the higher
accumulation share and the lower wage share; the distributionist
equilibrium $(s_-, \omega_-)$ the reverse. The classification is of
interior equilibria; whether an equilibrium with a bound on $\omega$
binding exists below the fold is not decided here.

In words, an effort ceiling that can be stretched only a little relative
to impatience and capital intensity admits no interior class compromise
at all: whatever share labour asks for, capital’s best reply undercuts
the accumulation that share was priced against, and there is no interior
fixed point. Raising the effort ceiling past the fold creates two
compromises at once, and a taste for accumulation for its own sake,
$\lambda > 0$, lowers the fold.

**Proposition 4$'$ (dominance over the whole equilibrium set).** Suppose
two admissible interior equilibria exist and the accumulationist one
leaves an unemployment pool, $(1-c)A(s_+) \le \mu(1) + n$ —
equivalently, by Proposition 5$'$, $\hat s_c \ge s_+$. Then from any
common initial state and for every $\lambda \ge 0$, both classes obtain
a strictly higher discounted payoff in the accumulationist equilibrium
than in *any other interior* open-loop equilibrium of the core, the
switching schedules of Proposition 3 included. As everywhere in this
paper, the comparison is over equilibria in which the wage bounds do not
bind; equilibria at a binding bound are unclassified. Both remain Nash
equilibria; nothing in the model moves an economy between them.

In words, capital’s consumption term is the same in the two compromises,
so capital prefers the one that grows faster; and labour, valuing the
wage bill of its whole class, gains more from the faster growth of
employment and productivity than it loses in share. The extension to the
whole set is not a second argument but the same one: because the state
enters every payoff affinely, the discounted value of *any* profile is
the discounted average of the same constant $B_i$ evaluated along it, so
a ranking that holds at each date holds for every schedule. This is a
ranking each class makes by its own objective, not a welfare judgement,
and it is not a prediction: an organisation of labour that has settled
on the distributionist compromise has no unilateral reason to leave it.

**Proposition 4$''$ (the preferred compromise can be
self-undermining).** If instead $\hat s_c < s_+$, the hypothesis of
Proposition 4$'$ fails, and Proposition 5$'$’s remaining two cases must
be separated. In the split case $s_- < \hat s_c < s_+$ the two
compromises differ in kind, not only in degree. The distributionist one
has an interior rest point; the accumulationist one has none, and by
Proposition 5 it drives the economy to full employment in finite time
from *every* interior initial state, at which point the core’s equations
no longer describe it. The infinite-horizon comparison is then
unavailable, and the interior equilibria the core can host for ever are
exactly those date-wise selections whose induced path never exhausts the
unemployment pool. That set is strictly larger than the distributionist
compromise alone: a schedule playing the accumulationist compromise for
a small enough fraction of each period stays inside the state space for
ever and, by Proposition 4$'$’s pointwise argument, both classes
strictly prefer it. Which of those schedules the classes would settle on
is a state-constrained problem the core does not solve, and it is
recorded as undischarged. In the remaining case, $\hat s_c \le s_-$,
*both* compromises accumulate past the threshold: each reaches full
employment in finite time from every interior start, no infinite-horizon
comparison is available for either, and the core hosts no interior
equilibrium for ever. The welfare ranking of Proposition 4$'$ is
therefore silent on that third case, and the model’s three persistence
regimes carry two comparisons, not three.

In words, the compromise both classes prefer is, in this case, the one
that abolishes the condition under which it was computed. The
unemployment pool is the residual of a bargain that never looks at it,
and where accumulation is fast enough the bargain consumes the residual
and with it the description. Nothing here says the economy must
therefore cycle; it says the core stops, and what replaces it is a
boundary law the paper does not write.

**Proposition 5 (where the unemployment pool settles, and whether it
persists).** Fix a compromise $(s, \omega)$ and write
$A \equiv s(\bar e-\omega)/\kappa$ for its accumulation rate; the
compromise itself does not depend on $c$. Write the employment-induced
part of the mechanisation law as $\mu(v) \equiv m_0 + b\ln v$ **with
$b > 0$**, or more generally any continuous strictly increasing function
on $(0,1]$ with $(1-c)A - n$ in its range. The restriction is not
cosmetic: at $b = 0$, which the domain admits, $\mu$ is constant rather
than strictly increasing, the displayed $\ln v^*$ below is not defined,
and there is no interior rest point at all. That face is Section 5’s and
is stated there. If $(1-c)A < \mu(1) + n$, the employment rate has a
unique rest point inside the state space, defined by
$\mu(v^*) = (1-c)A - n$, and every path that starts inside converges to
it monotonically; with the linear law, $\ln v^* = [(1-c)A - m_0 - n]/b$.
If $(1-c)A > \mu(1) + n$, there is no rest point inside the state space:
every path reaches full employment in finite time, and from that moment
the core’s equations no longer describe the economy. At equality the
rest point is full employment itself and is approached asymptotically,
not reached; under the linear law $\ln v(t) = \ln v(0)\,e^{-bt}$. The
unemployment pool persists, $v^* < 1$, if and only if $$
(1-c)\,A < \mu(1) + n ,
$$ that is, if and only if the labour-absorbing part of accumulation
falls short of the full-employment mechanisation rate plus population
growth.

**Proposition 5$'$ (the persistence threshold along the compromise).**
At an interior equilibrium capital’s first-order condition pins the
accumulation rate to the accumulation share alone, $$
A(s) = \frac{\rho\, s}{(1+\lambda)(1-s)},
$$ strictly increasing in $s$. Hence a compromise leaves a permanent
unemployment pool if and only if its accumulation share lies below $$
\hat s_c \;\equiv\; \frac{(m_0+n)(1+\lambda)}{(1-c)\rho + (m_0+n)(1+\lambda)}
$$ for the linear law, and the economy is in exactly one of three cases:
both compromises leave a permanent unemployment pool ($s_+ < \hat s_c$);
only the distributionist one does ($s_- < \hat s_c \le s_+$); neither
does ($\hat s_c \le s_-$). The threshold rises with $c$ and, whenever
$m_0 + n > 0$, tends to one as $c \to 1$: when accumulation displaces as
much labour as it hires, every compromise leaves a permanent
unemployment pool. With neither population growth nor autonomous
mechanisation the threshold is zero for every $c < 1$: an unemployment
pool then has nothing to form from.

**Corollary (the cases are realised).** Take $c = 0$ and $\lambda = 0$;
the equilibria quoted below are the roots of Proposition 4 at that
value, and they move with $\lambda$. At $\bar e = 1$, $\kappa = 2$,
$\rho = 0.08$, $m_0 = 0.02$, $n = 0.01$ and $b = 0.05$ the compromises
are $(s,\omega) = (0.2, 0.8)$ and $(0.8, 0.2)$ and
$\hat s_0 \approx 0.27$: the distributionist compromise leaves a
permanent unemployment pool, $v^* \approx 0.82$, while the
accumulationist one, with $A = 0.32$ against $m_0 + n = 0.03$, takes the
economy to full employment in finite time — the split case. At
$\bar e = 1$, $\kappa = 3$, $\rho = 0.08$, $m_0 = 0.10$, $n = 0.03$,
$b = 0.05$ the compromises are $(0.4, 0.6)$ and $(0.6, 0.4)$ and
$\hat s_0 \approx 0.62$: both leave one. These are witnesses of two of
the three cases. The third case is not sampled but proved: with
$m_0 = n = 0$ the threshold is $\hat s_c = 0$, so whenever two interior
compromises exist neither leaves a permanent unemployment pool.

In words, the direction of causation runs through $c$, and nothing else
in the model decides it. At $c = 0$ accumulation only absorbs labour,
unemployment persists where the compromise accumulates *slowly*, and the
mechanism is Goodwin’s, or Harrod’s: a race between capital and an
exogenously mechanising labour supply. The opposite direction — that
accumulation manufactures its own surplus of labour — enters through
$c$: as the labour-displacing share of accumulation rises, the threshold
$\hat s_c$ rises with it, and in the limit no compromise, however
accumulationist, absorbs the unemployment pool. Which direction holds is
therefore a theorem about $c$, and Proposition 5$'$ says exactly where
the line falls for each value of it; the compromise the classes reach is
the same on both sides of that line, because Proposition 2 keeps $c$ out
of it.

**Proposition 6 (the insider case).** With $a_W = 0$ labour’s shadow
price of employment is $b/(\rho(\rho+b))$, positive only because a
tighter labour market speeds the productivity its wage is indexed to,
and its interior share is $$
\omega = \frac{\kappa}{s}\Big[(1-c)\frac{b}{\rho(\rho+b)} + \frac{c}{\rho}\Big]^{-1},
$$ which at $c = 0$ is $\kappa\rho(\rho+b)/(bs)$ and diverges as
$b \to 0$: an insider organisation with no mechanisation stake pushes
the wage share to its ceiling, and the separation of Proposition 2
fails. With $c > 0$ the share stays finite as $b \to 0$, at
$\kappa\rho/(cs)$: labour-displacing accumulation gives even an insider
organisation a stake in accumulation, through the productivity its wage
is indexed to.

In words, the unemployment pool regulates the wage only for a labour
movement that does not count the unemployed as its own and has no
productivity stake in accumulation; for one that does either, the
compromise regulates the unemployment pool.

# 5. The Lancaster face

If $b = 0$ the employment-induced part of the mechanisation law is flat
and the employment rate rises, falls, or stays where it started
according as $(1-c)A$ exceeds, falls short of, or equals $m_0 + n$;
there is no interior rest point to converge to. Lancaster’s one-state
world, in which labour is never limiting, is the $b = 0$ face of this
one. Under fixed coefficients $av = K/(\kappa N)$, so the drift of $z$
is $s(e-\omega)/\kappa - n$ whatever the split of accumulation between
employment and productivity; that is why $c$ moves the rest point and
the threshold of Propositions 5 and 5$'$ and nothing in Propositions 3,
4 and 4$'$.

# 6. The regime the core does not reach

The second half of the mechanism is that unemployment regulates the
wage. In the core it does not: constant ceilings and class-wide
objectives leave the compromise blind to $v$. The regime in which it
does is the one where the ceilings move with the unemployment pool:
labour can enforce at most $\bar\omega(v)$, increasing in $v$, and
capital can extract at most $\bar e(v)$, decreasing in $v$. With
log-linear ceilings, $\bar\omega(v) = \hat\omega\, v^{\eta}$ and
$\bar e(v) = \hat e\, v^{-\zeta}$, the labour ceiling binds where
$\hat\omega v^\eta < \kappa\rho/s$, that is for a large enough
unemployment pool, and is slack above the threshold employment rate
$\hat v = (\kappa\rho/(s\hat\omega))^{1/\eta}$. Below $\hat v$ the
unemployment pool disciplines the wage; above it organised labour
restrains itself. Whether the rest point of Proposition 5 lies below or
above $\hat v$ is a closed-form comparison, and the state-dependence of
the binding ceiling makes the costates non-constant, so the equilibrium
in that regime is not a static game and is not proved here. What is at
stake there is which half of the mechanism does the work: below $\hat v$
unemployment sets the wage, above it the bargain does, and the same
economy can sit on either side of that line as it grows.

One structural remark connects it to Proposition 4$''$, and it is a
**conjecture**, not a result. The extraction ceiling
$\bar e(v) = \hat e\,v^{-\zeta}$ *falls* as employment rises: a large
unemployment pool is what lets capital raise effort per worker, and
absorbing the unemployment pool takes that away. But by Proposition 4 an
interior compromise exists only where the extractable day is large,
$\bar e > \kappa\rho(1 + 1/\sqrt{1+\lambda})^2$. If the regime’s
compromise were still characterised by that condition with $\bar e(v)$
in place of $\bar e$ — which is exactly what the non-constant costates
put in doubt, and why this is a conjecture — an interior compromise
would exist only below the employment rate $$
v_{\text{f}} = \Big(\hat e \big/ \kappa\rho(1 + 1/\sqrt{1+\lambda})^2\Big)^{1/\zeta},
$$ and the accumulationist compromise, which raises $v$, would run into
$v_{\text{f}}$ before it ran into full employment whenever
$v_{\text{f}} < 1$. That would be a second self-undermining channel,
through the fold rather than through the boundary of the state space,
and a more interesting one: the compromise would not merely outgrow its
description, it would dissolve the condition for its own existence. The
computation that settles it is the regime’s equilibrium itself, which is
why it is the next thing this programme owes.

# 7. So what

Five things a reader of this literature can take from the core, and one
warning.

First, the unemployment pool is an equilibrium object with a closed-form
size, and its persistence is decided by an inequality in which the
accumulation share, the wage share, extractable effort and the
labour-displacing share of accumulation all appear. Policies on working
time or on permitted work intensity move the fold of Proposition 4, and
so decide whether a compromise exists, before they move anything else;
and the direction in which accumulation acts on unemployment is not a
matter of doctrine but of one parameter, $c$, which the compromise never
sees.

Second, “the same economy” has two compromises, and they disagree about
unemployment. A programme that raises accumulation to absorb the
unemployment pool is, in this model, a programme that moves the economy
from the distributionist to the accumulationist equilibrium at a lower
wage share; it is not a free parameter change.

Third, whether the unemployment pool regulates the wage depends on whom
the organisation of labour counts as its own. An organisation that
internalises the unemployed sets the wage share by its own accumulation
calculus and hands unemployment to technology; one that does not is
disciplined by the unemployment pool in exactly the way the second half
of the mechanism describes.

Fourth, and this is the sentence a reader of this literature will
resist: where two compromises exist and both leave an unemployment pool,
both classes are strictly better off in the accumulationist one, labour
included, because for an organisation that values its whole class the
faster growth of employment and productivity outweighs the lower share.
That is dominance, not selection. Nothing in the model moves an economy
from the distributionist compromise to the accumulationist one, and an
insider organisation would not share the judgement.

Fifth, and it is the sharpest thing the model says, the qualification in
that last sentence is not fine print. Where the two compromises straddle
the persistence threshold, the compromise both classes prefer is
precisely the one that exhausts the unemployment pool — and a compromise
that exhausts it destroys the conditions under which it was computed,
because the core’s equations describe an economy with unemployed workers
in it. Accumulation fast enough to be preferred by everyone is
accumulation fast enough to end the description. The unemployment pool
is the residual of a bargain that never looks at it, and here the
bargain runs out of residual. What the classes settle on instead is a
state-constrained problem this paper leaves open; that it is the
*interesting* open problem, rather than a technicality, is the point.

The warning is about how much weight the separation theorem can bear.
Proposition 2 says a class that values its whole class is indifferent to
how fast machinery displaces labour — but that is a statement about a
log objective with equal weights on employment and productivity. An
organisation that weighted employment above the wage bill would not be
indifferent: it would trade share for jobs, and the size of the
unemployment pool would then depend on the bargain after all. The
separation is a theorem about preferences, not about organisation as
such, and it is the first thing to give way if that assumption is wrong.

# 8. Placement, by one primitive each

Goodwin (1967) fixes the wage by a Phillips law in the employment rate;
here the wage share is an instrument and the employment rate is what the
instruments leave behind. Lancaster (1973), Hoel (1978) and Pohjola
(1983) have capital as the state and labour never limiting; Shimomura
(1991) derives the feedback equilibria of that game under constant
absolute risk aversion. Proposition 2 says plainly that this paper’s
core is a game on that same state, capital per member of the labour
force, with logarithmic payoffs and a linear technology, and it claims
no novelty for the constant-strategy equilibrium as such; what it adds
is the employment rate as the object the game places, with the
persistence theorem, the fold and the dominance result that follow.

Two features of that lineage are worth naming exactly, because both look
like the results here and are not. First, its payoffs are *linear* in
each class’s consumption over a *finite, undiscounted* horizon — this is
Lancaster’s formulation as Pohjola takes it up and as de Zeeuw (1992)
restates it — so equilibrium controls are bang-bang and the multiplicity
that arises is a multiplicity of *switching dates*. De Zeeuw shows that
Pohjola’s open-loop Stackelberg solution under workers’ leadership is in
fact one of infinitely many whenever workers’ consumption floor is low
enough, and that the objective values are identical across all of them.
The fold of Proposition 4 is a different object: two interior
compromises with *strictly different* payoffs, which the log objective
and the infinite discounted horizon are what produce. Second, a payoff
ranking in a capitalism game already exists. Başar, Haurie and Ricci
(1985) show that feedback-Stackelberg leadership by capitalists weakly
Pareto-dominates the feedback Nash outcome of a modified Lancaster game,
workers’ leadership collapsing to Nash. That is a ranking *across
information structures*, it is weak, and it is again finite-horizon and
undiscounted; Proposition 4$'$ ranks two Nash equilibria of one game
strictly, and Proposition 4$''$ says when the higher-ranked one cannot
be sustained. Sorger (1997) makes redistribution in a two-class growing
economy a differential game between the capitalist class and a
government holding lump-sum taxes and transfers, with a Markov-perfect
equilibrium coinciding with a first-best; there is no government and no
tax instrument here. Mehrling (1986) synthesises Lancaster and Goodwin
into a differential game with steady states indexed by class
organisation; this paper carries the extraction margin and an induced
mechanisation law as primitives, and separates the compromise from the
unemployment pool. His instruments are the wage level and the investment
level — the Lancaster pair — and his payoffs are the present values of
workers’ consumption and capitalists’ profits, so the effort extracted
from an hour hired is not a control of his game and no class-size term
or effort disutility enters his objectives. That much is established
through a work that restates his model rather than from the paper
itself, which is unobtainable here, and the ledger of Appendix B carries
the grade. Two things it does not establish, and which are therefore not
claimed: whether the wage Phillips curve survives his synthesis, and
whether the employment rate is a state of his game. Bowles (1985) and
Bowles and Gintis (1993) put the extraction of labour under the threat
of job loss into a static contested exchange; here the same margin sits
inside a dynamic class game, and their result that ownership of the
accumulation asset confers power is theirs. Cajas Guijarro and Vera
(2022) carry the employment rate, the wage share and labour intensity as
states of a business-cycle model without strategic players. Veneziani
(2007) and Veneziani and Yoshihara study the persistence of exploitation
in competitive accumulation economies; here the classes are strategic
players and distribution is tracked in output units throughout.

# Appendix A. Proofs

## A.1 Proposition 1.

Set $\dot x = 0$: $s(e-\omega)/\kappa = m(v^*) + n$. Divide by $s$ for
$r^*$; divide $e - \omega = \kappa(m+n)/s$ by $\omega$ for the
profit–wage ratio.

## A.2 Proposition 2.

Write player $i$’s Hamiltonian $H_i = U_i + p_x^i \dot x + p_y^i \dot y$
with $U_i$ carrying weights $(a_x^i, a_y^i)$ on $(x,y)$. The costate
equations are $\dot p_y^i = \rho p_y^i - a_y^i$ and
$\dot p_x^i = \rho p_x^i - a_x^i + (p_x^i - p_y^i)\,m'(x)$. The bounded
stationary solution is $p_y^i = a_y^i/\rho$ and, if $a_x^i = a_y^i = a$,
$p_x^i = a/\rho$ regardless of $m'$, because the bracket vanishes. The
state-dependent part of $H_i$ is $(p_y^i - p_x^i)\,m(x) = 0$, so $H_i$
depends on the state only through $a(x+y)$, whose law of motion is
$\dot z = s(e-\omega)/\kappa - n$. Transversality holds because $z$
grows at most linearly and $\rho > 0$. For the linear law the same
computation gives, for general weights,
$p_x^i = (\rho a_x^i + b a_y^i)/(\rho(\rho+b))$, which reduces to
$a/\rho$ when the weights coincide and to $b/(\rho(\rho+b))$ for the
insider case.

## A.3 Proposition 3.

With constant costates the maximised Hamiltonian is separable in the
control-dependent part, so the open-loop Nash equilibrium maximises each
player’s Hamiltonian pointwise against the other’s constant strategy,
which is the static game displayed. The value functions
$V_i = (a_i/\rho)(x+y) + B_i$ satisfy the Hamilton–Jacobi–Bellman
equations identically in $(x,y)$ for the constant strategies, so the
open-loop equilibrium is Markov perfect. Capital’s derivative in $e$ is
$1/(e-\omega) + (1+\lambda)s/(\kappa\rho) > 0$, so $e = \bar e$.
Labour’s first-order condition is $1/\omega = s/(\kappa\rho)$. Capital’s
is $1/(1-s) = (1+\lambda)(e-\omega)/(\kappa\rho)$. These conditions are
sufficient, not merely necessary: each static payoff is the sum of a
logarithm and a term linear in the player’s own instrument, so it is
strictly concave in that instrument —
$\partial^2/\partial s^2 = -1/(1-s)^2 < 0$ for capital and
$\partial^2/\partial\omega^2 = -1/\omega^2 < 0$ for labour — and $e$
enters capital’s payoff monotonically, giving the corner. Best replies
are therefore unique, and the static Nash set consists of exactly the
interior solutions of the displayed quadratic together with any
equilibrium at which a bound on $\omega$ binds. That uniqueness is what
makes the equilibrium set of the whole game the set of date-wise
selections from a *known* finite set, which A.4$'$ then ranks.
Substituting $\omega = Q/s$ into the latter and clearing the
denominators $s$ and $1+\lambda$ gives the quadratic; the cleared form
and the displayed form are proportional with factor $-(1+\lambda)$.

## A.4 Proposition 4.

The discriminant of the quadratic is
$(\bar e + \lambda Q/(1+\lambda))^2 - 4\bar e Q$, a convex quadratic in
$\bar e$ whose zeros are $\bar e = Q(1 \pm 1/\sqrt{1+\lambda})^2$.
Between the zeros there are no real roots. Above the larger zero both
roots are real, lie in $(0,1)$, and satisfy $Q/s < \bar e$; below the
smaller zero the real roots violate $Q/s < \bar e$. The last three
sentences were decided by unsatisfiability on division-free encodings
over the whole domain, not sampled (Appendix A.7). At $\lambda = 0$ the
quadratic is $\bar e s^2 - \bar e s + Q = 0$ with discriminant
$\bar e(\bar e - 4Q)$; the roots are as displayed and lie in $(0,1)$
whenever they are real, since their sum is $1$ and their product
$Q/\bar e > 0$; and $s_- > Q/\bar e$ holds whenever the roots are real:
with $q \equiv Q/\bar e \in (0, 1/4]$, $s_- > q$ is equivalent to
$1 - 2q > \sqrt{1-4q}$, both sides positive, hence to $4q^2 > 0$.

## A.4$'$ Proposition 4$'$.

With constant strategies the value functions are
$V_i = (a_i/\rho)z + B_i$ and $\rho B_i = U_i(u^*) + (a_i/\rho)(A - n)$,
so two equilibria are ranked from a common state by $B_i$. Let
$s_- < s_+$ be the roots; by Vieta their product is $Q/\bar e$, so
$\bar e s_\pm - Q = \bar e s_\pm (1 - s_\mp)$ and capital’s consumption
term
$\ln(1-s) + \ln(\bar e - Q/s) = \ln(1-s) + \ln \bar e + \ln(1-s_{\text{other}})$
takes the same value at the two roots. Hence
$B_C(s_+) - B_C(s_-) = \frac{1+\lambda}{\rho^2}\big(A(s_+) - A(s_-)\big) = \frac{1+\lambda}{\rho^2}\,\frac{\bar e (s_+ - s_-)}{\kappa} > 0$.
For labour, along $\omega = Q/s$,
$\partial B_W/\partial s = -1/s + \bar e/(\kappa\rho)$, positive exactly
where $s > Q/\bar e$, which both admissible roots satisfy (A.4); so
$B_W$ is increasing on an interval containing both roots and
$B_W(s_+) > B_W(s_-)$. Both profiles satisfy both first-order
conditions, so both are Nash; no criterion in the model orders them
beyond this ranking.

*Extension to the whole set.* Let $\sigma$ be any measurable date-wise
selection of the static Nash set, so an open-loop equilibrium by
Proposition 3, and let $A(t) \equiv A(\sigma(t))$. Since
$\dot z = A - n$, the state is
$z(t) = z(0) + \int_0^t (A(\tau)-n)\,d\tau$, and interchanging the order
of integration in $\int_0^\infty e^{-\rho t} a_i z(t)\,dt$ gives $$
J_i(\sigma) = \frac{a_i z(0)}{\rho} + \rho\int_0^\infty e^{-\rho t} B_i(\sigma(t))\,dt ,
$$ with $B_i$ the same constant as above. The value of any equilibrium
is therefore an $e^{-\rho t}$-average of $B_i$ along it, the weights
integrate to $1/\rho$ whatever the schedule, and $B_i(s_+) > B_i(s_-)$
for both classes. Hence $J_i(\sigma) \le J_i(s_+)$ with equality only if
$\sigma = s_+$ almost everywhere. The interchange is licensed because
$\sigma$ takes values in the finite static Nash set, so $A$ is bounded,
$|z(t)| \le |z(0)| + Mt$ with $M = \max_\pm |A(s_\pm) - n|$, and
$\int_0^\infty e^{-\rho t}(|z(0)| + Mt)\,dt = |z(0)|/\rho + M/\rho^2 < \infty$.
Nothing beyond measurability of $\sigma$ is used. The action set itself
is not compact — $s$ ranges over the open interval $(0,1)$ — so the
bound comes from the equilibrium set, not from the action set.

*The hypothesis, and why it is not free.* Proposition 3 characterises
the equilibrium set only on a horizon over which the induced path stays
inside the state space. If $(1-c)A(s_+) > \mu(1)+n$ the constant
accumulationist profile leaves it in finite time (A.5), so $B_C(s_+)$
prices a path the core cannot host and the comparison above is not
available on $[0,\infty)$. The hypothesis $(1-c)A(s_+) \le \mu(1)+n$ is
exactly $\hat s_c \ge s_+$ by A.5$'$, so it introduces no object the
paper does not already have. It also does the work for *every* schedule
at once, which the extension needs and which the constant case alone
would not give: for any selection $\sigma$, $A(\sigma(t)) \le A(s_+)$,
so at the boundary $x = 0$,
$\dot x = (1-c)A(\sigma) - \mu(0) - n \le (1-c)A(s_+) - \mu(1) - n \le 0$.
The state space is therefore forward-invariant under every selection,
not merely under the two constant ones, and Proposition 3 characterises
the equilibrium set on the whole infinite horizon.

## A.4$''$ Proposition 4$''$.

In the split case $s_- < \hat s_c < s_+$ the two statements are A.5
applied at each root: $(1-c)A(s_-) < \mu(1)+n$ gives an interior rest
point, $(1-c)A(s_+) > \mu(1)+n$ gives
$\dot x \ge (1-c)A(s_+) - \mu(1) - n > 0$ on the state space and hence a
finite hitting time from every interior start. For the sustainable set,
take the linear law and a schedule of period $P$ playing $s_+$ on a
fraction $\delta$ of each period. Then $\dot x = -b\,(x - X_j)$ with
$X_\pm = ((1-c)A(s_\pm) - m_0 - n)/b$, so on each segment $x$ moves
geometrically towards $X_j$; the composition of the two segment maps is
an affine contraction with slope $e^{-bP} < 1$, its unique fixed point
is the periodic orbit, and the orbit’s peak is a continuous function of
$\delta$ taking the value $X_- < 0$ at $\delta = 0$. Continuity alone
therefore gives some $\delta > 0$ whose whole orbit stays strictly
inside, while $\delta = 1$ does not, since $X_+ > 0$. Monotonicity of
the peak in $\delta$, and hence a largest sustainable duty cycle, is not
claimed. By the extension above every such schedule strictly dominates
the constant distributionist profile for both classes. Whether the
supremum over sustainable schedules is attained is not decided here.

## A.5 Proposition 5.

Write $B \equiv (1-c)A$ for the labour-absorbing part of accumulation,
so $\dot x = B - \mu(x) - n$ with $\mu(x) = m_0 + b x$ in the linear
case. $\partial \dot x/\partial x = -\mu'(x) < 0$ for a strictly
increasing law, so $\dot x$ is strictly decreasing in $x$. If $B - n$
lies in the range of $\mu$ and $B < \mu(0) + n$, the root $x^*$ of
$\mu(x) = B - n$ is unique and satisfies $x^* < 0$; since $\dot x$ has
the sign of $x^* - x$, every path starting in $(-\infty, 0]$ converges
to it monotonically, and with the linear law it is the displayed
logarithm. If $B > \mu(0) + n$, then $\dot x \ge B - \mu(0) - n > 0$ on
the state space, a positive lower bound, so $x$ reaches $0$ in finite
time; this uses continuity of $\mu$. If $B = \mu(0) + n$, then
$\dot x = \mu(0) - \mu(x) > 0$ inside with no positive lower bound near
$0$, and $x^* = 0$ is approached asymptotically; under the linear law
$\dot x = -bx$ and $x(t) = x(0)e^{-bt}$. Persistence is the displayed
inequality with $\mu(1) = m_0$ in the linear case.

## A.5$'$ Proposition 5$'$.

Capital’s first-order condition,
$(1-s)(\bar e-\omega)(1+\lambda) = \kappa\rho$, gives
$(\bar e - \omega)/\kappa = \rho/((1+\lambda)(1-s))$ and hence
$A(s) = \rho s/((1+\lambda)(1-s))$, with
$A'(s) = \rho/((1+\lambda)(1-s)^2) > 0$. Solving
$(1-c)A(\hat s_c) = m_0 + n$ gives the displayed $\hat s_c$, and the
three cases follow from $s_- < s_+$. At $m_0 = n = 0$, $\hat s_c = 0$,
which is below every admissible root, so the “neither” case holds
identically there.

## A.6 Proposition 6.

Set $a_W = 0$ in the formula of A.2, so $p_x^W = b/(\rho(\rho+b))$ and
$p_y^W = 1/\rho$. With the mechanisation law carrying $c$,
$\partial\dot x/\partial\omega = -(1-c)s/\kappa$ and
$\partial\dot y/\partial\omega = -cs/\kappa$, so labour’s first-order
condition is $1/\omega = (s/\kappa)\big[(1-c)p_x^W + c\,p_y^W\big]$,
which is the displayed share; at $c = 0$ it is
$1/\omega = p_x^W s/\kappa$.

## A.7 Certificates.

Every identity in A.1–A.6, the sign in A.3, the drift identity of
Section 5, the non-emptiness of the hypothesis set of Propositions 3–5
under persistence, and the witnesses of the Corollary are checked
symbolically, with controls that must fail on a wrong object, in
`models/reserve_army_game/day0_stationary_locus_and_regimes_2026_09_08_8e8a87f3.py`.
The fold of A.4 for every $\lambda$, the admissibility of the roots
above it and their inadmissibility below it, the equality of capital’s
consumption term at the two roots, the sign of labour’s payoff
difference, and the locus $A(s)$ of A.5$'$ are checked in
`models/reserve_army_game/c2_adjudication_checks_2026_09_08_8e8a87f3.py`;
the value identity of A.4$'$ for a switching schedule, the pointwise
form of the comparison, the equivalence of the new hypothesis with
Proposition 5$'$’s threshold, the finite hitting time of the
accumulationist compromise at the Corollary’s own split witness, the
existence of a sustainable duty cycle in that case, the strict concavity
of each static payoff in its own instrument that makes A.3’s conditions
sufficient, and the inversion of Section 6’s conjectured threshold
$v_{\text{f}}$ are checked in
`models/reserve_army_game/schedule_dominance_and_domain_gap_2026_09_08_8f6007c0.py`,
whose denominator checks are also `unsat` verdicts on division-free
encodings. Every such `unsat` is a proof, not a sample. Each file prints
its own check and control counts and exits non-zero on any failure. The
witnesses are witnesses and prove nothing universal.

# Appendix B. Status ledger

| statement | status | what would change it |
|----|----|----|
| Prop. 1 | proved (identity) | — |
| Prop. 2 | proved on the stated domain (separation is form-free) | — |
| Prop. 3 | proved, conditional on the path staying inside the state space; Markov perfection of the constant profiles by direct HJB verification; constancy is not a property of all open-loop equilibria (switching schedules are equilibria too) | a boundary law at full employment would extend it |
| Prop. 4 | proved for every $\lambda \ge 0$ as a count of first-order solutions; interiority against the wage bounds is a separate check | boundary equilibria (a bound on $\omega$ binding) are unclassified |
| Prop. 4$'$ | proved for every $\lambda \ge 0$, over the whole open-loop equilibrium set, **under the added hypothesis that the accumulationist compromise leaves an unemployment pool**; without it the comparison is unavailable (Prop. 4$''$) | a boundary law at full employment would restore a comparison in the split case |
| Prop. 4$''$ | all three of Proposition 5$'$’s cases now separated: the split case proved (finite hitting time; sustainable set non-trivial by continuity in the duty cycle), and the case $\hat s_c \le s_-$ recorded as carrying NO welfare comparison at all | whether the Pareto supremum over sustainable schedules is attained is UNDISCHARGED; a boundary law would restore a comparison in both non-persisting cases |
| Prop. 5 | proved under continuity, strict monotonicity and range inclusion of $m$ | — |
| Prop. 5$'$ | proved | — |
| Corollary | witnesses of two of the three cases; the third proved at $m_0 = n = 0$ | — |
| Prop. 6 | proved | — |
| Selection among the equilibria | UNDISCHARGED; dominance now covers the whole set where the accumulationist compromise persists, so payoff dominance is decisive there if it is accepted as a refinement, but the model contains no adjustment process; in the split case selection is over sustainable schedules and is open | an adjustment process, or a boundary law that restores the infinite-horizon comparison |
| Continuation at full employment | UNDISCHARGED, outside the core | a boundary law |
| Section 6 regime | UNDISCHARGED, stated as a programme | the equilibrium with state-dependent ceilings |
| Section 6’s second self-undermining channel ($v_{\text{f}}$) | CONJECTURE, explicitly labelled; it substitutes $\bar e(v)$ into a fold condition proved for constant $\bar e$ | solving the regime’s equilibrium, which is the same computation the row above needs |
| Separation from Mehrling (1986) | witness grade, and partial. His instruments (wage level, investment level) and his payoffs (present values of consumption and profit) are established through Miebach (2011), a dissertation that restates his model; his own body is unobtainable. So the extraction margin and the objectives separate; the mechanisation law and the state do not | his body, or a second witness reporting his state variables and his supply side |
| Dockner et al. (2000) §7.2 | read at source; the linear-state conditions (7.35)–(7.36) and the Markov-perfectness of open-loop equilibria are stated in the text, not as a numbered theorem; cited as placement, not used as a step | — |
| Lancaster/Pohjola payoffs are linear over a finite undiscounted horizon | verified through de Zeeuw (1992), body read; Hoel’s own payoffs still unread | reading Hoel (1978) at source |

# References

Başar, T., A. Haurie and G. Ricci (1985). On the dominance of
capitalists’ leadership in a ‘feedback-Stackelberg’ solution of a
differential game model of capitalism. *Journal of Economic Dynamics and
Control* 9(1): 101–125.

Bowles, S. (1985). The production process in a competitive economy:
Walrasian, neo-Hobbesian, and Marxian models. *American Economic Review*
75(1): 16–36.

Bowles, S. and H. Gintis (1993). The revenge of homo economicus:
contested exchange and the revival of political economy. *Journal of
Economic Perspectives* 7(1): 83–102.

Cajas Guijarro, J. and L. Vera (2022). The macrodynamics of an
endogenous business cycle model of Marxist inspiration. *Structural
Change and Economic Dynamics* 62: 566–585.

de Zeeuw, A. J. (1992). Note on ‘Nash and Stackelberg solutions in a
differential game model of capitalism’. *Journal of Economic Dynamics
and Control* 16(1): 139–145.

Dockner, E. J., S. Jørgensen, N. Van Long and G. Sorger (2000).
*Differential Games in Economics and Management Science*. Cambridge
University Press.

Goodwin, R. M. (1967). A growth cycle. In C. H. Feinstein (ed.),
*Socialism, Capitalism and Economic Growth*. Cambridge University Press.

Hoel, M. (1978). Distribution and growth as a differential game between
workers and capitalists. *International Economic Review* 19(2): 335–350.

Lancaster, K. (1973). The dynamic inefficiency of capitalism. *Journal
of Political Economy* 81(5): 1092–1109.

Mehrling, P. G. (1986). A classical model of the class struggle: a
game-theoretic approach. *Journal of Political Economy* 94(6):
1280–1303.

Pohjola, M. (1983). Nash and Stackelberg solutions in a differential
game model of capitalism. *Journal of Economic Dynamics and Control* 6:
173–186.

Shimomura, K. (1991). The feedback equilibria of a differential game of
capitalism. *Journal of Economic Dynamics and Control* 15(2): 317–338.

Sorger, G. (1997). Efficient income redistribution in a growing economy.
*Central European Journal for Operations Research and Economics* 5:
41–50.

Veneziani, R. (2007). Exploitation and time. *Journal of Economic
Theory* 132(1): 189–207.
