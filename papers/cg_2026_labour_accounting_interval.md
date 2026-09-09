# Two-Input Continuation and the Labour-Accounting Interval
Carlos Galindo Escajeda
2026-09-01

# Abstract

A public stock that enters working-class continuation and is built only from a tax on profits is not cash and is not an additive social wage. At an interior rest point of the laws of motion, a labour-only charge conserves production, uniquely up to scale, if and only if replacement takes less than the product. The same charge does not conserve reproduction. The defect is an identity: owner consumption plus the net growth of both stocks. Inside the class of rules that charge a worker’s period between his private consumption and that plus the period’s gross public investment, every rule relocates the defect and none deletes it while the economy grows and owners consume. The ratio of remainder to charge is therefore an interval rather than a number, degenerate if and only if public investment is zero; and measured against its own ceiling, the width of that interval is a pure instrument ratio in which the growth factor does not appear at all. Closure inside the class can happen only in a window in the growth factor that is never wider than the capital share; that window is empty read as a year and unremarkable read as a generation, and the model does not name its period. Along the split that turns the tax from cash toward the stock, growth cancels the direct provision channel exactly, and the private-consumption ratio rises for the remaining reason: less of the tax comes back as cash. The charge is imposed at rest. It is not a law of value and not a national net social wage.

# 1. Introduction

Classical and Sraffian accounts treat the subsistence of labour as a circulating bundle or as a share of the real wage. In that geometry, conservation of labour magnitudes in the making of goods and conservation of labour magnitudes in the making of workers are one requirement written twice. The value of labour-power is the labour embodied in the wage bundle, and the ratio of surplus to necessary labour is a scalar.

That coextension fails as soon as continuation takes two inputs and the second is a durable public stock financed only out of capital income. Cash paid from that same tax is not the stock. The sum of the cash and the provision is not the continuation index. A labour-only charge that balances the making of goods does not, except on a thin set of primitives, balance the making of workers. What it leaves over is not a residual of measurement. It is owner consumption plus the net enlargement of both stocks, and it has a closed form.

There is a literature that measures the working class’s fiscal position as a single number, the net social wage, and finds the sign of that number turning on an accounting convention (Tonak 1987; Shaikh and Tonak 1994; Maniatis and Passas 2019; Karabacak and Tonak 2022; Charitou, Maniatis and Passas 2025). Charitou, Maniatis and Passas (2025) report, in their own summary of a nine-country panel, that the net fiscal position of the working class is negative in eight countries when indirect taxes are assumed to be partly paid by labour, and that the finding reverses when that assumption is dropped. Their convention is the incidence of taxes attributed to labour. The interval below turns on a different convention: whether the public stock is charged to a worker’s period as upkeep or as gross investment. The two are not rival measurements of one object. The only tax base here is capital income, so the statistic those authors compute is not defined in this model, and nothing below explains a panel or a time series.

**What is restated and what is proved here.** The environment, the two lemmas of Section 3, and Propositions 1 through 4 are the setting of a companion working paper on the two-class dynamic game (Galindo 2026), restated at their own strength with proofs given so that this article stands alone; that paper’s existence and stability theorems are used nowhere below. The contribution is Propositions 5 through 10, Corollary 1 and Theorem 1: that no additive total represents the continuation index unless the public stock has left it; that the labour-only charge closes on production and not on reproduction, with the defect exact; that the defect confines any closing rule to a bounded window in the growth factor; that the ratio of remainder to charge is an interval whose width is public investment, and whose width against its own ceiling is an instrument ratio the growth feedback never enters; that forbidding the magnitude of the good to drift is exactly the closure condition; and that along the fiscal split the growth feedback annihilates the direct provision channel term for term.

The charge is imposed on a rest point of stated laws. It is not an equilibrium object of the game that uses those laws, and constant shares are the class in which the rest point is written. Nothing below shows that restriction to be without loss against state-contingent play. Nothing below is a theory of surplus value or a national net social wage.

# 2. Laws of motion

Time is discrete. Two classes have sizes $N_{W,t}$ and $N_{C,t}$. Capital intensity is $x_t=K_t/N_{W,t}$, public provision per worker is $z_t=G_t/N_{W,t}$, and the class ratio is $\nu_t=N_{C,t}/N_{W,t}$. Output is

$$
Y_t=A K_t^{\alpha}N_{W,t}^{1-\alpha},\qquad w_t:=Y_t/N_{W,t}=A x_t^{\alpha},
$$

with $A>0$ and $\alpha\in(0,1)$. Factors are paid their marginal products.

A tax $\tau\in[0,\bar\tau]\subset[0,1)$ is levied on capital income $\alpha Y_t$. A split $\phi\in[0,1]$ sends the share $\phi$ of the receipt into a public stock $G$ and the share $1-\phi$ to workers as cash. After-tax capital income is reinvested at rate $i$. Depreciation rates satisfy $\delta,\delta_G\in(0,1]$. Consumption and the two stock laws are

$$
C_{W,t}=\bigl[(1-\alpha)+(1-\phi)\tau\alpha\bigr]Y_t,\qquad
C_{C,t}=(1-i)(1-\tau)\alpha Y_t,
$$

$$
K_{t+1}=(1-\delta)K_t+i(1-\tau)\alpha Y_t,\qquad
G_{t+1}=(1-\delta_G)G_t+\phi\tau\alpha Y_t.
$$

