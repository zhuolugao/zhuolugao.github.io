<style>
  .news-list {
    list-style: none;
    margin: 0.25em 0 0 0;
    padding: 0;
  }
  .news-list li {
    display: flex;
    align-items: baseline;
    gap: 0.9em;
    padding: 0.55em 0;
    border-bottom: 1px solid #eee;
    line-height: 1.5;
  }
  .news-list li:last-child {
    border-bottom: none;
  }
  .news-date {
    flex: 0 0 6.5em;
    font-weight: 700;
    font-size: 0.82em;
    letter-spacing: 0.02em;
    color: #6f777d;
    text-transform: uppercase;
    white-space: nowrap;
  }
  .news-item {
    flex: 1 1 auto;
  }
  @media (max-width: 480px) {
    .news-list li { flex-direction: column; gap: 0.15em; }
    .news-date { flex-basis: auto; }
  }
</style>

<ul class="news-list">
  <li>
    <span class="news-date">2026–27</span>
    <span class="news-item">I will be on the <strong>2026–27 Academic Job Market</strong>.</span>
  </li>
  <li>
    <span class="news-date">Sep 2026</span>
    <span class="news-item">Our paper <em>The On-the-Run Discount</em> won the <strong>Best Paper Award in Asset Pricing</strong> at the NFA Annual Meeting in Quebec City.</span>
  </li>
</ul>
