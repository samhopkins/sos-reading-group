## SoS+TCS Reading Group

The SoS+TCS reading group is a once-monthly virtual reading group on recent papers in theoretical computer science, focusing primarily on the power and limitations of hierarchies of convex programs (like the *Sum of Squares hierarchy*) in algorithm design.

**Format:** We meet for 3 hour whiteboard/chalk/tablet talks, to allow lots of time for interaction and discussion with the speaker. Sessions will have 1-2 coffee breaks. **Everyone is welcome, and no question is too simple.** Our format is inspired by the old [MIT/MSR Reading Group](http://people.csail.mit.edu/madry/reading-group/). Contact the organizers to get on the mailing list for Zoom links.

3 hours is a long time. It is **not rude** to leave at the first break, or even before.

**Date and Time:** By default, the 3rd Wednesday of every month, from 9am-12pm Pacific time. Schedule may vary from month to month.

**Organizers:** [Tselil Schramm](https://tselilschramm.org/) and [Sam Hopkins](http://www.samuelbhopkins.com/)

### Schedule, Winter/Spring 2021

**January ~~27~~ *26* (note this is the 4th ~~Wednesday~~ *Tuesday*), 9am-12pm Pacific:** [Mitali Bafna](https://mitalibafna.github.io/) (Harvard) and [Max Hopkins](http://cseweb.ucsd.edu/~nmhopkin/) (UCSD) on SoS algorithms for Unique Games over certifiable small-set expanders and Johnson schemes. NOTE DATE CHANGE.

<details>
  <summary>Abstract (click to expand)</summary>
  
    <p>The Unique Games Conjecture (UGC) is a central open question in hardness of approximation which posits that it is NP-hard to distinguish between nearly satisfiable and highly unsatisfiable instances of a certain 2-variable constraint satisfaction problem called Unique Games (UG). </p>

    <p>In the first half of this talk, we cover a new strategy for playing (affine) UG based on rounding "low-entropy" solutions --- measured via a novel global potential function --- to sum-of-squares (SoS) semidefinite programs. As a result, we obtain efficient algorithms for UG whenever low-degree sum-of-squares proofs certify good bounds on the small-set-expansion of the underlying constraint graph, notably including well-studied algebraic graphs such as the noisy hypercube and short code. The best-known algorithms for these important classes prior to this work took quasi-polynomial and nearly-exponential time respectively [ABS10]. </p>

    <p>In the second half of the talk, we cover a local-to-global extension of this strategy for constraint graphs whose small, non-expanding sets are SoS-certifiably explained by non-expanding local structure. We focus mainly on the case of the Johnson Scheme, and in particular on how viewing these graphs as random walks on an underlying high-dimensional expander facilitates the understanding of such local-to-global structure. Combined with the UG strategy for certifiable small-set expanders, we discuss how these structure theorems provide an efficient algorithm for UG over the Johnson Scheme whose soundness and runtime depend on the number of unique large eigenvalues, providing a substantial improvement over prior techniques reliant on the total number of large eigenvalues [ABS10].</p>

  <p>Time permitting, we end by discussing connections with the similar characterization of non-expansion for the Grassmann scheme (the q-analog of the Johnson scheme) used to resolve the 2-2 Games Conjecture [KMS18], raising a fascinating interplay between hardness of and algorithms for unique games.</p>

  <p>Based on joint works with Barak, Kaufman, Kothari, Lovett, Schramm, and Steurer: <a href="https://arxiv.org/abs/2006.09969">paper 1</a>, <a href="https://arxiv.org/abs/2011.04658">paper 2</a></p>
</details>

**February 17, 9am-12pm Pacific:** [Madhur Tulsiani](https://ttic.uchicago.edu/~madhurt/) (TTIC) on SoS algorithms and lower bounds for constraint satisfaction problems over high-dimensional expanders. 

<details>
  <summary>Abstract (click to expand)</summary>
  
    <p>This talk will discuss some ways in which notions of expansion in hypergraphs (high-dimensional expansion) can be used to prove algorithmic as well as hardness results for the Sum-of-Squares SDP hierarchy. We plan to discuss two recent results related to Constraint Satisfaction Problems (CSPs) and the SoS hierarchy:</p>
<ul>
        <li> CSP instances on high-dimensional expanders are easy to approximate using O(1) levels of the SoS hierarchy</li>

        <li> Explicit CSP instances on high-dimensional expanders that are hard for \Omega(\sqrt{log n}) levels of the SoS hierarchy. </li>
        </ul>

<p>We will discuss why both the above results are simultaneously true, using different notions of instances "on" high-dimensional expanders, and the expansion properties relevant for both results. Time permitting, we will also discuss some new structural results for expanding hypergraphs, which yield faster algorithms, bypassing the SoS hierarchy.</p>

<p>Based on joint works with Alev, Dinur, Filmus, Harsha, Jeronimo, Quintana, and Srivastava.
    
    </p>
</details>

**March ~~17~~ *18* (note this is the 4th ~~Wednesday~~ *Thursday*), 9am-12pm Pacific:** [Daniel Kane](https://cseweb.ucsd.edu/~dakane/) (UC San Diego) on Small Covers for Near-Zero Sets of Polynomials and Learning Latent Variable Models.

<details>
  <summary>Abstract (click to expand)</summary>
  
    <p>We present a new technique for learning latent variable models with many parameters. The basic idea is to use the method of moments to find a large vector space of polynomials which nearly vanish on all of the parameters of the problem and to use this along with a new structural result to find a small cover of the set of relevant parameters after which exhaustive algorithms can be applied. Using this technique we develop substantially improved algorithms for learning mixtures of spherical Gaussians, mixtures of linear regressions and non-negative linear combinations of ReLUs.</p>
</details>


**April 21, 9am-12pm Pacific:** [Fred Koehler](http://math.mit.edu/~fkoehler/) (MIT) on approximating partition functions.

**May 19, 9am-12pm Pacific:**

**June 16, 9am-12pm Pacific:** Morris Yau (UC Berkeley) on [Online and Distribution-Free Robustness](https://arxiv.org/abs/2010.04157).