Write the four shares of output as

$$
\kappa_W:=(1-\alpha)+(1-\phi)\tau\alpha,\qquad
s_C:=(1-i)(1-\tau)\alpha,\qquad
\iota:=i(1-\tau)\alpha,\qquad
\varsigma:=\phi\tau\alpha,
$$

so that per-head claims are $c_{W,t}=\kappa_W w_t$ and $c_{C,t}=s_C w_t/\nu_t$.

Continuation is a technology that converts this period’s resources into next period’s numbers. It is not a fertility choice and not an altruism parameter:

$$
g_{W,t}=\frac{N_{W,t+1}}{N_{W,t}}=B\bigl(c_{W,t}^{\theta}z_t^{1-\theta}\bigr)^{\gamma},\qquad
g_{C,t}=\frac{N_{C,t+1}}{N_{C,t}}=B\,c_{C,t}^{\gamma},
$$

with $B>0$, $\gamma\in(0,1)$ and $\theta\in(0,1]$. The public argument enters the worker’s map and the owner’s not at all. The outer map $u\mapsto Bu^{\gamma}$ is common to both classes and strictly increasing.

An **interior rest point** of the laws is a tuple $(x,z,\nu,g)$ with $x,z,\nu>0$, $i\in(0,1)$, $\phi\tau\in(0,1)$,

$$
g>\max(1-\delta,\,1-\delta_G),
$$

both stock laws holding with constant shares, and $g_W=g_C=g$. Write

$$
m:=g-1+\delta,\qquad m_G:=g-1+\delta_G,\qquad \zeta:=\delta x/w .
$$

The restriction $i<1$ is not a convenience. At $i=1$ owner consumption vanishes, the owner’s continuation factor is zero, and no interior class ratio exists; that configuration is off the domain rather than on its edge.

# 3. Stationarity

**Lemma 1 (index equalisation).** *Let each class continue through a scalar index of its own inputs, $g_j=F(x_j)$, with $F$ strictly increasing on $(0,\infty)$. At any interior stationary class ratio, $x_W=x_C$, whatever $F$ is and whatever the policy.*

*Proof.* Interior stationarity of $\nu$ is $\nu'=\nu\in(0,\infty)$, which is $g_C=g_W$. A strictly increasing map on $(0,\infty)$ is injective, so $F(x_W)=F(x_C)$ forces $x_W=x_C$. No instrument enters. $\square$

Under the maps of Section 2 this reads

$$
c_W^{\theta}z^{1-\theta}=c_C. \tag{1}
$$

**Lemma 2 (displacement, without a functional form).** *Let $x_C=c_C$ and let the worker’s index be $x_W=h(c_W,z)$ with $h$ nondecreasing in $c_W$ and strictly increasing in $z$. At any interior stationary class ratio, $h(c_W,z)=c_C$. If $(c_1,z_1)$ and $(c_2,z_2)$ both lie on that locus and $z_1<z_2$, then $c_1>c_2$.*

*Proof.* Lemma 1 gives $h(c_W,z)=c_C$. Suppose $z_1<z_2$ and, for contradiction, $c_1\le c_2$. Monotonicity in the first argument gives $h(c_1,z_1)\le h(c_2,z_1)$, and strict monotonicity in the second gives $h(c_2,z_1)<h(c_2,z_2)$. Then $h(c_1,z_1)<h(c_2,z_2)$ while both equal $c_C$. $\square$

No differentiability, no concavity and no continuity is used, and neither $\gamma$ nor $B$ appears. A larger public stock strictly displaces the worker’s private claim, and that displacement is an order property of the stationarity locus rather than a feature of the technology chosen to represent it.

**Proposition 1 (the ratio, and the nesting).** *At an interior rest point, $c_W^{\theta}z^{1-\theta}=c_C$. If $\theta\in(0,1)$,*

$$
\frac{c_C}{c_W}=\Bigl(\frac{z}{c_W}\Bigr)^{1-\theta}=\Bigl(\frac{z}{c_C}\Bigr)^{(1-\theta)/\theta},
\tag{2}
$$

*and along the locus holding $c_C$ fixed, $\partial\ln c_W/\partial\ln z=-(1-\theta)/\theta<0$. Hence $c_C>c_W$ if and only if $z>c_W$, equivalently if and only if $z>c_C$. If $\theta=1$, then $c_W=c_C$ at every policy.*

*Proof.* Lemma 1 gives (1). Divide by $c_W>0$ for the first member of (2); solve (1) for $c_W$ and divide for the second. Logarithmic differentiation of (1) at fixed $c_C$ gives $\theta\,d\ln c_W+(1-\theta)\,d\ln z=0$. The map $t\mapsto t^{1-\theta}$ is strictly increasing and equals one at $t=1$. At $\theta=1$, (1) reads $c_W=c_C$, and no instrument appears in that identity. $\square$

**Proposition 2 (an unfunded public stock).** *Let $\theta\in(0,1)$. If $\phi=0$ and $\delta_G=1$, then $G_{t+1}=0$ and $g_{W,t+1}=0$. If $\phi=0$ and $\delta_G<1$, any stationary $z>0$ forces $g_W=1-\delta_G$, which is outside the interior domain $g>1-\delta_G$.*

