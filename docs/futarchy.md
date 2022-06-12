---
id: futarchy
title: Futarchy and Zeitgeist DAOs
---

> "Vote on values, but bet on beliefs"
>
> -   Robin Hanson

Futarchy is a mode of governance defined by R. Hanson in _Shall We Vote on
Values, But Bet on Beliefs?_[^1]. An organization governed by futarchy (nation,
city, corporation, DAO, etc.) selects its _values_ (how is _welfare_ measured?)
using some form of a democratic vote, but uses prediction markets in which
informants bet on their _beliefs_ to aggregate information on which policies
will improve the organization's welfare and which policies won't.

[^1]:
    [Shall We Vote on Values, But Bet on Beliefs?](https://www.researchgate.net/publication/277294676_Shall_We_Vote_on_Values_But_Bet_on_Beliefs),
    The Journal of Political Philosophy, 21(2), pp. 151–178 (2013).

## Introduction to Futarchy

In [^1], Hanson suggests the possibility that that many types of governance
suffer from making inefficient policy decisions (in the sense that "most
everyone could expect to gain from other feasible policies") due to our info
institutions' failure to sufficiently aggregate information (where _info
institution_ refers to the following: "public relations teams, organized
interest groups, news media, conversation forums, think tanks, universities,
journals, elite committees, and state agencies").

In _futarchy_, decisions about policy are delegated to prediction markets,
instead of relying on the classical info institution. In these markets, the efficacy of
the policies is estimated in terms of a pre-defined _welfare measure_, a scalar
measure of how well things are going for the organization. Depending on the measurements
made using the prediction markets, the policy is either adopted or not.

## Futarchy by Example

It's easiest to illustrate this new concept through the use of an example.
Suppose that a group wants to make large-scale decisions using futarchy. This is
done by first selecting the welfare measure In case of a publicly traded
company, this could be the stock price of the company.

When a yay/nay decision needs to be made (for example: "Should we fire our CEO?"
for a public company), two scalar markets are created:

-   $M_0$: _What's the stock price next year if the CEO is fired?_
-   $M_1$: _What's the stock price next year if the CEO is not fired?_

These markets will run for some time and provide a prediction for which decision
is _better_: The difference $s_0 - s_1$ between the results of $M_0$ and $M_1$
approximates the effect of firing the CEO on the stock price. If the estimate of
$M_0$ is larger than the estimate of $M_1$, then the stock price is expected to
increase. This means that the CEO actually gets fired and the trades of $M_1$
are cancelled (this is done as we have no way of ever knowing what the stock
price would have been if the CEO had remained in place). If, on the other hand,
the estimate of $M_1$ is larger than that of $M_0$, then the CEO keeps their job
and the trades of $M_0$ are cancelled.

The traders in favor of firing the CEO can buy exposure to both markers by
acquiring LONG shares of $M_0$ and SHORT shares of $M_1$. Similarly, traders in
favor of keeping the CEO in place can buy SHORT of $M_0$ and LONG of $M_1$.
Therefore, both parties have skin in the game regardless of what decision is
eventually made. If the decision turns out to be good (stock price is as
predicted or higher), then the traders will on average profit from participating
in the market. If the decision turns out to be bad (stock price is lower than
predicted), then most traders will suffer losses.

Other scenarios can be approached using this pattern. If a political party
wishes to select a candidate in order to maximize their change of winning, they
might select their share of the popular vote as the welfare measure and open a
scalar market for each candidate $i$:

-   $M^i_0$: _What will our share of the popular vote be if we choose $i$ as
    candidate?_
-   $M^i_1$: _What will our share of the popular vote be if we don't choose $i$
    as candidate?_

Of course, these are only toy examples of applications of futarchy. The
processes above can be embellished in a multitude of ways. For example, maybe
the motion to fire the CEO should only be put into action if there is a _clear_
difference between the stock prices $s_0$ and $s_1$ (say, 5 percent). We
encourage you to take a look at section _IX. A Reference Proposal_ of
[Shall We Vote on Values, But Bet on Beliefs?](https://www.researchgate.net/publication/277294676_Shall_We_Vote_on_Values_But_Bet_on_Beliefs)
for a deeper dive into the topic.

## Vote on Values, Bet on Beliefs

Futarchy lets informants bet their funds on what they believe to be true,
rewarding those who are right and punishing those that are wrong. But as the
examples above show, selecting the welfare measure has wide-ranging
consequences. For example, by setting the welfare measure as the party's share
of the popular vote, the party's candidate is now selected purely on their merit
in winning the election; but is the candidate actually a competent politician
and leader? Maybe firing the CEO will result in a short-term rally, but will
will improvement last? The success of futarchy hinges on the selection of a good
welfare measure.

The previously mentioned section _IX. A Reference Proposal_ suggests that the selection
of welfare measures, proposals 
This is the difference between betting on beliefs about policy regarding the welfare measure in prediction markets,
and voting on values 

The full quote is as follows:

> Under a new form of governance, we could formally defer to betting markets on
> matters of fact, while retaining representative democracy on matters of value.
> That is, we could vote on values but bet on beliefs.
