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
    <span class="news-date">Aug 2–4</span>
    <span class="news-item">I will present <em>The On-the-Run Discount</em> at the <strong>Aarhus Finance Forum 2026</strong>.</span>
  </li>
  <li>
    <span class="news-date">Aug 20–22</span>
    <span class="news-item">I will discuss at the <strong>2026 EFA Annual Meeting</strong> in Ghent, Belgium.</span>
  </li>
  <li>
    <span class="news-date">Sep 25–27</span>
    <span class="news-item">I will present at the <strong>2026 NFA Annual Meeting</strong> in Quebec City, Canada.</span>
  </li>
</ul>