*Proof.* The inflow to $G$ is $\phi\tau\alpha Y$. At $\phi=0$ the law is $G_{t+1}=(1-\delta_G)G_t$. If $\delta_G=1$ then $z_{t+1}=0$, and for $\theta<1$ the worker’s factor is zero at the next date. If $\delta_G<1$ and $z'=z>0$, then $g_W=1-\delta_G$. $\square$

The stock law has one source term, and cash from the same tax does not stand in for it. At a stationary positive stock, the whole receipt paid out as cash leaves worker continuation exactly where no tax leaves it.

**Proposition 3 (rest points, reparameterised by the scale of continuation).** *Fix admissible $(\alpha,\delta,\delta_G,\tau,\phi,i,\theta,\gamma)$ with $i\in(0,1)$ and $\phi\tau\in(0,1)$. For every target $g>\max(1-\delta,1-\delta_G)$ there exists a unique $B>0$ inducing an interior rest point of the laws with that growth factor.*

*Proof.* Stationarity of the intensive stocks is $gx=(1-\delta)x+\iota Ax^{\alpha}$ and $gz=(1-\delta_G)z+\varsigma Ax^{\alpha}$, whose unique positive roots are

$$
x(g)=\Bigl(\frac{\iota A}{m}\Bigr)^{1/(1-\alpha)},\qquad
z(g)=\frac{\varsigma A\,x(g)^{\alpha}}{m_G},
\tag{3}
$$

both positive and strictly decreasing on the open range, because $\alpha<1$. Hence $w(g)=Ax(g)^{\alpha}$ and $c_W(g)=\kappa_W w(g)$ are strictly decreasing, and by (1) so is $c_C(g)=c_W(g)^{\theta}z(g)^{1-\theta}$, from $+\infty$ to $0$. Then $g=Bc_C(g)^{\gamma}$ rearranges to $\ln B=\mathcal{H}(g)$, where

$$
\mathcal{H}(g):=\ln g-\gamma\ln c_C(g),\qquad
\mathcal{H}'(g)=\frac{1}{g}+\frac{\gamma\alpha}{(1-\alpha)m}+\frac{\gamma(1-\theta)}{m_G}>0 .
\tag{H}
$$

The derivative follows from $\ln c_C=\theta\ln\kappa_W+\ln w+(1-\theta)(\ln\varsigma-\ln m_G)$ together with $d\ln w/dg=-\alpha/[(1-\alpha)m]$, which is (3). Every term of $\mathcal{H}'$ is positive at an interior rest point, so $\mathcal{H}$ is continuous and strictly increasing, with limits $-\infty$ and $+\infty$ at the two ends of the range. Exactly one $B>0$ solves $\ln B=\mathcal{H}(g)$. The class ratio $\nu=s_C w(g)/c_C(g)$ is then residual and positive. $\square$

Proposition 3 reparameterises rest points of the laws by the scale of continuation. Galindo (2026, Proposition 6) states the rest-point growth factor in closed form given $B$; Proposition 3 is that statement read the other way round, and the reading rather than the closed form is what is used below — to turn a stated tuple into an induced one. A growth factor is not a free parameter, so exhibiting a configuration that satisfies an inequality is worth nothing until some admissible primitive puts a rest point there. It does not characterise play.

**Proposition 4 (adding-up).** *At any interior rest point, $\kappa_W+s_C+\iota+\varsigma=1$. Stationarity gives $\iota w=\delta x+(g-1)x$ and $\varsigma w=\delta_G z+(g-1)z$, and therefore*

$$
w=c_W+c_C\nu+\delta x+(g-1)x+\delta_G z+(g-1)z .
\tag{4}
$$

*Proof.* Expanding the four shares,

$$
(1-\alpha)+(1-\phi)\tau\alpha+(1-i)(1-\tau)\alpha+i(1-\tau)\alpha+\phi\tau\alpha=(1-\alpha)+\alpha=1 .
$$

The two stock identities are the intensive form of the laws at rest. Substitute $c_W=\kappa_W w$ and $c_C\nu=s_C w$. $\square$

**Proposition 5 (the index admits no additive total).** *Let $S=p_c c_W+p_z z$ with $p_c,p_z>0$. If $\theta\in(0,1)$, then $S$ and $c_W^{\theta}z^{1-\theta}$ induce distinct ordinal rankings on an open set of bundles in $\mathbb{R}_{++}^{2}$. They coincide if and only if $\theta=1$.*

*Proof.* Level sets of the index satisfy $z=k\,c_W^{-\theta/(1-\theta)}$ for $k>0$, and

$$
\frac{d^{2}z}{dc_W^{2}}=\frac{\theta}{(1-\theta)^{2}}\,k\,c_W^{-\theta/(1-\theta)-2}>0 ,
$$

so they are strictly convex. Level sets of $S$ are lines. A line cannot coincide with a strictly convex curve on a nonempty open set. At $\theta=1$ the index is $c_W$ itself. $\square$

A published total of wages plus benefits is an instance of $S$. It does not rank continuation bundles, and no choice of prices makes it do so while the public stock is still an input.

# 4. A labour-only charge

Assign an undated magnitude $\chi$ to a unit of the good and take the living labour of one worker over one period as numéraire, $\varpi=1$. Conservation requires each activity to surrender the magnitude of the non-labour inputs it uses up, plus the living labour performed. The assignment is a convention imposed on the rest point. The laws do not derive it, and nothing below pretends they do.

