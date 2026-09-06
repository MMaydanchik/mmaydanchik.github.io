---
permalink: /
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
<style>
  .papers-section {
    margin-top: 1.6em;
  }
  .papers-section h3 {
    font-weight: 600;
    letter-spacing: 0.02em;
    margin-bottom: 0.6em;
  }
  .paper-entry {
    padding: 1.4em 0;
    border-top: 1px solid #ececec;
  }
  .paper-entry:first-of-type {
    border-top: none;
    padding-top: 0.4em;
  }
  .paper-title {
    font-size: 1.05em;
    font-weight: 600;
    color: #2c4258;
    text-decoration: none !important;
  }
  .paper-title:hover {
    color: #17293a;
    text-decoration: none !important;
  }
  .paper-meta {
    font-size: 0.85em;
    color: #767676;
    margin-top: 0.2em;
  }
  .toggle-row {
    display: flex;
    flex-wrap: wrap;
    gap: 0.5em;
    margin-top: 0.7em;
  }
  .toggle-radio {
    position: absolute;
    opacity: 0;
    pointer-events: none;
  }
  .toggle-btn {
    display: inline-block;
    cursor: pointer;
    font-size: 0.8em;
    color: #767676;
    padding: 0.28em 0.85em;
    border: 1px solid #dcdcdc;
    border-radius: 999px;
    text-decoration: none !important;
    transition: color 0.15s ease, border-color 0.15s ease, background-color 0.15s ease;
    user-select: none;
  }
  .toggle-btn:hover {
    color: #800000;
    border-color: #800000;
  }
  .toggle-radio:checked + .toggle-btn {
    color: #800000;
    border-color: #800000;
    background-color: #fbf1f1;
  }
  .toggle-panel {
    display: none;
    margin-top: 0.7em;
    padding: 0.9em 1em;
    background-color: #fbf1f1;
    border-radius: 6px;
    font-size: 0.9em;
    line-height: 1.5;
    color: #3a3a3a;
  }
  .toggle-panel a {
    color: #565656;
    text-decoration: underline;
  }
  .toggle-panel a:hover {
    color: #800000;
  }
  #ev-abstract:checked ~ #ev-panel-abstract,
  #ev-media:checked ~ #ev-panel-media,
  #nl-abstract:checked ~ #nl-panel-abstract {
    display: block;
  }
  .paper-body {
    display: flex;
    gap: 1.4em;
    align-items: flex-start;
  }
  .paper-body .paper-text {
    flex: 1 1 auto;
    min-width: 0;
  }
  .paper-body .paper-figure {
    flex: 0 0 320px;
    width: 320px;
    height: 203px;
    display: flex;
    align-items: center;
    justify-content: center;
  }
  .paper-figure img {
    max-width: 100%;
    max-height: 100%;
    width: auto;
    height: auto;
    object-fit: contain;
    display: block;
    border-radius: 2px;
  }
  @media (max-width: 700px) {
    .paper-body {
      flex-direction: column;
    }
    .paper-body .paper-figure {
      width: 100%;
      height: auto;
    }
    .paper-figure img {
      width: 100%;
      height: auto;
    }
  }
</style>

Hi! I'm a PhD candidate in the Economics Department at the University of Chicago. My research interests are in industrial organization & environmental economics. I am particularly interested in markets for and the adoption of new green technologies.

<div class="papers-section" markdown="0">

<h1>Working Papers</h1>

