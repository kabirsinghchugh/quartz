Consider a sender ($S$) who has private information about the state of nature, and a second agent (the “receiver” $R$) who will make a decision which depends on the true state. $R$ cannot commit in advance to take actions conditional on the message, so this is not the same as the principle-agent problem. S and R have different, commonly-known preferences. That is, if the state of nature $X$ is distributed $U[0,1]$, S may prefer that action X is taken, while R may find $X+.1$ optimal. There is clearly a useless equilibrium, where no matter what S sends, R takes action $E[X]+.1$ and holds suitable offequilibrium-path beliefs. The more interesting question is whether there are any “influential” cheap talk equilibria?

Intuitively, the answer is no. For instance, in the above example, say the true state of nature is .2. S will then wish to report .1 is the true state, after which R would take action .2, the optimal one for S. But R is smarter than this: she will know S has an incentive to underreport, and therefore will take action .3, or the message sent by S plus .2. But if S thinks R will do this, he will underreport even more, sending message 0. But then….well, you see that hypothesized equilibrium unravels quite quickly.

However, Crawford and Sobel prove that, as long as each agent has utility strictly concave in the action taken, and as long as each agent prefers strictly higher actions as the state of nature increases, then there are indeed influential equilibria, and that these equilibria take a particularly nice form. There is an integer $N(b)$, where b is a measure of how different each agent’s bias is, such that for every integer from 1 to N(b), an equilibrium exists such that the sender partitions his message space into N(b) cells and sends a message measurable to that partition. That is, the sender coarsens the possible messages he can send. For instance, instead of saying that the state of nature is .35 or .62 or whatever, he will simply say “Low” or “High”, where low maps to $[0,.4]$ and high to $[.4,1]$.

Cheap talk can be influential indeed, but only when messages are vague enough that knowledge about biases doesn’t unravel the equilibrium. Further, the most influential equilibrium, meaning the one whose partition has N(b) cells, gives the sender (ex-ante, meaning before he knows the state of nature) and the receiver (in the interim sense) the highest utilities, and this utility is increasing as the difference is bias between the two agents decreases. That is, cheap talk is easier when we “almost” agree.

Three quick notes.

First, as the authors are upfront about, comparative statics are not totally convincing when there are multiple equilibria. They give some reasons why you might want to focus on the equilibria with the finest partition, but none of them are particularly convincing. When Schelling argues for focal equilibria, I interpret this as “easy to compute” or “linked to existing social norms” or something of the sort; “having the finest or coarsest partition of the message space” doesn’t strike me as being very focal! The argument that we can safely ignore Pareto inferior equilibria is also okay more generally, but here the sender, at the time he sends his message, does not consider coarser partition equilibria inferior always. That is, in the example above where R plays $E[X]+.1$ in the uninformative equilibrium, then when the true state actually is .6, S is best off in the completely uninformative equilibrium!

Second, you might wonder how many real-world decisions fit the single-maximum, single-crossing-in-state-of-nature assumptions required for this nice result; potentially persuasive communication is much more complex, often multidimensional, etc. Critiques of this nature have led, since 1982, to many very nice results in the huge cheap talk literature.

Third, the equilibria above is obviously only an “essential” equilibria, in Crawford-Sobel’s terminology. That is, there are many ways R might map messages into beliefs. For instance, he may interpret the message 7 as really meaning 3. In equilibrium, both agents know this mapping, so this point presents no interesting alterations to the potential equilibrium payoffs.