**Proposition 6 (production conserves, and the condition is stronger than interiority).** *Production conserves if and only if $\chi(w-\delta x)=1$. A strictly positive solution exists, uniquely up to scale, if and only if $\zeta<1$, and then*

$$
\chi=\frac{1}{w-\delta x}=\frac{\ell}{1-\zeta}=\ell\sum_{k\ge 0}\zeta^{k},\qquad \ell=1/w .
\tag{5}
$$

*The condition $\zeta<1$ is $g>1-\delta+\delta\iota$, which exceeds interiority by exactly $\delta\iota>0$. At $g\ge 1$ it holds automatically.*

*Proof.* Conservation is $\chi w=\chi\delta x+1$, that is $\chi(w-\delta x)=1$. A strictly positive $\chi$ exists if and only if $w>\delta x$, which is $\zeta<1$; the solution ray is then unique. Dividing by $w$ gives $\chi=\ell/(1-\zeta)$, and $\sum_{k\ge0}\zeta^{k}=1/(1-\zeta)$ converges under the same condition, so the closed form and the reduction to dated labour are one object. Stationarity of $x$ is $mx=\iota w$, so $\zeta=\delta\iota/m$; interiority gives $m>0$, and $i<1$, $\tau<1$, $\alpha<1$ give $\iota<1$. Then $\zeta<1$ clears to $\delta\iota<m$, that is $g>1-\delta+\delta\iota$. At $g\ge1$, $m\ge\delta>\delta\iota$, so $\zeta<\iota<1$. $\square$

The threshold $1-\delta+\delta\iota$ lies strictly below one, by $\delta(1-\iota)>0$. Between it and one lies a band of contracting rest points at which production still conserves; below it lie interior rest points at which no positive magnitude exists at all. What excludes a magnitude at the second is the gross-investment share, not the contraction.

**Proposition 7 (reproduction does not conserve, and the defect is exact).** *Under Proposition 6, reproduction conserves if and only if*

$$
c_W+\delta_G z=(g-1)(w-\delta x).
\tag{6}
$$

*Independently of that demand,*

$$
(w-\delta x)-(c_W+\delta_G z)=c_C\nu+(g-1)(x+z).
\tag{R}
$$

*At an interior rest point with $g\ge 1$ the right-hand side of (R) is strictly positive. Under a closing rule the remainder $R:=(w-\delta x)-b^{\ast}$ equals $(2-g)(w-\delta x)$, and vanishes only at $g=2$.*

*Proof.* Reproduction takes one worker and the period’s bundle and returns $g$ workers, so conserving it would read $1+\chi(c_W+\delta_G z)=g$; under Proposition 6 that is (6). From (4), subtract $\delta x+c_W+\delta_G z$ from both sides to obtain (R), which uses only adding-up and stationarity of the two stocks and is an identity rather than a conservation statement. At an interior rest point $i<1$ and $\tau<1$, so $c_C\nu=s_C w>0$; at $g\ge1$ the second term is nonnegative; the sum is therefore strictly positive. If a rule sets $b^{\ast}=(g-1)(w-\delta x)$, the left-hand side of (R) becomes $(2-g)(w-\delta x)$, and given $w>\delta x$ this vanishes if and only if $g=2$. $\square$

Closure and a vanishing right-hand side are two events, not one, and they are close enough to be welded together by mistake. Closure is $b=(g-1)(w-\delta x)$; a vanishing right member of (R) is $b=w-\delta x$. They coincide only at $g=2$, which Proposition 8 excludes. A rule can close the accounting and leave a remainder, and in the window it does.

The public stock enters (R) twice, with different coefficients. Replacement $\delta_G z$ stands on the worker’s side; net enlargement $(g-1)z$ stands on the other. Stationarity gives $\delta_G z+(g-1)z=\varsigma w$, and likewise $\delta x+(g-1)x=\iota w$: replacing the stock is part of what the period costs, enlarging it is not. Charge the worker nothing for the public stock and the whole of $\varsigma w$ joins the right-hand side of (R). Charge him the period’s gross public investment and the public stock leaves that side entirely. Charge replacement only, as production already charges $\delta x$, and the stock is split. All three placements are exact, and the laws adjudicate none of them.

# 5. The rule class, the window, and the interval

Let $b$ be the physical bundle charged to the reproduction of one worker. The class is

$$
\mathcal{B}:=\bigl\{\,b:\ c_W\le b\le c_W+\varsigma w\,\bigr\}.
$$

The lower vertex charges private consumption alone; the upper charges that plus the period’s gross public investment; the intermediate vertex $c_W+\delta_G z$ charges private consumption plus public replacement. The lower bound is not optional: a rule charging less than what the worker consumes is not charging his period. The upper bound is an argument rather than a derivation. The model contains two charges that the period does not itself produce — labour, and the services of the two stocks — and private capital is already charged to production at $\delta x$, so charging any of it again to reproduction would charge one real thing twice. That leaves the public stock, of which the period contains $\varsigma w$ in total. A rule above the upper vertex charges the worker for something the period does not contain. Results that use only the lower bound are marked where they occur.

**Proposition 8 (the window).** *Reproduction conserves if and only if $b^{\ast}=(g-1)(w-\delta x)$. Inside $\mathcal{B}$ this requires*