<div class="paper-entry">
  <div class="paper-body">
    <div class="paper-text">
      <a class="paper-title" href="/files/EVTrade.pdf">The Effects of &ldquo;Buy American&rdquo;: Electric Vehicles and the Inflation Reduction Act</a>
      <div class="paper-meta">with Hunt Allcott, Reigner Kane, Joseph S. Shapiro, and Felix Tintelnot</div>
      <div class="paper-meta"><em>Revise and Resubmit</em> at <em>American Economic Review</em></div>

      <input type="checkbox" id="ev-abstract" class="toggle-radio">
      <input type="checkbox" id="ev-media" class="toggle-radio">
      <div class="toggle-row">
        <label for="ev-abstract" class="toggle-btn">Abstract</label>
        <a class="toggle-btn toggle-link" href="/files/EVTrade.pdf">PDF</a>
        <a class="toggle-btn toggle-link" href="https://www.nber.org/papers/w33032">NBER WP</a>
        <label for="ev-media" class="toggle-btn">Media</label>
      </div>
      <div id="ev-panel-abstract" class="toggle-panel">We provide the first ex post microeconomic welfare analysis of the electric vehicle (EV) tax credits in the Inflation Reduction Act (IRA). Relative to pre-IRA policy, the credits generated $1.96 in domestic benefits per dollar of government spending, with taxpayer cost of $36,500 per additional EV. Relative to having no EV credits, they yielded $1.11 in domestic benefits per dollar of government spending. A leasing loophole that sidestepped domestic content rules created negative domestic benefits. A prominent example of green industrial policy, the credits harmed foreign countries by shifting surplus to domestic producers and helped them by decreasing CO<sub>2</sub> emissions.</div>
      <div id="ev-panel-media" class="toggle-panel"><a href="https://energyathaas.wordpress.com/2024/10/07/will-the-iras-buy-american-tilt-help-us-electric-vehicles/">Energy Institute Blog</a> &middot; <a href="https://www.nytimes.com/2024/10/07/business/economy/electric-vehicle-tax-credits-study.html">New York Times (October 2024)</a> &middot; <a href="https://www.bloomberg.com/news/articles/2024-11-19/us-electric-vehicle-demand-seen-plunging-27-without-tax-credit">Bloomberg</a> &middot; <a href="https://www.nytimes.com/2024/11/25/business/trump-electric-vehicle-tax-credit.html">New York Times (November 2024)</a> &middot; <a href="https://www.ft.com/content/e8f623e1-c75a-478e-ad8f-aa5b05ef6aa0">Financial Times</a> &middot; <a href="https://finance.yahoo.com/news/not-trivial-ev-sales-could-drop-nearly-30-if-trump-repeals-tax-credit-194135070.html">Yahoo Finance</a></div>
    </div>
    <div class="paper-figure">
      <img src="/images/EVTrade_Fig3.png" alt="Figure from The Effects of Buy American">
    </div>
  </div>
</div>

<div class="paper-entry">
  <div class="paper-body">
    <div class="paper-text">
      <a class="paper-title" href="/files/NLsampling.pdf">Exact Simulation of Nested Logit Draws</a>
      <!-- <div class="paper-meta">In preparation for submission</div> -->

      <input type="checkbox" id="nl-abstract" class="toggle-radio">
      <div class="toggle-row">
        <label for="nl-abstract" class="toggle-btn">Abstract</label>
        <a class="toggle-btn toggle-link" href="/files/NLsampling.pdf">PDF</a>
      </div>
      <div id="nl-panel-abstract" class="toggle-panel">Nested logit models are simple to estimate, but nested logit errors have long resisted closed-form simulation. Galichon (2022) resolves a longstanding conjecture to show that nested logit errors decompose into standard Gumbel and positive stable components. I combine this result with the Kanter (1975) representation of positive stable variables to demonstrate a method for simulating error vectors for arbitrary trees. The method is fast, exact, and scales well. Monte Carlo simulations and timing benchmarks demonstrate its advantages over existing methods employing numerical inversion or moment-matching. It is a practical tool for discrete choice applications requiring full vectors of correlated shocks.</div>
    </div>
    <div class="paper-figure">
      <img src="/images/NLsampling_Fig2c.png" alt="Figure from Exact Simulation of Nested Logit Draws">
    </div>
  </div>
</div>

</div>

### Works In Progress
<div>
"Salesforce Competition in Residential Solar"
</div>