$$
\kappa_W\le(g-1)(1-\zeta)\le\kappa_W+\varsigma=(1-\alpha)+\tau\alpha .
\tag{7}
$$

*Necessary conditions on any such $g$ are*

$$
2-\alpha\;\le\;g\;<\;2-\alpha(1-\tau)(1-\delta i)\;\le\;2 ,
\tag{8}
$$

*an interval of length at most $\alpha[\tau+\delta i(1-\tau)]\le\alpha$. Writing $u=g-1$ and*

$$
Q(u):=\frac{u\bigl(u+\delta(1-\iota)\bigr)}{u+\delta},
$$

*$Q$ is strictly increasing on $u\ge0$, and the exact edges of (7), when the band is nonempty, are the unique positive roots of $Q(u)=\kappa_W$ and $Q(u)=\kappa_W+\varsigma$. No interior rest point with $g\le1$ closes under a rule that charges at least $c_W$. No interior rest point with $g\ge2$ closes under a rule that charges at most net output. Under a closing rule, $R=(2-g)(w-\delta x)>0$.*

*Proof.* Dividing $b^{\ast}=(g-1)(w-\delta x)$ by $w>0$ gives $b^{\ast}/w=(g-1)(1-\zeta)$; membership in $\mathcal{B}$ is (7), and $\kappa_W+\varsigma=(1-\alpha)+(1-\phi)\tau\alpha+\phi\tau\alpha$.

*Lower edge.* Every rule in $\mathcal{B}$ charges at least $\kappa_W w$, and $\kappa_W\ge1-\alpha>0$. A positive pair of magnitudes requires $\zeta<1$ by Proposition 6, so $1-\zeta>0$, and the lower edge of (7) then signs $g-1>0$ before any multiplier is used. Only then does $\zeta\ge0$ give

$$
g-1\ \ge\ (g-1)(1-\zeta)\ \ge\ \kappa_W\ \ge\ 1-\alpha ,
$$

which is $g\ge2-\alpha$. The order matters: the multiplier step is $(g-1)\zeta\ge0$ and fails at $g<1$. Where instead $\zeta\ge1$, Proposition 6 supplies no positive pair for any rule to close, so the two cases partition the interior rest points and the exclusion of $g\le1$ carries no condition on $\zeta$.

*Upper edge.* For $u=g-1>0$, $(g-1)\zeta=\delta\iota u/(u+\delta)<\delta\iota$, so $(g-1)(1-\zeta)>(g-1)-\delta\iota$. If (7) holds then $(g-1)-\delta\iota<1-\alpha(1-\tau)$, hence

$$
g<2-\alpha(1-\tau)+\delta i(1-\tau)\alpha=2-\alpha(1-\tau)(1-\delta i)\le2 .
$$

The length of the necessary interval is $\alpha[\tau+\delta i(1-\tau)]$, which is at most $\alpha$ and equals it only at $\delta i=1$.

*Exact edges.* Substituting $\zeta=\delta\iota/m$ and $m=u+\delta$ into the middle member of (7) gives $Q(u)$, and

$$
Q'(u)=\frac{(u+\delta)^{2}-\delta^{2}\iota}{(u+\delta)^{2}}>0
$$

on $u\ge0$ because $\iota<1$. The equation $Q(u)=\kappa$ clears to $u^{2}+u[\delta(1-\iota)-\kappa]-\kappa\delta=0$, whose roots have product $-\kappa\delta<0$; exactly one is positive.

*Remainder.* Proposition 7 gives $R=(2-g)(w-\delta x)$, and (8) forces $g<2$ while Proposition 6 forces $w-\delta x>0$, so $R>0$. Separately, a closing rule of any kind satisfies $R\ge0$, because a period cannot be charged more than it yields; with $w-\delta x>0$ that forces $g\le2$ with no reference to $\mathcal{B}$ at all. $\square$

Three things follow, and they are worth separating. The lower bound $2-\alpha$ uses only the premise that a worker is charged at least what he consumes. The sharpened upper bound uses the class. Drop the class and the general window is $[2-\alpha,\,2]$, closed at the top and exactly as wide as the capital share: a reader who refuses the double-charging argument loses the sharpening and keeps everything else, gaining only the configuration in which a worker’s period is charged the entire net product and nothing at all is left over. That is not a rescue of the accounting. It is the plainest statement of what closing it would cost.

The window is not empty, and it is reached. At $\alpha=3/4$ with $\tau=\phi=i=\delta=\delta_G=1/2$, the band (7) is $[7/16,\,5/8]$ and the closing share is $(g-1)(1-\zeta)=29/64$ at $g=3/2$, so a rule in $\mathcal{B}$ closes the system there. By Proposition 3 that configuration is induced rather than merely stated: with every instrument held, exactly one $B>0$ — here $B\approx33.09$ — puts a rest point at $g=3/2$. The upper edge binds just as concretely. At $\alpha=\tau=i=\delta=\delta_G=1/2$ with $\phi=1$, the point $g=3$ satisfies the lower edge and violates the upper, the closing bundle being $1.95\,w$ against a maximum defensible charge of $0.75\,w$; the unique $B$ inducing it is $B\approx26.18$.

That second witness is the one that matters for how the result is read. Read with the lower bound alone, the failure of closure looks like a shortfall that faster growth would cure. It would not. Above the window the balancing bundle exceeds everything a rule may charge, exactly as below it the bundle falls short of what the worker himself consumes. The two edges refuse for opposite reasons, and both refuse.

The window constrains a growth factor **per model period**. At $\alpha=1/3$ the lower edge is $g\ge5/3$: sixty-seven to one hundred per cent per period. Read as a year against ordinary capital shares and ordinary growth, the interval is empty. Read as a generation, it is unremarkable. The model does not name its period, so the emptiness at a yearly reading is a remark about an unnamed period length and not an empirical finding about any economy.

**Proposition 9 (the interval).** *Let production conserve, and set*

$$
\varepsilon(b):=\frac{(w-\delta x)-b}{b}=\frac{R}{b}.
$$

*As $b$ runs through $\mathcal{B}$, $\varepsilon$ is strictly decreasing and runs over $[\varepsilon_-,\varepsilon_+]$ with*

$$
\varepsilon_+=\frac{1-\zeta}{\kappa_W}-1,\qquad
\varepsilon_-=\frac{(g-1)x+s_C w}{(\kappa_W+\varsigma)\,w},\qquad
\varepsilon_+-\varepsilon_-=\frac{(1-\zeta)\,\varsigma}{\kappa_W(\kappa_W+\varsigma)} .
\tag{9}
$$

*The width vanishes if and only if $\varsigma=0$, and at fixed $(\alpha,\tau,\zeta)$ it is strictly increasing in $\varsigma$. Moreover $\varepsilon\le\varepsilon_+<\alpha/(1-\alpha)$ at every interior rest point with $\zeta>0$. A closing rule would demand $\varepsilon^{\ast}(g)=(2-g)/(g-1)$, strictly decreasing on $(1,2)$ from $\alpha/(1-\alpha)$ at $g=2-\alpha$ to $0$ as $g\uparrow2$; and on $g>1$, condition (7) is exactly $\varepsilon_-\le\varepsilon^{\ast}(g)\le\varepsilon_+$.*

*Proof.* $\partial\varepsilon/\partial b=-(w-\delta x)/b^{2}<0$ whenever $w>\delta x$ and $b>0$, so the endpoints of $\mathcal{B}$ give the endpoints of $\varepsilon$, which are $\kappa_W w$ and $(\kappa_W+\varsigma)w$. The numerator of $\varepsilon_-$ is

$$
(1-\zeta)-(\kappa_W+\varsigma)=(1-\tau)\alpha-\zeta=\frac{(1-\tau)\alpha\,(m-\delta i)}{m}=\frac{(g-1)x+s_C w}{w},
$$

using $\kappa_W+\varsigma+\iota+s_C=1$, $\zeta=\delta\iota/m$, and $\iota w=\delta x+(g-1)x$. Subtracting the two endpoints gives the width. Since $\kappa_W+\varsigma=(1-\alpha)+\tau\alpha$ does not carry $\phi$, write $S$ for it; then the width is $(1-\zeta)\varsigma/[(S-\varsigma)S]$, and $d[\varsigma/(S-\varsigma)]/d\varsigma=S/(S-\varsigma)^{2}>0$. It is zero if and only if $\varsigma=0$, since $1-\zeta>0$ and $\kappa_W>0$.

*Ceiling.* $\kappa_W\ge1-\alpha$ gives $\varepsilon_+\le(\alpha-\zeta)/(1-\alpha)<\alpha/(1-\alpha)$ whenever $\zeta>0$, and $\zeta>0$ whenever $\iota>0$.

*Closing rate.* At $b=b^{\ast}=(g-1)(w-\delta x)$, $\varepsilon^{\ast}=1/(g-1)-1=(2-g)/(g-1)$, with derivative $-1/(g-1)^{2}<0$ and $\varepsilon^{\ast}(2-\alpha)=\alpha/(1-\alpha)$. Multiplying $\varepsilon_+-\varepsilon^{\ast}$ by $(g-1)\kappa_W>0$ recovers the lower edge of (7); multiplying $\varepsilon^{\ast}-\varepsilon_-$ by $(g-1)(\kappa_W+\varsigma)>0$ recovers the upper. On $g>1$ the window and the interval are one restriction written in two coordinates. $\square$

The floor $\varepsilon_-$ is net private accumulation plus owner consumption, measured against the most the class may charge a worker. Those are precisely the two uses of the period’s product that no rule may charge to him, so nothing in the floor cancels: it could vanish only if both vanished, and they vanish together only at $g=1$, which kills accumulation, with $i=1$, which kills owner consumption — a pair that is not in the domain. The floor does not move with the split. The ceiling and the width do.

Two remarks fence the interval. The strict monotonicity in $\varsigma$ is a statement about (9) at a fixed replacement share and a fixed ceiling $S$; it is not a comparative static of the rest point, along which $\zeta$ moves with $g$. And the degeneracy is $\varsigma=0$ and nothing else: $\mathcal{B}$ carries no $\theta$, so the width does not collapse at $\theta=1$. What happens at $\theta=1$ is different and simpler. By Proposition 1 the two classes’ private claims are then equal at every policy, the public stock has left the worker’s map, and there is no displacement for the accounting to be about. The interval survives $\theta=1$; the question does not.

**Corollary 1 (the latitude, net of the growth feedback).** *At any interior rest point at which production conserves,*

$$
\varepsilon_+-\varepsilon_-=\bigl(1+\varepsilon_+\bigr)\,\frac{\varsigma}{\kappa_W+\varsigma},
\qquad
\frac{\varsigma}{\kappa_W+\varsigma}=\frac{\phi\tau\alpha}{(1-\alpha)+\tau\alpha}.
\tag{14}
$$

*The second factor carries no growth factor, no replacement share and no technology constant. It is the fraction of the maximum defensible charge that public investment makes up, and it is strictly increasing in the split and in the tax.*

*Proof.* By (9), $1+\varepsilon_+=(1-\zeta)/\kappa_W$; multiplying by $\varsigma/(\kappa_W+\varsigma)$ gives the width in (9). Proposition 4 gives $\kappa_W+\varsigma=(1-\alpha)+\tau\alpha$, which carries neither $\phi$ nor any dated object, and $\partial[\varsigma/S]/\partial\phi=\tau\alpha/S>0$ at that fixed $S$, with the same computation in $\tau$. $\square$

The two factors of (14) separate what the rest point decides from what the instruments decide. The width itself is not claimed monotone in the split: raising $\phi$ moves the growth factor, and the growth factor’s own response is not signed here, since the numerator $P$ of Theorem 1’s proof changes sign across the family. The width *measured against its own ceiling* is monotone, and unconditionally so, because both the growth factor and the replacement share leave that ratio. So the instrument that turns the tax from cash toward the stock widens the accounting latitude in exactly the proportion in which it funds the stock — and by Theorem 1 below, the same instrument widens the private-consumption gap. One movement, two widenings, and neither of them is the stock getting larger.

Incidence conventions choose a point in $[\varepsilon_-,\varepsilon_+]$. They do not choose whether anything remains.

# 6. Dated magnitudes

Proposition 6 writes the reproduction requirement with the same $\varpi$ on both sides, although that activity spans a period and the $g$ workers it returns exist one date later. The premise — that a unit of the good carries the same magnitude at every date — is load-bearing and was never stated. Dating the magnitudes states it, and shows what it costs.

**Proposition 10 (dating, and the drift).** *Let magnitudes carry the date, remain positive, and write $n_t=w_t-\delta x_t>0$. Production within period $t$ gives $\varpi_t=\chi_t n_t$; reproduction from $t$ to $t+1$ gives $\varpi_t+\chi_t b_t=\varpi_{t+1}g_{W,t}$. Together they determine*

$$
\rho_t:=\frac{\chi_{t+1}}{\chi_t}=\frac{n_t+b_t}{n_{t+1}\,g_{W,t}}
\tag{10}
$$

*and leave $\chi_0$ free, so the dated system always solves for positive magnitudes wherever $n_t>0$. At a rest point,*

$$
\rho-1=\frac{b-b^{\ast}}{g\,(w-\delta x)},
\tag{11}
$$

*so $\rho=1$ if and only if $b=b^{\ast}$.*

*Proof.* Substitute $\varpi_t=\chi_t n_t$ into the reproduction requirement and cancel $\chi_t>0$ to obtain (10). Two unknowns and two requirements at each date fix the ratio and carry neither magnitude. At a rest point $n_{t+1}=n_t=n$ and $g_{W,t}=g$, so $\rho=(n+b)/(ng)$, and subtracting one gives (11). $\square$

The over-determination of Section 4 is therefore the price of forbidding the drift, not a property of the model standing alone. Forbidding it is exactly the closure condition of Proposition 8, and the sign of the drift is the failing edge: below the window $\rho>1$ under every rule in the class, above it $\rho<1$ under every rule. Propositions 7, 8, 9 and 10 are four readings of one scalar.

# 7. The split

**Theorem 1 (the split widens the private-consumption gap, growth feedback included).** *Let $\theta\in(0,1)$. Move $\phi$ at fixed $(\tau,i,B)$, with $g$ reselected by the stationary laws rather than held. Then at every interior rest point*

$$
\frac{\partial}{\partial\phi}\ln\frac{c_C}{c_W}>0 .
$$

*The splits at which $c_C>c_W$ therefore form an upper interval, crossed at most once, whose boundary is the split at which public provision per worker overtakes the worker’s own private claim. Simultaneous movement of $\tau$ or $i$ is not claimed. At $\theta=1$ the gap is identically one.*

*Proof.* Proposition 1 gives $c_C/c_W=(z/c_W)^{1-\theta}$, and (3) gives $z=\varsigma w/m_G$ against $c_W=\kappa_W w$, so

$$
\ln\frac{z}{c_W}=\ln(\phi\tau\alpha)-\ln\kappa_W-\ln m_G .
$$

Write $a:=1/\phi$ and $b:=\tau\alpha/\kappa_W$. Since $\partial\kappa_W/\partial\phi=-\tau\alpha$ and $m_G$ moves only through $g$,

$$
\frac{\partial}{\partial\phi}\ln\frac{z}{c_W}=a+b-\frac{1}{m_G}\frac{\partial g}{\partial\phi}.
\tag{12}
$$

The stationary condition is $\ln B=\mathcal{H}(g)$ of (H), which written out is

$$
\ln g=\ln B+\gamma\theta\ln\kappa_W+\gamma\ln w+\gamma(1-\theta)\ln(\phi\tau\alpha)-\gamma(1-\theta)\ln m_G .
$$

Differentiating at fixed $(\tau,i,B)$ and collecting the coefficients of $\partial g/\partial\phi$,

$$
\mathcal{H}'(g)\,\frac{\partial g}{\partial\phi}=\gamma P,\qquad P=(1-\theta)a-\theta b ,
$$

with $\mathcal{H}'$ as in (H) and strictly positive at an interior rest point. Substituting into (12) and clearing $m_G\mathcal{H}'>0$, the numerator is

$$
\mathcal{N}=(a+b)\Bigl(\frac{m_G}{g}+\frac{\gamma\alpha\,m_G}{(1-\alpha)m}\Bigr)+\gamma(1-\theta)(a+b)-\gamma P
=(a+b)\Bigl(\frac{m_G}{g}+\frac{\gamma\alpha\,m_G}{(1-\alpha)m}\Bigr)+\gamma b ,
$$

because $\gamma(1-\theta)(a+b)-\gamma[(1-\theta)a-\theta b]=\gamma(1-\theta)b+\gamma\theta b=\gamma b$. At an interior rest point with $\phi\tau>0$ every factor of $\mathcal{N}$ is positive, so

$$
\frac{\partial}{\partial\phi}\ln\frac{c_C}{c_W}=\frac{1-\theta}{m_G\,\mathcal{H}'(g)}\,\mathcal{N}>0 .
\tag{13}
$$

The map $\phi\mapsto\ln(c_C/c_W)$ is strictly increasing on $(0,1]$, so the set on which $c_C>c_W$ is an upper interval, and by Proposition 1 its boundary is the split, if any, at which $z=c_W$. $\square$

The growth feedback does not merely fail to reverse the direct effect. It annihilates it. Raising the split feeds the public stock directly, at rate $a$; the stationary system answers by moving the growth factor, which moves the stock’s own investment margin the other way; and what $\gamma P$ removes from $\gamma(1-\theta)(a+b)$ is exactly $\gamma(1-\theta)a$, the whole of the direct channel. What survives is carried by $b=\tau\alpha/\kappa_W$ — the worker’s share of output, which falls as the split rises because less of the tax comes back to him as cash — together with two strictly positive stationary terms. A dominance argument would have been a weaker result and a different one. The cancellation is exact.

A wider private gap is not a worse-off worker. The continuation indices are equalised at every split, and by Lemma 2 the public provision is standing in for the private claim it displaces. What Theorem 1 signs is the measured private ratio, and only along the family that holds $\tau$ and $i$. A reader who measures what a capital-funded social wage does by that ratio will find it widening monotonically, which is the direction such a reader is least likely to guess: what widens the gap is funding the stock more fully, not less.

# 8. Scope

The coextension of production-conservation and reproduction-conservation is an artefact of a one-input subsistence bundle. Once continuation uses a public stock built from profits, a labour-only ledger that balances goods does not, except on a thin window, balance people. The defect is identity (R). Every rule in $\mathcal{B}$ relocates the social wage inside that identity, and none deletes the right-hand side while owners consume and the two stocks grow.

The ratio a related literature reports as a point is, in this instrument set, an interval whose width rises with public investment in continuation and collapses if and only if that investment ceases. Charging conventions select a point in it. They do not decide whether the interval is degenerate.

Closure inside $\mathcal{B}$ is a window in the growth factor, never wider than the capital share, empty at a yearly reading of ordinary calibrations, and not a property of any particular set of national accounts. Faster growth is not an escape: the same laws induce rest points that breach the upper edge, and one is exhibited above.

The fiscal split that builds the stock is the split that widens private cash inequality, and the reason is not that the stock is small. The extra public intensity per worker is eaten exactly by the extra growth it finances. What remains is that less of the tax is paid as cash.

What travels is the unfunded hole, identity (R), the necessary window, the interval $\varepsilon=R/b$, the ratio (14) that takes the growth feedback out of the latitude, the no-drift reading of closure, and the cancellation that signs the private gap. They are statements about a rest point of stated laws under a stated charge, inside the constant-share class, and every step of Sections 4 and 5 is a statement about a single date. Existence of such a configuration under a wider class of policies is not shown here, and neither is uniqueness. This is not a theory of value, not a net social wage for any country, and not an equilibrium of the game whose laws have been used.

# References

-   Charitou, A., T. Maniatis, and C. Passas (2025). “An Investigation of the Net Social Wage Ratio in
    Nine European Countries, 1995–2018.” *Review of Radical Political Economics* 58(1): 5–21.
-   Galindo Escajeda, C. (2026). “Capital-Funded Public Provision and the Private-Consumption Gap in a
    Two-Class Dynamic Game.” Working paper.
-   Karabacak, Y., and E. A. Tonak (2022). “The Net Social Wage in Turkey, 1980–2019.” *Review of
    Radical Political Economics* 54(4): 479–500.
-   Maniatis, T., and C. Passas (2019). “The Net Social Wage in Different Welfare Regimes.” *Capital &
    Class* 43(2): 227–250.
-   Shaikh, A. M., and E. A. Tonak (1994). *Measuring the Wealth of Nations: The Political Economy of
    National Accounts*. Cambridge University Press.
-   Tonak, E. A. (1987). “The U.S. Welfare State and the Working Class, 1952–1980.” *Review of Radical
    Political Economics* 19(1): 47–72.
