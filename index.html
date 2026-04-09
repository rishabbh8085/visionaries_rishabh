<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>NeighbourHood – Local Services Marketplace</title>
<link href="https://fonts.googleapis.com/css2?family=Syne:wght@400;500;600;700;800&family=DM+Sans:ital,wght@0,300;0,400;0,500;1,300&display=swap" rel="stylesheet">
<style>
  :root {
    --bg: #0a0a0f;
    --surface: #12121a;
    --surface2: #1a1a26;
    --border: rgba(255,255,255,0.07);
    --accent: #f97316;
    --accent2: #fb923c;
    --green: #22c55e;
    --blue: #3b82f6;
    --purple: #a855f7;
    --text: #f1f0ec;
    --muted: #6b6b80;
    --card-hover: rgba(249,115,22,0.06);
    --radius: 16px;
    --radius-sm: 10px;
  }

  * { margin: 0; padding: 0; box-sizing: border-box; }

  html { scroll-behavior: smooth; }

  body {
    background: var(--bg);
    color: var(--text);
    font-family: 'DM Sans', sans-serif;
    font-size: 15px;
    line-height: 1.6;
    overflow-x: hidden;
  }

  /* NOISE TEXTURE */
  body::before {
    content: '';
    position: fixed;
    inset: 0;
    background-image: url("data:image/svg+xml,%3Csvg viewBox='0 0 256 256' xmlns='http://www.w3.org/2000/svg'%3E%3Cfilter id='noise'%3E%3CfeTurbulence type='fractalNoise' baseFrequency='0.9' numOctaves='4' stitchTiles='stitch'/%3E%3C/filter%3E%3Crect width='100%25' height='100%25' filter='url(%23noise)' opacity='0.03'/%3E%3C/svg%3E");
    pointer-events: none;
    z-index: 9999;
    opacity: 0.4;
  }

  h1, h2, h3, h4, h5 { font-family: 'Syne', sans-serif; }

  /* SCROLLBAR */
  ::-webkit-scrollbar { width: 4px; }
  ::-webkit-scrollbar-track { background: var(--bg); }
  ::-webkit-scrollbar-thumb { background: var(--accent); border-radius: 2px; }

  /* NAV */
  nav {
    position: fixed;
    top: 0; left: 0; right: 0;
    z-index: 1000;
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding: 16px 40px;
    background: rgba(10,10,15,0.85);
    backdrop-filter: blur(20px);
    border-bottom: 1px solid var(--border);
  }

  .logo {
    font-family: 'Syne', sans-serif;
    font-weight: 800;
    font-size: 22px;
    letter-spacing: -0.5px;
  }
  .logo span { color: var(--accent); }

  .nav-links { display: flex; gap: 32px; align-items: center; }
  .nav-links a {
    color: var(--muted);
    text-decoration: none;
    font-size: 14px;
    font-weight: 500;
    transition: color 0.2s;
  }
  .nav-links a:hover { color: var(--text); }

  .nav-actions { display: flex; gap: 12px; align-items: center; }

  .btn {
    padding: 10px 22px;
    border-radius: 8px;
    font-family: 'DM Sans', sans-serif;
    font-size: 14px;
    font-weight: 500;
    cursor: pointer;
    border: none;
    transition: all 0.2s;
    text-decoration: none;
    display: inline-flex;
    align-items: center;
    gap: 8px;
  }

  .btn-ghost {
    background: transparent;
    color: var(--muted);
    border: 1px solid var(--border);
  }
  .btn-ghost:hover { color: var(--text); border-color: rgba(255,255,255,0.2); }

  .btn-primary {
    background: var(--accent);
    color: #fff;
    font-weight: 600;
  }
  .btn-primary:hover { background: var(--accent2); transform: translateY(-1px); box-shadow: 0 8px 24px rgba(249,115,22,0.3); }

  .btn-outline {
    background: transparent;
    color: var(--accent);
    border: 1px solid var(--accent);
  }
  .btn-outline:hover { background: rgba(249,115,22,0.1); }

  .btn-lg { padding: 14px 32px; font-size: 16px; border-radius: 10px; }

  /* PAGES */
  .page { display: none; min-height: 100vh; }
  .page.active { display: block; }

  /* =================== HOME PAGE =================== */
  #page-home { padding-top: 80px; }

  /* HERO */
  .hero {
    position: relative;
    padding: 100px 40px 80px;
    text-align: center;
    overflow: hidden;
  }

  .hero-bg {
    position: absolute;
    inset: 0;
    background: radial-gradient(ellipse 80% 60% at 50% -10%, rgba(249,115,22,0.15) 0%, transparent 60%),
                radial-gradient(ellipse 60% 40% at 10% 80%, rgba(168,85,247,0.08) 0%, transparent 50%),
                radial-gradient(ellipse 50% 40% at 90% 70%, rgba(59,130,246,0.08) 0%, transparent 50%);
    pointer-events: none;
  }

  .hero-badge {
    display: inline-flex;
    align-items: center;
    gap: 8px;
    background: rgba(249,115,22,0.12);
    border: 1px solid rgba(249,115,22,0.3);
    border-radius: 100px;
    padding: 6px 16px;
    font-size: 13px;
    color: var(--accent);
    margin-bottom: 28px;
    font-weight: 500;
  }

  .hero h1 {
    font-size: clamp(42px, 7vw, 84px);
    font-weight: 800;
    line-height: 1.05;
    letter-spacing: -2px;
    margin-bottom: 24px;
    max-width: 900px;
    margin-left: auto;
    margin-right: auto;
  }

  .hero h1 .highlight {
    background: linear-gradient(135deg, var(--accent), #fbbf24);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    background-clip: text;
  }

  .hero p {
    color: var(--muted);
    font-size: 18px;
    max-width: 540px;
    margin: 0 auto 40px;
    line-height: 1.7;
    font-weight: 300;
  }

  .hero-actions {
    display: flex;
    gap: 14px;
    justify-content: center;
    flex-wrap: wrap;
    margin-bottom: 60px;
  }

  .hero-stats {
    display: flex;
    justify-content: center;
    gap: 48px;
    flex-wrap: wrap;
  }

  .stat-item { text-align: center; }
  .stat-num {
    font-family: 'Syne', sans-serif;
    font-size: 32px;
    font-weight: 800;
    color: var(--text);
    letter-spacing: -1px;
  }
  .stat-num span { color: var(--accent); }
  .stat-label { color: var(--muted); font-size: 13px; margin-top: 2px; }

  /* SEARCH BAR */
  .search-section {
    padding: 0 40px 60px;
    max-width: 800px;
    margin: 0 auto;
  }

  .search-card {
    background: var(--surface);
    border: 1px solid var(--border);
    border-radius: var(--radius);
    padding: 8px;
    display: flex;
    gap: 8px;
    align-items: center;
  }

  .search-card input, .search-card select {
    background: transparent;
    border: none;
    color: var(--text);
    font-family: 'DM Sans', sans-serif;
    font-size: 15px;
    padding: 10px 16px;
    outline: none;
    flex: 1;
  }
  .search-card select option { background: var(--surface); }
  .search-card .divider { width: 1px; height: 28px; background: var(--border); }

  /* CATEGORY GRID */
  .section {
    padding: 60px 40px;
    max-width: 1200px;
    margin: 0 auto;
  }

  .section-header {
    display: flex;
    justify-content: space-between;
    align-items: flex-end;
    margin-bottom: 32px;
  }

  .section-title {
    font-size: 28px;
    font-weight: 700;
    letter-spacing: -0.5px;
  }

  .section-sub { color: var(--muted); font-size: 14px; margin-top: 4px; }

  .cat-grid {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(160px, 1fr));
    gap: 16px;
  }

  .cat-card {
    background: var(--surface);
    border: 1px solid var(--border);
    border-radius: var(--radius);
    padding: 24px 16px;
    text-align: center;
    cursor: pointer;
    transition: all 0.25s;
    position: relative;
    overflow: hidden;
  }

  .cat-card::before {
    content: '';
    position: absolute;
    inset: 0;
    background: var(--cat-color, var(--accent));
    opacity: 0;
    transition: opacity 0.25s;
  }

  .cat-card:hover { border-color: var(--cat-color, var(--accent)); transform: translateY(-3px); box-shadow: 0 12px 32px rgba(0,0,0,0.3); }
  .cat-card:hover::before { opacity: 0.06; }

  .cat-icon { font-size: 36px; margin-bottom: 12px; display: block; position: relative; z-index: 1; }
  .cat-name { font-family: 'Syne', sans-serif; font-size: 13px; font-weight: 600; letter-spacing: 0.2px; position: relative; z-index: 1; }
  .cat-count { color: var(--muted); font-size: 11px; margin-top: 4px; position: relative; z-index: 1; }

  /* PROVIDER CARDS */
  .provider-grid {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(280px, 1fr));
    gap: 20px;
  }

  .provider-card {
    background: var(--surface);
    border: 1px solid var(--border);
    border-radius: var(--radius);
    overflow: hidden;
    cursor: pointer;
    transition: all 0.25s;
  }

  .provider-card:hover {
    border-color: rgba(249,115,22,0.3);
    transform: translateY(-3px);
    box-shadow: 0 16px 40px rgba(0,0,0,0.4);
  }

  .provider-img {
    height: 140px;
    background: var(--surface2);
    position: relative;
    overflow: hidden;
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 60px;
  }

  .provider-badge {
    position: absolute;
    top: 12px; right: 12px;
    background: var(--green);
    color: #fff;
    font-size: 10px;
    font-weight: 600;
    padding: 3px 10px;
    border-radius: 100px;
    letter-spacing: 0.5px;
  }

  .provider-body { padding: 18px; }

  .provider-meta {
    display: flex;
    justify-content: space-between;
    align-items: flex-start;
    margin-bottom: 8px;
  }

  .provider-name { font-family: 'Syne', sans-serif; font-weight: 700; font-size: 16px; }
  .provider-role { color: var(--muted); font-size: 12px; margin-top: 2px; }

  .rating {
    display: flex;
    align-items: center;
    gap: 4px;
    font-size: 13px;
    font-weight: 600;
    color: #fbbf24;
  }
  .rating .reviews { color: var(--muted); font-weight: 400; font-size: 12px; }

  .provider-tags {
    display: flex;
    gap: 6px;
    flex-wrap: wrap;
    margin: 10px 0;
  }

  .tag {
    background: rgba(255,255,255,0.05);
    border: 1px solid var(--border);
    border-radius: 100px;
    padding: 3px 10px;
    font-size: 11px;
    color: var(--muted);
  }

  .provider-footer {
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin-top: 14px;
    padding-top: 14px;
    border-top: 1px solid var(--border);
  }

  .price { font-family: 'Syne', sans-serif; font-weight: 700; font-size: 18px; }
  .price span { color: var(--muted); font-size: 12px; font-weight: 400; font-family: 'DM Sans', sans-serif; }

  .avail-dot {
    width: 8px; height: 8px;
    background: var(--green);
    border-radius: 50%;
    display: inline-block;
    box-shadow: 0 0 8px var(--green);
    animation: pulse 2s infinite;
  }

  @keyframes pulse {
    0%, 100% { opacity: 1; }
    50% { opacity: 0.4; }
  }

  /* HOW IT WORKS */
  .how-section {
    padding: 80px 40px;
    background: var(--surface);
    border-top: 1px solid var(--border);
    border-bottom: 1px solid var(--border);
  }

  .how-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
    gap: 40px;
    max-width: 1000px;
    margin: 48px auto 0;
  }

  .how-step { text-align: center; }

  .step-num {
    width: 56px; height: 56px;
    background: rgba(249,115,22,0.1);
    border: 1px solid rgba(249,115,22,0.3);
    border-radius: 14px;
    display: flex;
    align-items: center;
    justify-content: center;
    font-family: 'Syne', sans-serif;
    font-size: 22px;
    font-weight: 800;
    color: var(--accent);
    margin: 0 auto 20px;
  }

  .step-title { font-family: 'Syne', sans-serif; font-weight: 700; font-size: 17px; margin-bottom: 10px; }
  .step-desc { color: var(--muted); font-size: 14px; line-height: 1.7; }

  /* TESTIMONIALS */
  .testimonial-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
    gap: 20px;
  }

  .testimonial-card {
    background: var(--surface);
    border: 1px solid var(--border);
    border-radius: var(--radius);
    padding: 24px;
  }

  .stars { color: #fbbf24; font-size: 14px; margin-bottom: 12px; }
  .testimonial-text { color: var(--muted); font-size: 14px; line-height: 1.7; margin-bottom: 16px; font-style: italic; }
  .testimonial-author { display: flex; align-items: center; gap: 10px; }
  .author-avatar {
    width: 36px; height: 36px;
    border-radius: 50%;
    background: var(--surface2);
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 18px;
  }
  .author-name { font-weight: 600; font-size: 14px; }
  .author-loc { color: var(--muted); font-size: 12px; }

  /* =================== BROWSE PAGE =================== */
  #page-browse { padding-top: 80px; }

  .browse-layout {
    display: grid;
    grid-template-columns: 280px 1fr;
    min-height: calc(100vh - 80px);
  }

  .filter-sidebar {
    background: var(--surface);
    border-right: 1px solid var(--border);
    padding: 32px 24px;
    position: sticky;
    top: 80px;
    height: calc(100vh - 80px);
    overflow-y: auto;
  }

  .filter-section { margin-bottom: 28px; }
  .filter-title { font-family: 'Syne', sans-serif; font-size: 13px; font-weight: 700; letter-spacing: 0.5px; color: var(--muted); text-transform: uppercase; margin-bottom: 14px; }

  .filter-chips { display: flex; flex-wrap: wrap; gap: 8px; }
  .chip {
    padding: 6px 14px;
    border-radius: 100px;
    border: 1px solid var(--border);
    font-size: 13px;
    cursor: pointer;
    transition: all 0.2s;
    background: transparent;
    color: var(--muted);
    font-family: 'DM Sans', sans-serif;
  }
  .chip:hover, .chip.active { background: rgba(249,115,22,0.1); border-color: var(--accent); color: var(--accent); }

  .range-slider {
    -webkit-appearance: none;
    width: 100%;
    height: 4px;
    background: var(--surface2);
    border-radius: 2px;
    outline: none;
    margin-top: 8px;
  }
  .range-slider::-webkit-slider-thumb {
    -webkit-appearance: none;
    width: 18px; height: 18px;
    border-radius: 50%;
    background: var(--accent);
    cursor: pointer;
  }

  .filter-range-label { display: flex; justify-content: space-between; color: var(--muted); font-size: 12px; margin-top: 8px; }

  .browse-content { padding: 32px 40px; }

  .browse-toolbar {
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin-bottom: 24px;
  }

  .result-count { color: var(--muted); font-size: 14px; }
  .result-count strong { color: var(--text); }

  .sort-select {
    background: var(--surface);
    border: 1px solid var(--border);
    color: var(--text);
    padding: 8px 14px;
    border-radius: 8px;
    font-family: 'DM Sans', sans-serif;
    font-size: 14px;
    outline: none;
    cursor: pointer;
  }

  /* =================== PROVIDER DETAIL PAGE =================== */
  #page-detail { padding-top: 80px; }

  .detail-hero {
    background: var(--surface);
    border-bottom: 1px solid var(--border);
    padding: 48px 40px;
  }

  .detail-hero-inner {
    max-width: 1100px;
    margin: 0 auto;
    display: grid;
    grid-template-columns: auto 1fr auto;
    gap: 32px;
    align-items: start;
  }

  .detail-avatar {
    width: 100px; height: 100px;
    border-radius: 20px;
    background: var(--surface2);
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 52px;
    border: 2px solid var(--border);
  }

  .detail-name { font-size: 32px; font-weight: 800; letter-spacing: -0.5px; margin-bottom: 4px; }
  .detail-role { color: var(--accent); font-size: 15px; font-weight: 500; margin-bottom: 12px; }
  .detail-stats { display: flex; gap: 24px; }
  .detail-stat { text-align: center; }
  .detail-stat-num { font-family: 'Syne', sans-serif; font-size: 22px; font-weight: 800; }
  .detail-stat-label { color: var(--muted); font-size: 12px; }

  .booking-panel {
    background: var(--surface2);
    border: 1px solid var(--border);
    border-radius: var(--radius);
    padding: 24px;
    min-width: 280px;
  }

  .booking-price { font-family: 'Syne', sans-serif; font-size: 28px; font-weight: 800; margin-bottom: 4px; }
  .booking-price small { font-size: 14px; color: var(--muted); font-family: 'DM Sans', sans-serif; font-weight: 400; }

  .form-group { margin-bottom: 14px; }
  .form-label { font-size: 12px; font-weight: 600; color: var(--muted); margin-bottom: 6px; display: block; letter-spacing: 0.3px; }
  .form-input, .form-select, .form-textarea {
    width: 100%;
    background: var(--surface);
    border: 1px solid var(--border);
    border-radius: 8px;
    padding: 10px 14px;
    color: var(--text);
    font-family: 'DM Sans', sans-serif;
    font-size: 14px;
    outline: none;
    transition: border-color 0.2s;
  }
  .form-input:focus, .form-select:focus, .form-textarea:focus { border-color: var(--accent); }
  .form-select option, .form-input option { background: var(--surface); }
  .form-textarea { resize: vertical; min-height: 80px; }

  .detail-content {
    max-width: 1100px;
    margin: 0 auto;
    padding: 48px 40px;
    display: grid;
    grid-template-columns: 1fr 320px;
    gap: 48px;
  }

  .section-heading { font-size: 20px; font-weight: 700; margin-bottom: 16px; }

  .service-list { display: flex; flex-direction: column; gap: 12px; margin-bottom: 32px; }
  .service-item {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 14px 18px;
    background: var(--surface);
    border: 1px solid var(--border);
    border-radius: 10px;
    cursor: pointer;
    transition: all 0.2s;
  }
  .service-item:hover { border-color: rgba(249,115,22,0.3); }
  .service-item-name { font-weight: 500; }
  .service-item-dur { color: var(--muted); font-size: 13px; }
  .service-item-price { font-family: 'Syne', sans-serif; font-weight: 700; color: var(--accent); }

  .review-list { display: flex; flex-direction: column; gap: 16px; }
  .review-item { padding: 18px; background: var(--surface); border: 1px solid var(--border); border-radius: 10px; }
  .review-header { display: flex; justify-content: space-between; margin-bottom: 8px; }
  .review-name { font-weight: 600; font-size: 14px; }
  .review-date { color: var(--muted); font-size: 12px; }
  .review-text { color: var(--muted); font-size: 14px; line-height: 1.6; }

  /* =================== DASHBOARD =================== */
  #page-dashboard { padding-top: 80px; }

  .dashboard-layout {
    display: grid;
    grid-template-columns: 220px 1fr;
    min-height: calc(100vh - 80px);
  }

  .dash-sidebar {
    background: var(--surface);
    border-right: 1px solid var(--border);
    padding: 32px 16px;
    position: sticky;
    top: 80px;
    height: calc(100vh - 80px);
  }

  .dash-nav { display: flex; flex-direction: column; gap: 4px; }
  .dash-nav-item {
    display: flex;
    align-items: center;
    gap: 12px;
    padding: 10px 14px;
    border-radius: 8px;
    cursor: pointer;
    color: var(--muted);
    font-size: 14px;
    font-weight: 500;
    transition: all 0.2s;
  }
  .dash-nav-item:hover, .dash-nav-item.active { background: rgba(249,115,22,0.1); color: var(--accent); }
  .dash-nav-item .icon { font-size: 18px; }

  .dash-main { padding: 40px; }

  .dash-greeting { font-size: 28px; font-weight: 800; margin-bottom: 4px; letter-spacing: -0.5px; }
  .dash-sub { color: var(--muted); margin-bottom: 32px; }

  .metrics-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
    gap: 16px;
    margin-bottom: 32px;
  }

  .metric-card {
    background: var(--surface);
    border: 1px solid var(--border);
    border-radius: var(--radius);
    padding: 20px 24px;
    position: relative;
    overflow: hidden;
  }
  .metric-card::after {
    content: '';
    position: absolute;
    bottom: 0; right: 0;
    width: 60px; height: 60px;
    background: var(--accent);
    opacity: 0.06;
    border-radius: 50%;
    transform: translate(20px, 20px);
  }

  .metric-label { color: var(--muted); font-size: 12px; font-weight: 600; letter-spacing: 0.3px; text-transform: uppercase; margin-bottom: 8px; }
  .metric-value { font-family: 'Syne', sans-serif; font-size: 28px; font-weight: 800; letter-spacing: -0.5px; }
  .metric-change { font-size: 12px; margin-top: 4px; }
  .metric-change.up { color: var(--green); }
  .metric-change.down { color: #ef4444; }

  .dash-grid { display: grid; grid-template-columns: 1fr 340px; gap: 24px; }

  .table-card {
    background: var(--surface);
    border: 1px solid var(--border);
    border-radius: var(--radius);
    overflow: hidden;
  }
  .table-header { padding: 18px 20px; border-bottom: 1px solid var(--border); display: flex; justify-content: space-between; align-items: center; }
  .table-title { font-family: 'Syne', sans-serif; font-weight: 700; font-size: 15px; }

  table { width: 100%; border-collapse: collapse; }
  thead th { padding: 12px 20px; text-align: left; font-size: 11px; color: var(--muted); text-transform: uppercase; letter-spacing: 0.5px; font-weight: 600; border-bottom: 1px solid var(--border); background: rgba(255,255,255,0.02); }
  tbody td { padding: 14px 20px; font-size: 14px; border-bottom: 1px solid var(--border); }
  tbody tr:last-child td { border-bottom: none; }
  tbody tr:hover { background: rgba(255,255,255,0.02); }

  .status-badge {
    padding: 3px 10px;
    border-radius: 100px;
    font-size: 11px;
    font-weight: 600;
    letter-spacing: 0.3px;
  }
  .status-confirmed { background: rgba(34,197,94,0.12); color: var(--green); border: 1px solid rgba(34,197,94,0.2); }
  .status-pending { background: rgba(251,191,36,0.12); color: #fbbf24; border: 1px solid rgba(251,191,36,0.2); }
  .status-cancelled { background: rgba(239,68,68,0.12); color: #ef4444; border: 1px solid rgba(239,68,68,0.2); }

  .mini-chart {
    display: flex;
    align-items: flex-end;
    gap: 4px;
    height: 40px;
  }
  .bar {
    flex: 1;
    background: rgba(249,115,22,0.3);
    border-radius: 3px 3px 0 0;
    min-width: 8px;
    transition: background 0.2s;
  }
  .bar:hover { background: var(--accent); }
  .bar.active { background: var(--accent); }

  .notif-list { display: flex; flex-direction: column; }
  .notif-item { padding: 14px 20px; border-bottom: 1px solid var(--border); display: flex; gap: 12px; align-items: flex-start; }
  .notif-item:last-child { border-bottom: none; }
  .notif-dot { width: 8px; height: 8px; border-radius: 50%; background: var(--accent); margin-top: 6px; flex-shrink: 0; }
  .notif-dot.read { background: var(--border); }
  .notif-text { font-size: 13px; color: var(--muted); line-height: 1.5; }
  .notif-text strong { color: var(--text); }
  .notif-time { font-size: 11px; color: var(--muted); margin-top: 3px; }

  /* =================== POST JOB PAGE =================== */
  #page-post { padding-top: 80px; }
  .post-inner { max-width: 640px; margin: 0 auto; padding: 60px 40px; }
  .post-title { font-size: 36px; font-weight: 800; margin-bottom: 6px; letter-spacing: -0.5px; }
  .post-sub { color: var(--muted); margin-bottom: 40px; }

  .step-indicator { display: flex; gap: 8px; margin-bottom: 36px; }
  .step-dot {
    flex: 1;
    height: 4px;
    border-radius: 2px;
    background: var(--surface2);
    transition: background 0.3s;
  }
  .step-dot.active { background: var(--accent); }

  .form-card {
    background: var(--surface);
    border: 1px solid var(--border);
    border-radius: var(--radius);
    padding: 28px;
    margin-bottom: 16px;
  }

  .form-row { display: grid; grid-template-columns: 1fr 1fr; gap: 16px; }

  .upload-zone {
    border: 2px dashed var(--border);
    border-radius: 10px;
    padding: 32px;
    text-align: center;
    cursor: pointer;
    transition: all 0.2s;
    color: var(--muted);
  }
  .upload-zone:hover { border-color: var(--accent); color: var(--text); }
  .upload-icon { font-size: 32px; margin-bottom: 8px; }

  /* TOAST */
  .toast {
    position: fixed;
    bottom: 32px; right: 32px;
    background: var(--surface2);
    border: 1px solid var(--border);
    border-radius: 10px;
    padding: 14px 20px;
    display: flex;
    align-items: center;
    gap: 12px;
    font-size: 14px;
    box-shadow: 0 16px 40px rgba(0,0,0,0.5);
    transform: translateY(80px);
    opacity: 0;
    transition: all 0.3s;
    z-index: 9000;
    max-width: 320px;
  }
  .toast.show { transform: translateY(0); opacity: 1; }
  .toast-icon { font-size: 20px; }

  /* MODAL */
  .modal-overlay {
    position: fixed;
    inset: 0;
    background: rgba(0,0,0,0.75);
    backdrop-filter: blur(8px);
    z-index: 8000;
    display: flex;
    align-items: center;
    justify-content: center;
    opacity: 0;
    pointer-events: none;
    transition: opacity 0.2s;
  }
  .modal-overlay.show { opacity: 1; pointer-events: all; }

  .modal {
    background: var(--surface);
    border: 1px solid var(--border);
    border-radius: var(--radius);
    padding: 36px;
    max-width: 440px;
    width: calc(100% - 40px);
    transform: scale(0.9);
    transition: transform 0.2s;
  }
  .modal-overlay.show .modal { transform: scale(1); }
  .modal-title { font-size: 22px; font-weight: 800; margin-bottom: 6px; }
  .modal-sub { color: var(--muted); font-size: 14px; margin-bottom: 24px; }

  /* ANIMATIONS */
  @keyframes fadeInUp {
    from { opacity: 0; transform: translateY(24px); }
    to { opacity: 1; transform: translateY(0); }
  }

  .page.active .hero { animation: fadeInUp 0.6s ease both; }
  .page.active .search-section { animation: fadeInUp 0.6s 0.1s ease both; }

  /* RESPONSIVE */
  @media (max-width: 768px) {
    nav { padding: 14px 20px; }
    .nav-links { display: none; }
    .hero { padding: 60px 20px 40px; }
    .search-section { padding: 0 20px 40px; }
    .search-card { flex-direction: column; align-items: stretch; }
    .search-card .divider { display: none; }
    .section { padding: 40px 20px; }
    .browse-layout { grid-template-columns: 1fr; }
    .filter-sidebar { display: none; }
    .detail-hero-inner { grid-template-columns: 1fr; }
    .detail-content { grid-template-columns: 1fr; }
    .booking-panel { order: -1; }
    .dashboard-layout { grid-template-columns: 1fr; }
    .dash-sidebar { display: none; }
    .dash-main { padding: 24px 20px; }
    .dash-grid { grid-template-columns: 1fr; }
    .form-row { grid-template-columns: 1fr; }
    .post-inner { padding: 40px 20px; }
    .how-section { padding: 60px 20px; }
  }

  /* FOOTER */
  footer {
    background: var(--surface);
    border-top: 1px solid var(--border);
    padding: 48px 40px 24px;
    margin-top: 80px;
  }
  .footer-grid {
    display: grid;
    grid-template-columns: 2fr 1fr 1fr 1fr;
    gap: 40px;
    max-width: 1100px;
    margin: 0 auto;
    margin-bottom: 40px;
  }
  .footer-brand p { color: var(--muted); font-size: 14px; line-height: 1.7; margin-top: 12px; }
  .footer-col-title { font-family: 'Syne', sans-serif; font-size: 13px; font-weight: 700; letter-spacing: 0.5px; color: var(--text); margin-bottom: 14px; text-transform: uppercase; }
  .footer-links { display: flex; flex-direction: column; gap: 8px; }
  .footer-links a { color: var(--muted); font-size: 14px; text-decoration: none; transition: color 0.2s; }
  .footer-links a:hover { color: var(--text); }
  .footer-bottom { text-align: center; color: var(--muted); font-size: 13px; border-top: 1px solid var(--border); padding-top: 24px; max-width: 1100px; margin: 0 auto; }

  /* CHIP TOGGLE */
  .toggle-group { display: flex; background: var(--surface2); border-radius: 8px; padding: 3px; }
  .toggle-btn {
    flex: 1;
    padding: 8px 16px;
    border: none;
    background: transparent;
    color: var(--muted);
    font-family: 'DM Sans', sans-serif;
    font-size: 14px;
    border-radius: 6px;
    cursor: pointer;
    transition: all 0.2s;
  }
  .toggle-btn.active { background: var(--surface); color: var(--text); box-shadow: 0 1px 4px rgba(0,0,0,0.3); }

  /* MAP PLACEHOLDER */
  .map-placeholder {
    background: var(--surface2);
    border: 1px solid var(--border);
    border-radius: var(--radius);
    height: 240px;
    display: flex;
    align-items: center;
    justify-content: center;
    flex-direction: column;
    gap: 10px;
    color: var(--muted);
    margin-bottom: 20px;
    position: relative;
    overflow: hidden;
  }

  .map-dots {
    position: absolute;
    inset: 0;
    background: 
      radial-gradient(circle at 30% 40%, rgba(249,115,22,0.15) 0%, transparent 40%),
      radial-gradient(circle at 70% 60%, rgba(59,130,246,0.1) 0%, transparent 30%);
  }

  /* CHIP SELECT */
  .checkbox-group { display: flex; flex-direction: column; gap: 8px; }
  .checkbox-label {
    display: flex;
    align-items: center;
    gap: 10px;
    cursor: pointer;
    color: var(--muted);
    font-size: 14px;
    transition: color 0.2s;
  }
  .checkbox-label:hover { color: var(--text); }
  .checkbox-label input { accent-color: var(--accent); width: 16px; height: 16px; }

</style>
</head>
<body>

<!-- NAV -->
<nav>
  <div class="logo">neighbour<span>hood</span></div>
  <div class="nav-links">
    <a href="#" onclick="showPage('home')">Home</a>
    <a href="#" onclick="showPage('browse')">Browse Services</a>
    <a href="#" onclick="showPage('post')">Post a Job</a>
    <a href="#" onclick="showPage('dashboard')">Dashboard</a>
  </div>
  <div class="nav-actions">
    <button class="btn btn-ghost" onclick="showModal('login')">Log In</button>
    <button class="btn btn-primary" onclick="showModal('signup')">Get Started</button>
  </div>
</nav>

<!-- =================== HOME =================== -->
<div id="page-home" class="page active">

  <!-- HERO -->
  <section class="hero">
    <div class="hero-bg"></div>
    <div class="hero-badge">🏘️ Trusted in 200+ Neighbourhoods</div>
    <h1>Your Street's Best<br><span class="highlight">Services, On Demand</span></h1>
    <p>Connect instantly with verified plumbers, tutors, electricians, and delivery agents right in your neighbourhood.</p>
    <div class="hero-actions">
      <button class="btn btn-primary btn-lg" onclick="showPage('browse')">Find a Service ↗</button>
      <button class="btn btn-outline btn-lg" onclick="showModal('provider-signup')">Become a Provider</button>
    </div>
    <div class="hero-stats">
      <div class="stat-item">
        <div class="stat-num">12<span>K+</span></div>
        <div class="stat-label">Service Providers</div>
      </div>
      <div class="stat-item">
        <div class="stat-num">48<span>K+</span></div>
        <div class="stat-label">Jobs Completed</div>
      </div>
      <div class="stat-item">
        <div class="stat-num">4.9<span>★</span></div>
        <div class="stat-label">Average Rating</div>
      </div>
      <div class="stat-item">
        <div class="stat-num">200<span>+</span></div>
        <div class="stat-label">Neighbourhoods</div>
      </div>
    </div>
  </section>

  <!-- SEARCH -->
  <div class="search-section">
    <div class="search-card">
      <input type="text" placeholder="🔍  What service do you need?" id="hero-search">
      <div class="divider"></div>
      <input type="text" placeholder="📍  Your area / pincode">
      <div class="divider"></div>
      <button class="btn btn-primary" onclick="doSearch()">Search</button>
    </div>
  </div>

  <!-- CATEGORIES -->
  <div class="section">
    <div class="section-header">
      <div>
        <div class="section-title">Browse by Category</div>
        <div class="section-sub">Find the right professional for every need</div>
      </div>
      <button class="btn btn-ghost" onclick="showPage('browse')">View all →</button>
    </div>
    <div class="cat-grid" id="cat-grid"></div>
  </div>

  <!-- FEATURED PROVIDERS -->
  <div class="section">
    <div class="section-header">
      <div>
        <div class="section-title">Top Rated Nearby</div>
        <div class="section-sub">Highly reviewed professionals in your area</div>
      </div>
      <button class="btn btn-ghost" onclick="showPage('browse')">See all →</button>
    </div>
    <div class="provider-grid" id="home-providers"></div>
  </div>

  <!-- HOW IT WORKS -->
  <div class="how-section">
    <div style="text-align:center">
      <div class="section-title">How It Works</div>
      <div class="section-sub" style="margin-top:8px">Get help in three simple steps</div>
    </div>
    <div class="how-grid">
      <div class="how-step">
        <div class="step-num">01</div>
        <div class="step-title">Search & Discover</div>
        <div class="step-desc">Browse verified service providers in your neighbourhood by category, rating, or price.</div>
      </div>
      <div class="how-step">
        <div class="step-num">02</div>
        <div class="step-title">Book Instantly</div>
        <div class="step-desc">Pick your time slot, describe your problem, and confirm your booking in seconds.</div>
      </div>
      <div class="how-step">
        <div class="step-num">03</div>
        <div class="step-title">Job Done</div>
        <div class="step-desc">Your provider arrives on time. Pay securely through the app and rate your experience.</div>
      </div>
      <div class="how-step">
        <div class="step-num">04</div>
        <div class="step-title">Safe & Secure</div>
        <div class="step-desc">Every provider is background-verified. Payments are held in escrow until you're satisfied.</div>
      </div>
    </div>
  </div>

  <!-- TESTIMONIALS -->
  <div class="section">
    <div class="section-header">
      <div>
        <div class="section-title">What Customers Say</div>
        <div class="section-sub">Real reviews from real neighbours</div>
      </div>
    </div>
    <div class="testimonial-grid">
      <div class="testimonial-card">
        <div class="stars">★★★★★</div>
        <p class="testimonial-text">"Found a plumber within 20 minutes. He arrived on time, fixed the leak, and the pricing was totally fair. Will definitely use again!"</p>
        <div class="testimonial-author">
          <div class="author-avatar">👩</div>
          <div>
            <div class="author-name">Priya Sharma</div>
            <div class="author-loc">Lajpat Nagar, Delhi</div>
          </div>
        </div>
      </div>
      <div class="testimonial-card">
        <div class="stars">★★★★★</div>
        <p class="testimonial-text">"My son's grades improved dramatically after just one month with the tutor I found here. Great platform for finding local talent!"</p>
        <div class="testimonial-author">
          <div class="author-avatar">👨</div>
          <div>
            <div class="author-name">Rahul Mehta</div>
            <div class="author-loc">Malviya Nagar, Delhi</div>
          </div>
        </div>
      </div>
      <div class="testimonial-card">
        <div class="stars">★★★★☆</div>
        <p class="testimonial-text">"As a freelance electrician, this platform doubled my income in two months. The booking system is seamless and payments are always on time."</p>
        <div class="testimonial-author">
          <div class="author-avatar">👷</div>
          <div>
            <div class="author-name">Vikram Singh</div>
            <div class="author-loc">Service Provider, Noida</div>
          </div>
        </div>
      </div>
    </div>
  </div>

  <!-- CTA BANNER -->
  <div style="padding: 0 40px 60px">
    <div style="background: linear-gradient(135deg, rgba(249,115,22,0.15), rgba(168,85,247,0.08)); border: 1px solid rgba(249,115,22,0.2); border-radius: 20px; padding: 56px 48px; text-align: center; max-width: 1100px; margin: 0 auto; position: relative; overflow: hidden;">
      <div style="position:absolute;inset:0;background:radial-gradient(ellipse 80% 80% at 50% 50%, rgba(249,115,22,0.08), transparent);pointer-events:none;"></div>
      <h2 style="font-size:36px;font-weight:800;margin-bottom:12px;letter-spacing:-0.5px;">Ready to Get Started?</h2>
      <p style="color:var(--muted);max-width:440px;margin:0 auto 28px;font-size:16px;">Join thousands of happy customers and providers in your neighbourhood today.</p>
      <div style="display:flex;gap:12px;justify-content:center;flex-wrap:wrap;">
        <button class="btn btn-primary btn-lg" onclick="showPage('browse')">Find Services Now</button>
        <button class="btn btn-ghost btn-lg" onclick="showModal('provider-signup')">Join as Provider</button>
      </div>
    </div>
  </div>

  <footer>
    <div class="footer-grid">
      <div class="footer-brand">
        <div class="logo" style="font-size:20px">neighbour<span>hood</span></div>
        <p>Connecting local service providers with customers in your community. Trusted, verified, and always nearby.</p>
      </div>
      <div>
        <div class="footer-col-title">Services</div>
        <div class="footer-links">
          <a href="#">Plumbing</a>
          <a href="#">Electrical</a>
          <a href="#">Tutoring</a>
          <a href="#">Delivery</a>
          <a href="#">Cleaning</a>
        </div>
      </div>
      <div>
        <div class="footer-col-title">Company</div>
        <div class="footer-links">
          <a href="#">About Us</a>
          <a href="#">Careers</a>
          <a href="#">Blog</a>
          <a href="#">Press</a>
        </div>
      </div>
      <div>
        <div class="footer-col-title">Support</div>
        <div class="footer-links">
          <a href="#">Help Center</a>
          <a href="#">Safety</a>
          <a href="#">Privacy</a>
          <a href="#">Terms</a>
        </div>
      </div>
    </div>
    <div class="footer-bottom">© 2026 NeighbourHood. All rights reserved. · Made with ❤️ for local communities</div>
  </footer>

</div>

<!-- =================== BROWSE =================== -->
<div id="page-browse" class="page">
  <div class="browse-layout">
    <div class="filter-sidebar">
      <div style="font-family:'Syne',sans-serif;font-weight:800;font-size:16px;margin-bottom:28px;">Filters</div>

      <div class="filter-section">
        <div class="filter-title">Category</div>
        <div class="filter-chips" id="filter-cats"></div>
      </div>

      <div class="filter-section">
        <div class="filter-title">Availability</div>
        <div class="filter-chips">
          <button class="chip active" onclick="toggleChip(this)">Available Now</button>
          <button class="chip" onclick="toggleChip(this)">Today</button>
          <button class="chip" onclick="toggleChip(this)">This Week</button>
        </div>
      </div>

      <div class="filter-section">
        <div class="filter-title">Price Range (₹/hr)</div>
        <input type="range" class="range-slider" min="100" max="2000" value="1000" id="price-range" oninput="updatePriceLabel(this.value)">
        <div class="filter-range-label">
          <span>₹100</span>
          <span id="price-label">Up to ₹1,000</span>
        </div>
      </div>

      <div class="filter-section">
        <div class="filter-title">Minimum Rating</div>
        <div class="filter-chips">
          <button class="chip" onclick="toggleChip(this)">★ 3+</button>
          <button class="chip active" onclick="toggleChip(this)">★ 4+</button>
          <button class="chip" onclick="toggleChip(this)">★ 4.5+</button>
        </div>
      </div>

      <div class="filter-section">
        <div class="filter-title">Experience</div>
        <div class="checkbox-group">
          <label class="checkbox-label"><input type="checkbox" checked> 1+ Years</label>
          <label class="checkbox-label"><input type="checkbox" checked> 3+ Years</label>
          <label class="checkbox-label"><input type="checkbox"> 5+ Years</label>
          <label class="checkbox-label"><input type="checkbox"> 10+ Years</label>
        </div>
      </div>

      <div class="filter-section">
        <div class="filter-title">Distance</div>
        <input type="range" class="range-slider" min="1" max="20" value="5" id="dist-range" oninput="updateDistLabel(this.value)">
        <div class="filter-range-label">
          <span>1 km</span>
          <span id="dist-label">Within 5 km</span>
        </div>
      </div>

      <button class="btn btn-primary" style="width:100%;margin-top:8px;">Apply Filters</button>
      <button class="btn btn-ghost" style="width:100%;margin-top:8px;">Reset</button>
    </div>

    <div class="browse-content">
      <div style="margin-bottom:24px;">
        <div class="search-card" style="margin-bottom:16px;">
          <input type="text" placeholder="🔍  Search services, providers..." style="flex:1;">
          <div class="divider"></div>
          <input type="text" placeholder="📍  Location" style="width:160px;">
          <button class="btn btn-primary" style="padding:8px 18px;">Search</button>
        </div>
        <div style="display:flex;gap:8px;flex-wrap:wrap;" id="active-filter-chips"></div>
      </div>

      <div class="browse-toolbar">
        <div class="result-count"><strong id="result-count">24</strong> providers found near you</div>
        <div style="display:flex;gap:12px;align-items:center;">
          <div class="toggle-group">
            <button class="toggle-btn active">⊞ Grid</button>
            <button class="toggle-btn">☰ List</button>
          </div>
          <select class="sort-select">
            <option>Sort: Relevance</option>
            <option>Sort: Rating ↓</option>
            <option>Sort: Price ↑</option>
            <option>Sort: Distance</option>
          </select>
        </div>
      </div>

      <div class="provider-grid" id="browse-providers"></div>

      <div style="text-align:center;padding:40px;">
        <button class="btn btn-outline btn-lg">Load More Providers</button>
      </div>
    </div>
  </div>
</div>

<!-- =================== PROVIDER DETAIL =================== -->
<div id="page-detail" class="page">
  <div class="detail-hero">
    <div class="detail-hero-inner" id="detail-hero-inner">
      <!-- populated by JS -->
    </div>
  </div>
  <div class="detail-content" id="detail-content">
    <!-- populated by JS -->
  </div>
</div>

<!-- =================== POST JOB =================== -->
<div id="page-post" class="page">
  <div class="post-inner">
    <div class="post-title">Post a Job</div>
    <div class="post-sub">Describe what you need and get matched with the best providers.</div>

    <div class="step-indicator">
      <div class="step-dot active" id="step1-dot"></div>
      <div class="step-dot" id="step2-dot"></div>
      <div class="step-dot" id="step3-dot"></div>
    </div>

    <!-- Step 1 -->
    <div id="post-step1">
      <div class="form-card">
        <div class="section-heading" style="font-size:18px;margin-bottom:20px;">Job Details</div>
        <div class="form-group">
          <label class="form-label">Service Category *</label>
          <select class="form-select">
            <option value="">Select a category</option>
            <option>🔧 Plumbing</option>
            <option>⚡ Electrical</option>
            <option>📚 Tutoring</option>
            <option>🚴 Delivery</option>
            <option>🧹 Cleaning</option>
            <option>🔨 Carpentry</option>
            <option>🎨 Painting</option>
            <option>📷 Photography</option>
          </select>
        </div>
        <div class="form-group">
          <label class="form-label">Job Title *</label>
          <input class="form-input" type="text" placeholder="e.g. Fix kitchen sink leak urgently">
        </div>
        <div class="form-group">
          <label class="form-label">Description *</label>
          <textarea class="form-textarea" rows="4" placeholder="Describe the problem in detail. What needs to be done? Any specific requirements?"></textarea>
        </div>
        <div class="form-row">
          <div class="form-group">
            <label class="form-label">Budget (₹)</label>
            <input class="form-input" type="number" placeholder="Your budget">
          </div>
          <div class="form-group">
            <label class="form-label">Urgency</label>
            <select class="form-select">
              <option>ASAP (within hours)</option>
              <option>Today</option>
              <option>This week</option>
              <option>Flexible</option>
            </select>
          </div>
        </div>
        <div class="form-group">
          <label class="form-label">Photos (optional)</label>
          <div class="upload-zone" onclick="showToast('📸 File upload interface would open here')">
            <div class="upload-icon">📷</div>
            <div style="font-weight:500;margin-bottom:4px;">Drag & drop or click to upload</div>
            <div style="font-size:12px;color:var(--muted);">JPG, PNG up to 10MB each</div>
          </div>
        </div>
      </div>
      <button class="btn btn-primary btn-lg" style="width:100%" onclick="postStep(2)">Continue →</button>
    </div>

    <!-- Step 2 -->
    <div id="post-step2" style="display:none;">
      <div class="form-card">
        <div class="section-heading" style="font-size:18px;margin-bottom:20px;">Location & Schedule</div>
        <div class="form-group">
          <label class="form-label">Service Address *</label>
          <input class="form-input" type="text" placeholder="Full address where service is needed">
        </div>
        <div class="form-group">
          <label class="form-label">Area / Locality</label>
          <input class="form-input" type="text" placeholder="e.g. Lajpat Nagar, South Delhi">
        </div>
        <div class="map-placeholder">
          <div class="map-dots"></div>
          <div style="font-size:32px;position:relative;">📍</div>
          <div style="position:relative;">Map pin drop coming soon</div>
          <div style="font-size:12px;position:relative;color:var(--muted);">Interactive map integration</div>
        </div>
        <div class="form-row">
          <div class="form-group">
            <label class="form-label">Preferred Date</label>
            <input class="form-input" type="date">
          </div>
          <div class="form-group">
            <label class="form-label">Preferred Time</label>
            <select class="form-select">
              <option>Morning (8am-12pm)</option>
              <option>Afternoon (12pm-4pm)</option>
              <option>Evening (4pm-8pm)</option>
            </select>
          </div>
        </div>
      </div>
      <div style="display:flex;gap:12px;">
        <button class="btn btn-ghost btn-lg" style="flex:1" onclick="postStep(1)">← Back</button>
        <button class="btn btn-primary btn-lg" style="flex:2" onclick="postStep(3)">Continue →</button>
      </div>
    </div>

    <!-- Step 3 -->
    <div id="post-step3" style="display:none;">
      <div class="form-card">
        <div class="section-heading" style="font-size:18px;margin-bottom:20px;">Contact & Review</div>
        <div class="form-row">
          <div class="form-group">
            <label class="form-label">Your Name *</label>
            <input class="form-input" type="text" placeholder="Full name">
          </div>
          <div class="form-group">
            <label class="form-label">Phone Number *</label>
            <input class="form-input" type="tel" placeholder="+91 99999 99999">
          </div>
        </div>
        <div class="form-group">
          <label class="form-label">Email</label>
          <input class="form-input" type="email" placeholder="your@email.com">
        </div>
        <div style="background:rgba(249,115,22,0.06);border:1px solid rgba(249,115,22,0.15);border-radius:10px;padding:16px;margin-top:8px;">
          <div style="font-weight:600;margin-bottom:8px;font-size:14px;">📋 Job Summary</div>
          <div style="color:var(--muted);font-size:13px;line-height:1.8;">
            Your job post will be visible to verified providers in your area. You'll receive quotes within minutes and can compare before booking.
          </div>
        </div>
      </div>
      <div style="display:flex;gap:12px;">
        <button class="btn btn-ghost btn-lg" style="flex:1" onclick="postStep(2)">← Back</button>
        <button class="btn btn-primary btn-lg" style="flex:2" onclick="submitJob()">🚀 Post Job</button>
      </div>
    </div>
  </div>
</div>

<!-- =================== DASHBOARD =================== -->
<div id="page-dashboard" class="page">
  <div class="dashboard-layout">
    <div class="dash-sidebar">
      <div class="dash-nav">
        <div class="dash-nav-item active"><span class="icon">📊</span> Overview</div>
        <div class="dash-nav-item"><span class="icon">📅</span> Bookings</div>
        <div class="dash-nav-item"><span class="icon">⭐</span> Reviews</div>
        <div class="dash-nav-item"><span class="icon">💰</span> Earnings</div>
        <div class="dash-nav-item"><span class="icon">🔔</span> Notifications</div>
        <div class="dash-nav-item"><span class="icon">⚙️</span> Settings</div>
      </div>
      <div style="position:absolute;bottom:32px;left:16px;right:16px;">
        <div style="background:rgba(249,115,22,0.08);border:1px solid rgba(249,115,22,0.2);border-radius:10px;padding:14px;">
          <div style="font-size:12px;color:var(--accent);font-weight:600;margin-bottom:4px;">PRO STATUS</div>
          <div style="font-size:13px;color:var(--muted);">Verified Provider ✓</div>
          <div style="font-size:11px;color:var(--muted);margin-top:4px;">Member since Jan 2025</div>
        </div>
      </div>
    </div>

    <div class="dash-main">
      <div class="dash-greeting">Good morning, Ravi! 👋</div>
      <div class="dash-sub">Here's what's happening with your services today.</div>

      <div class="metrics-grid">
        <div class="metric-card">
          <div class="metric-label">Total Earnings</div>
          <div class="metric-value">₹84,200</div>
          <div class="metric-change up">↑ 12% vs last month</div>
        </div>
        <div class="metric-card">
          <div class="metric-label">Jobs Completed</div>
          <div class="metric-value">247</div>
          <div class="metric-change up">↑ 8 this month</div>
        </div>
        <div class="metric-card">
          <div class="metric-label">Avg. Rating</div>
          <div class="metric-value">4.9★</div>
          <div class="metric-change up">↑ from 4.8</div>
        </div>
        <div class="metric-card">
          <div class="metric-label">Pending Requests</div>
          <div class="metric-value">3</div>
          <div class="metric-change" style="color:var(--muted);">Awaiting response</div>
        </div>
        <div class="metric-card">
          <div class="metric-label">Response Rate</div>
          <div class="metric-value">96%</div>
          <div class="metric-change up">Top 5% of providers</div>
        </div>
      </div>

      <div class="dash-grid">
        <div>
          <div class="table-card">
            <div class="table-header">
              <div class="table-title">Recent Bookings</div>
              <button class="btn btn-ghost" style="padding:6px 14px;font-size:12px;">View All</button>
            </div>
            <table>
              <thead>
                <tr>
                  <th>Customer</th>
                  <th>Service</th>
                  <th>Date</th>
                  <th>Amount</th>
                  <th>Status</th>
                </tr>
              </thead>
              <tbody>
                <tr>
                  <td>Anita K.</td>
                  <td>Pipe Repair</td>
                  <td>Today, 2pm</td>
                  <td>₹850</td>
                  <td><span class="status-badge status-confirmed">Confirmed</span></td>
                </tr>
                <tr>
                  <td>Suresh P.</td>
                  <td>Drain Cleaning</td>
                  <td>Today, 5pm</td>
                  <td>₹600</td>
                  <td><span class="status-badge status-pending">Pending</span></td>
                </tr>
                <tr>
                  <td>Meera J.</td>
                  <td>Water Heater Install</td>
                  <td>Apr 10, 10am</td>
                  <td>₹2,200</td>
                  <td><span class="status-badge status-confirmed">Confirmed</span></td>
                </tr>
                <tr>
                  <td>Amit S.</td>
                  <td>Tap Replacement</td>
                  <td>Apr 8</td>
                  <td>₹450</td>
                  <td><span class="status-badge status-confirmed">Confirmed</span></td>
                </tr>
                <tr>
                  <td>Pooja R.</td>
                  <td>Leak Detection</td>
                  <td>Apr 7</td>
                  <td>₹350</td>
                  <td><span class="status-badge status-cancelled">Cancelled</span></td>
                </tr>
              </tbody>
            </table>
          </div>

          <div class="table-card" style="margin-top:20px;">
            <div class="table-header">
              <div class="table-title">Weekly Earnings</div>
              <div style="color:var(--muted);font-size:13px;">Apr 3 – Apr 9</div>
            </div>
            <div style="padding:20px;">
              <div style="display:flex;justify-content:space-between;align-items:flex-end;margin-bottom:8px;">
                <div style="font-size:28px;font-weight:800;font-family:'Syne',sans-serif;">₹18,450</div>
                <div style="color:var(--green);font-size:13px;">↑ 15% vs last week</div>
              </div>
              <div style="display:flex;align-items:flex-end;gap:6px;height:80px;margin-top:16px;">
                <div style="flex:1;display:flex;flex-direction:column;align-items:center;gap:6px;">
                  <div style="flex:1;width:100%;background:rgba(249,115,22,0.25);border-radius:4px 4px 0 0;" title="Mon: ₹2,400"></div>
                  <div style="font-size:10px;color:var(--muted);">M</div>
                </div>
                <div style="flex:1;display:flex;flex-direction:column;align-items:center;gap:6px;">
                  <div style="flex:1;width:100%;background:rgba(249,115,22,0.4);border-radius:4px 4px 0 0;margin-top:20px;" title="Tue"></div>
                  <div style="font-size:10px;color:var(--muted);">T</div>
                </div>
                <div style="flex:1;display:flex;flex-direction:column;align-items:center;gap:6px;">
                  <div style="flex:1;width:100%;background:var(--accent);border-radius:4px 4px 0 0;margin-top:5px;" title="Wed"></div>
                  <div style="font-size:10px;color:var(--muted);">W</div>
                </div>
                <div style="flex:1;display:flex;flex-direction:column;align-items:center;gap:6px;">
                  <div style="flex:1;width:100%;background:rgba(249,115,22,0.35);border-radius:4px 4px 0 0;margin-top:28px;" title="Thu"></div>
                  <div style="font-size:10px;color:var(--muted);">T</div>
                </div>
                <div style="flex:1;display:flex;flex-direction:column;align-items:center;gap:6px;">
                  <div style="flex:1;width:100%;background:rgba(249,115,22,0.5);border-radius:4px 4px 0 0;margin-top:12px;" title="Fri"></div>
                  <div style="font-size:10px;color:var(--muted);">F</div>
                </div>
                <div style="flex:1;display:flex;flex-direction:column;align-items:center;gap:6px;">
                  <div style="flex:1;width:100%;background:rgba(249,115,22,0.2);border-radius:4px 4px 0 0;margin-top:45px;" title="Sat"></div>
                  <div style="font-size:10px;color:var(--muted);">S</div>
                </div>
                <div style="flex:1;display:flex;flex-direction:column;align-items:center;gap:6px;">
                  <div style="flex:1;width:100%;background:rgba(249,115,22,0.15);border-radius:4px 4px 0 0;margin-top:55px;" title="Sun"></div>
                  <div style="font-size:10px;color:var(--muted);">S</div>
                </div>
              </div>
            </div>
          </div>
        </div>

        <div style="display:flex;flex-direction:column;gap:20px;">
          <div class="table-card">
            <div class="table-header">
              <div class="table-title">Notifications</div>
              <span style="background:var(--accent);color:#fff;font-size:11px;padding:2px 8px;border-radius:100px;font-weight:700;">3 New</span>
            </div>
            <div class="notif-list">
              <div class="notif-item">
                <div class="notif-dot"></div>
                <div>
                  <div class="notif-text"><strong>New booking request</strong> from Anita for pipe repair today at 2pm</div>
                  <div class="notif-time">10 mins ago</div>
                </div>
              </div>
              <div class="notif-item">
                <div class="notif-dot"></div>
                <div>
                  <div class="notif-text"><strong>Payment received</strong> ₹850 from Suresh Patel</div>
                  <div class="notif-time">1 hour ago</div>
                </div>
              </div>
              <div class="notif-item">
                <div class="notif-dot"></div>
                <div>
                  <div class="notif-text"><strong>New review</strong> – Meera gave you ★★★★★</div>
                  <div class="notif-time">3 hours ago</div>
                </div>
              </div>
              <div class="notif-item">
                <div class="notif-dot read"></div>
                <div>
                  <div class="notif-text"><strong>Profile verified</strong> – Your ID check is complete</div>
                  <div class="notif-time">Yesterday</div>
                </div>
              </div>
              <div class="notif-item">
                <div class="notif-dot read"></div>
                <div>
                  <div class="notif-text">Reminder: <strong>Drain cleaning job</strong> tomorrow at 9am, Hauz Khas</div>
                  <div class="notif-time">Yesterday</div>
                </div>
              </div>
            </div>
          </div>

          <div class="table-card">
            <div class="table-header">
              <div class="table-title">Quick Actions</div>
            </div>
            <div style="padding:16px;display:flex;flex-direction:column;gap:10px;">
              <button class="btn btn-primary" style="width:100%;justify-content:center;" onclick="showPage('post')">📋 Post a New Job</button>
              <button class="btn btn-ghost" style="width:100%;justify-content:center;" onclick="showToast('📅 Calendar view coming soon')">📅 Manage Schedule</button>
              <button class="btn btn-ghost" style="width:100%;justify-content:center;" onclick="showToast('✏️ Profile editor opened')">✏️ Edit Profile</button>
              <button class="btn btn-ghost" style="width:100%;justify-content:center;" onclick="showToast('💳 Payout initiated')">💳 Request Payout</button>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</div>

<!-- LOGIN MODAL -->
<div class="modal-overlay" id="modal-login">
  <div class="modal">
    <div class="modal-title">Welcome Back</div>
    <div class="modal-sub">Log in to your NeighbourHood account</div>
    <div class="toggle-group" style="margin-bottom:20px;">
      <button class="toggle-btn active">Customer</button>
      <button class="toggle-btn">Service Provider</button>
    </div>
    <div class="form-group">
      <label class="form-label">Email / Phone</label>
      <input class="form-input" type="text" placeholder="your@email.com">
    </div>
    <div class="form-group">
      <label class="form-label">Password</label>
      <input class="form-input" type="password" placeholder="••••••••">
    </div>
    <div style="text-align:right;margin-bottom:20px;"><a href="#" style="color:var(--accent);font-size:13px;">Forgot password?</a></div>
    <button class="btn btn-primary btn-lg" style="width:100%;" onclick="closeModal('login');showPage('dashboard');showToast('👋 Welcome back!')">Log In</button>
    <div style="text-align:center;margin-top:16px;color:var(--muted);font-size:13px;">Don't have an account? <a href="#" style="color:var(--accent);" onclick="closeModal('login');showModal('signup')">Sign up</a></div>
    <button onclick="closeModal('login')" style="position:absolute;top:20px;right:20px;background:none;border:none;color:var(--muted);font-size:20px;cursor:pointer;">✕</button>
  </div>
</div>

<!-- SIGNUP MODAL -->
<div class="modal-overlay" id="modal-signup">
  <div class="modal">
    <div class="modal-title">Join NeighbourHood</div>
    <div class="modal-sub">Create your account in seconds</div>
    <div class="toggle-group" style="margin-bottom:20px;">
      <button class="toggle-btn active">I need services</button>
      <button class="toggle-btn">I offer services</button>
    </div>
    <div class="form-row">
      <div class="form-group">
        <label class="form-label">First Name</label>
        <input class="form-input" type="text" placeholder="Rahul">
      </div>
      <div class="form-group">
        <label class="form-label">Last Name</label>
        <input class="form-input" type="text" placeholder="Sharma">
      </div>
    </div>
    <div class="form-group">
      <label class="form-label">Phone / Email</label>
      <input class="form-input" type="text" placeholder="+91 99999 99999">
    </div>
    <div class="form-group">
      <label class="form-label">Password</label>
      <input class="form-input" type="password" placeholder="Min. 8 characters">
    </div>
    <button class="btn btn-primary btn-lg" style="width:100%;margin-top:4px;" onclick="closeModal('signup');showPage('dashboard');showToast('🎉 Account created! Welcome!')">Create Account</button>
    <div style="text-align:center;margin-top:14px;color:var(--muted);font-size:12px;">By signing up you agree to our <a href="#" style="color:var(--accent);">Terms</a> & <a href="#" style="color:var(--accent);">Privacy Policy</a></div>
    <button onclick="closeModal('signup')" style="position:absolute;top:20px;right:20px;background:none;border:none;color:var(--muted);font-size:20px;cursor:pointer;">✕</button>
  </div>
</div>

<!-- PROVIDER SIGNUP MODAL -->
<div class="modal-overlay" id="modal-provider-signup">
  <div class="modal">
    <div class="modal-title">Become a Provider</div>
    <div class="modal-sub">Start earning by offering your skills in your neighbourhood</div>
    <div class="form-group">
      <label class="form-label">Service Category</label>
      <select class="form-select">
        <option>🔧 Plumbing</option>
        <option>⚡ Electrical Work</option>
        <option>📚 Tutoring / Education</option>
        <option>🚴 Delivery Services</option>
        <option>🧹 Cleaning</option>
        <option>🔨 Carpentry</option>
      </select>
    </div>
    <div class="form-group">
      <label class="form-label">Years of Experience</label>
      <select class="form-select">
        <option>Less than 1 year</option>
        <option>1–3 years</option>
        <option>3–5 years</option>
        <option>5–10 years</option>
        <option>10+ years</option>
      </select>
    </div>
    <div class="form-group">
      <label class="form-label">Hourly Rate (₹)</label>
      <input class="form-input" type="number" placeholder="e.g. 500">
    </div>
    <button class="btn btn-primary btn-lg" style="width:100%;margin-top:4px;" onclick="closeModal('provider-signup');showToast('✅ Application submitted! We\'ll verify your profile within 24 hours.')">Submit Application</button>
    <button onclick="closeModal('provider-signup')" style="position:absolute;top:20px;right:20px;background:none;border:none;color:var(--muted);font-size:20px;cursor:pointer;">✕</button>
  </div>
</div>

<!-- BOOKING MODAL -->
<div class="modal-overlay" id="modal-book">
  <div class="modal">
    <div class="modal-title">Confirm Booking</div>
    <div class="modal-sub" id="book-modal-sub">You're booking a service</div>
    <div class="form-group">
      <label class="form-label">Select Date</label>
      <input class="form-input" type="date">
    </div>
    <div class="form-group">
      <label class="form-label">Select Time</label>
      <select class="form-select">
        <option>9:00 AM</option>
        <option>10:00 AM</option>
        <option>11:00 AM</option>
        <option>2:00 PM</option>
        <option>3:00 PM</option>
        <option>4:00 PM</option>
        <option>5:00 PM</option>
      </select>
    </div>
    <div class="form-group">
      <label class="form-label">Notes for Provider</label>
      <textarea class="form-textarea" placeholder="Any specific instructions or details..."></textarea>
    </div>
    <div style="background:var(--surface2);border-radius:8px;padding:14px;margin-bottom:16px;font-size:13px;">
      <div style="display:flex;justify-content:space-between;margin-bottom:6px;"><span style="color:var(--muted);">Service fee</span><span id="book-price">₹500</span></div>
      <div style="display:flex;justify-content:space-between;margin-bottom:6px;"><span style="color:var(--muted);">Platform fee</span><span>₹25</span></div>
      <div style="display:flex;justify-content:space-between;padding-top:8px;border-top:1px solid var(--border);font-weight:700;"><span>Total</span><span id="book-total">₹525</span></div>
    </div>
    <button class="btn btn-primary btn-lg" style="width:100%;" onclick="confirmBooking()">🔒 Confirm & Pay</button>
    <button onclick="closeModal('book')" style="position:absolute;top:20px;right:20px;background:none;border:none;color:var(--muted);font-size:20px;cursor:pointer;">✕</button>
  </div>
</div>

<!-- TOAST -->
<div class="toast" id="toast">
  <span class="toast-icon" id="toast-icon">✅</span>
  <span id="toast-msg">Action completed!</span>
</div>

<script>
// ===================== DATA =====================
const categories = [
  { name: 'Plumbing', icon: '🔧', count: 142, color: '#3b82f6' },
  { name: 'Electrical', icon: '⚡', count: 98, color: '#f59e0b' },
  { name: 'Tutoring', icon: '📚', count: 231, color: '#8b5cf6' },
  { name: 'Delivery', icon: '🚴', count: 187, color: '#10b981' },
  { name: 'Cleaning', icon: '🧹', count: 156, color: '#ec4899' },
  { name: 'Carpentry', icon: '🔨', count: 73, color: '#f97316' },
  { name: 'Painting', icon: '🎨', count: 61, color: '#06b6d4' },
  { name: 'Photography', icon: '📷', count: 44, color: '#a855f7' },
  { name: 'Gardening', icon: '🌱', count: 89, color: '#22c55e' },
  { name: 'AC Repair', icon: '❄️', count: 112, color: '#6366f1' },
];

const providers = [
  { id: 1, name: 'Ravi Kumar', role: 'Master Plumber', emoji: '🔧', rating: 4.9, reviews: 284, price: 400, priceUnit: '/hr', tags: ['Leak Fix', 'Pipe Fitting', 'Drain'], avail: true, badge: 'Top Rated', exp: '8 yrs', jobs: 612, area: 'Lajpat Nagar' },
  { id: 2, name: 'Priya Saxena', role: 'Home Tutor – Maths & Science', emoji: '📚', rating: 4.8, reviews: 193, price: 600, priceUnit: '/hr', tags: ['Class 10', 'JEE Prep', 'CBSE'], avail: true, badge: 'Verified', exp: '5 yrs', jobs: 340, area: 'Malviya Nagar' },
  { id: 3, name: 'Suresh Electricals', role: 'Licensed Electrician', emoji: '⚡', rating: 4.7, reviews: 148, price: 350, priceUnit: '/hr', tags: ['Wiring', 'Short Circuit', 'Fan Install'], avail: false, badge: null, exp: '12 yrs', jobs: 891, area: 'GK-2' },
  { id: 4, name: 'Ankit Delivery', role: 'Same-Day Courier', emoji: '🚴', rating: 4.6, reviews: 87, price: 150, priceUnit: '/delivery', tags: ['Documents', 'Food', 'Parcels'], avail: true, badge: 'New', exp: '2 yrs', jobs: 1203, area: 'Hauz Khas' },
  { id: 5, name: 'Neha Cleaning Co.', role: 'Professional Cleaner', emoji: '🧹', rating: 4.9, reviews: 321, price: 500, priceUnit: '/session', tags: ['Deep Clean', 'Office', 'Post-Party'], avail: true, badge: 'Top Rated', exp: '6 yrs', jobs: 445, area: 'Vasant Kunj' },
  { id: 6, name: 'Amit Sharma', role: 'AC Technician', emoji: '❄️', rating: 4.5, reviews: 112, price: 450, priceUnit: '/hr', tags: ['Servicing', 'Installation', 'Repair'], avail: true, badge: null, exp: '9 yrs', jobs: 728, area: 'Dwarka' },
];

// ===================== RENDER =====================
function renderCategories() {
  const grid = document.getElementById('cat-grid');
  const filterCats = document.getElementById('filter-cats');
  if (!grid) return;
  grid.innerHTML = categories.map(c => `
    <div class="cat-card" style="--cat-color:${c.color}" onclick="filterByCategory('${c.name}')">
      <span class="cat-icon">${c.icon}</span>
      <div class="cat-name">${c.name}</div>
      <div class="cat-count">${c.count} providers</div>
    </div>
  `).join('');

  if (filterCats) {
    filterCats.innerHTML = categories.map(c => `
      <button class="chip" onclick="toggleChip(this)">${c.icon} ${c.name}</button>
    `).join('');
  }
}

function renderProviders(containerId, list) {
  const el = document.getElementById(containerId);
  if (!el) return;
  el.innerHTML = list.map(p => `
    <div class="provider-card" onclick="showDetail(${p.id})">
      <div class="provider-img" style="background:linear-gradient(135deg,rgba(255,255,255,0.03),rgba(255,255,255,0.01))">
        <span style="font-size:64px">${p.emoji}</span>
        ${p.badge ? `<div class="provider-badge">${p.badge}</div>` : ''}
      </div>
      <div class="provider-body">
        <div class="provider-meta">
          <div>
            <div class="provider-name">${p.name}</div>
            <div class="provider-role">${p.role}</div>
          </div>
          <div class="rating">★ ${p.rating} <span class="reviews">(${p.reviews})</span></div>
        </div>
        <div class="provider-tags">
          ${p.tags.map(t => `<span class="tag">${t}</span>`).join('')}
        </div>
        <div style="font-size:12px;color:var(--muted);margin-top:6px;">📍 ${p.area} · ${p.exp} experience</div>
        <div class="provider-footer">
          <div class="price">₹${p.price} <span>${p.priceUnit}</span></div>
          <div style="display:flex;align-items:center;gap:6px;font-size:12px;color:${p.avail ? 'var(--green)' : 'var(--muted)'}">
            ${p.avail ? `<span class="avail-dot"></span> Available` : '○ Busy'}
          </div>
        </div>
      </div>
    </div>
  `).join('');
}

function showDetail(id) {
  const p = providers.find(x => x.id === id);
  if (!p) return;

  const hero = document.getElementById('detail-hero-inner');
  hero.innerHTML = `
    <div class="detail-avatar">${p.emoji}</div>
    <div>
      <div style="display:flex;align-items:center;gap:12px;margin-bottom:4px;">
        <div class="detail-name">${p.name}</div>
        ${p.badge ? `<span class="provider-badge" style="position:relative;top:0;right:0">${p.badge}</span>` : ''}
      </div>
      <div class="detail-role">${p.role}</div>
      <div style="display:flex;gap:8px;flex-wrap:wrap;margin:10px 0;">
        ${p.tags.map(t => `<span class="tag">${t}</span>`).join('')}
      </div>
      <div class="detail-stats">
        <div class="detail-stat"><div class="detail-stat-num">★ ${p.rating}</div><div class="detail-stat-label">Rating</div></div>
        <div class="detail-stat"><div class="detail-stat-num">${p.reviews}</div><div class="detail-stat-label">Reviews</div></div>
        <div class="detail-stat"><div class="detail-stat-num">${p.jobs}</div><div class="detail-stat-label">Jobs Done</div></div>
        <div class="detail-stat"><div class="detail-stat-num">${p.exp}</div><div class="detail-stat-label">Experience</div></div>
      </div>
    </div>
    <div class="booking-panel">
      <div class="booking-price">₹${p.price} <small>${p.priceUnit}</small></div>
      <div style="color:var(--muted);font-size:13px;margin-bottom:20px;">${p.avail ? '<span style="color:var(--green)">● Available now</span>' : '○ Currently busy'}</div>
      <div class="form-group">
        <label class="form-label">Select Service</label>
        <select class="form-select">
          <option>Standard Visit</option>
          <option>Emergency Call</option>
          <option>Full Inspection</option>
        </select>
      </div>
      <div class="form-group">
        <label class="form-label">Preferred Time</label>
        <select class="form-select">
          <option>Morning (9am-12pm)</option>
          <option>Afternoon (12pm-4pm)</option>
          <option>Evening (4pm-7pm)</option>
        </select>
      </div>
      <button class="btn btn-primary btn-lg" style="width:100%;justify-content:center;margin-top:4px;" onclick="event.stopPropagation();showModal('book');document.getElementById('book-modal-sub').textContent='Booking with ${p.name}';document.getElementById('book-price').textContent='₹${p.price}';document.getElementById('book-total').textContent='₹${p.price + 25}'">📅 Book Now</button>
      <button class="btn btn-ghost" style="width:100%;justify-content:center;margin-top:8px;" onclick="showToast('💬 Chat feature coming soon!')">💬 Message Provider</button>
    </div>
  `;

  const content = document.getElementById('detail-content');
  content.innerHTML = `
    <div>
      <div class="section-heading">Services Offered</div>
      <div class="service-list">
        <div class="service-item" onclick="showModal('book')">
          <div><div class="service-item-name">Standard Visit</div><div class="service-item-dur">Est. 1-2 hours</div></div>
          <div class="service-item-price">₹${p.price}</div>
        </div>
        <div class="service-item" onclick="showModal('book')">
          <div><div class="service-item-name">Emergency / Urgent</div><div class="service-item-dur">Same day, 2x rate</div></div>
          <div class="service-item-price">₹${p.price * 2}</div>
        </div>
        <div class="service-item" onclick="showModal('book')">
          <div><div class="service-item-name">Full Inspection</div><div class="service-item-dur">Est. 3-4 hours</div></div>
          <div class="service-item-price">₹${p.price * 3}</div>
        </div>
      </div>

      <div class="section-heading">About ${p.name}</div>
      <p style="color:var(--muted);font-size:14px;line-height:1.8;margin-bottom:28px;">
        Experienced ${p.role.toLowerCase()} with ${p.exp} of professional experience in the Delhi NCR region. Fully verified, background-checked, and rated by ${p.reviews}+ happy customers. I pride myself on punctuality, transparency, and quality work. Available in ${p.area} and nearby areas.
      </p>

      <div class="section-heading">Customer Reviews</div>
      <div class="review-list">
        <div class="review-item">
          <div class="review-header">
            <div style="display:flex;align-items:center;gap:10px;"><div class="author-avatar">👩</div><div><div class="review-name">Meera Jain</div><div style="color:#fbbf24;font-size:12px;">★★★★★</div></div></div>
            <div class="review-date">3 days ago</div>
          </div>
          <div class="review-text">Excellent work! Fixed the issue quickly and explained everything clearly. Highly professional.</div>
        </div>
        <div class="review-item">
          <div class="review-header">
            <div style="display:flex;align-items:center;gap:10px;"><div class="author-avatar">👨</div><div><div class="review-name">Rajesh Kumar</div><div style="color:#fbbf24;font-size:12px;">★★★★★</div></div></div>
            <div class="review-date">1 week ago</div>
          </div>
          <div class="review-text">Arrived on time, very clean work. Fair pricing. Will definitely call again for future needs.</div>
        </div>
        <div class="review-item">
          <div class="review-header">
            <div style="display:flex;align-items:center;gap:10px;"><div class="author-avatar">👩</div><div><div class="review-name">Sunita Aggarwal</div><div style="color:#fbbf24;font-size:12px;">★★★★☆</div></div></div>
            <div class="review-date">2 weeks ago</div>
          </div>
          <div class="review-text">Good service overall. Minor delay but called ahead to inform. Work quality was great.</div>
        </div>
      </div>
    </div>
    <div>
      <div class="table-card">
        <div class="table-header"><div class="table-title">Availability</div></div>
        <div style="padding:16px;">
          ${['Mon','Tue','Wed','Thu','Fri','Sat','Sun'].map((d,i) => `
            <div style="display:flex;justify-content:space-between;align-items:center;padding:8px 0;border-bottom:1px solid var(--border);last-child:border-none;">
              <span style="font-size:13px;color:${i===5||i===6?'var(--muted)':'var(--text)'}">${d}</span>
              <span style="font-size:12px;color:${i===5||i===6?'var(--muted)':'var(--green)'};">${i===5||i===6?'Unavailable':'9:00 AM – 7:00 PM'}</span>
            </div>
          `).join('')}
        </div>
      </div>
      <div class="table-card" style="margin-top:16px;">
        <div class="table-header"><div class="table-title">Location</div></div>
        <div style="padding:16px;">
          <div class="map-placeholder" style="height:160px;margin:0;">
            <div class="map-dots"></div>
            <div style="font-size:28px;position:relative;">📍</div>
            <div style="position:relative;font-size:13px;">${p.area}, Delhi</div>
          </div>
          <div style="margin-top:12px;font-size:13px;color:var(--muted);">Serves within 10km radius</div>
        </div>
      </div>
    </div>
  `;

  showPage('detail');
}

// ===================== PAGE NAVIGATION =====================
function showPage(name) {
  document.querySelectorAll('.page').forEach(p => p.classList.remove('active'));
  document.getElementById(`page-${name}`).classList.add('active');
  window.scrollTo(0, 0);
}

// ===================== MODAL =====================
function showModal(name) {
  document.getElementById(`modal-${name}`).classList.add('show');
}
function closeModal(name) {
  document.getElementById(`modal-${name}`).classList.remove('show');
}

document.querySelectorAll('.modal-overlay').forEach(overlay => {
  overlay.addEventListener('click', e => {
    if (e.target === overlay) overlay.classList.remove('show');
  });
});

// ===================== TOAST =====================
let toastTimer;
function showToast(msg) {
  const toast = document.getElementById('toast');
  document.getElementById('toast-msg').textContent = msg;
  toast.classList.add('show');
  clearTimeout(toastTimer);
  toastTimer = setTimeout(() => toast.classList.remove('show'), 3000);
}

// ===================== FILTERS =====================
function toggleChip(el) {
  el.classList.toggle('active');
}

function updatePriceLabel(val) {
  document.getElementById('price-label').textContent = `Up to ₹${Number(val).toLocaleString('en-IN')}`;
}

function updateDistLabel(val) {
  document.getElementById('dist-label').textContent = `Within ${val} km`;
}

function filterByCategory(cat) {
  showPage('browse');
  showToast(`🔍 Filtering by: ${cat}`);
}

// ===================== SEARCH =====================
function doSearch() {
  const val = document.getElementById('hero-search').value;
  showPage('browse');
  if (val) showToast(`🔍 Searching for: ${val}`);
}

// ===================== POST JOB =====================
function postStep(n) {
  [1,2,3].forEach(i => {
    document.getElementById(`post-step${i}`).style.display = i === n ? 'block' : 'none';
    document.getElementById(`step${i}-dot`).classList.toggle('active', i <= n);
  });
  window.scrollTo(0, 0);
}

function submitJob() {
  showPage('home');
  setTimeout(() => showToast('🎉 Job posted! You\'ll receive quotes soon.'), 300);
}

// ===================== BOOKING =====================
function confirmBooking() {
  closeModal('book');
  showToast('✅ Booking confirmed! Check your dashboard for details.');
}

// ===================== INIT =====================
renderCategories();
renderProviders('home-providers', providers.slice(0, 4));
renderProviders('browse-providers', providers);

// Nav toggle for mobile
document.querySelectorAll('.toggle-btn').forEach(btn => {
  btn.addEventListener('click', function() {
    this.closest('.toggle-group').querySelectorAll('.toggle-btn').forEach(b => b.classList.remove('active'));
    this.classList.add('active');
  });
});

// Dash nav
document.querySelectorAll('.dash-nav-item').forEach(item => {
  item.addEventListener('click', function() {
    document.querySelectorAll('.dash-nav-item').forEach(i => i.classList.remove('active'));
    this.classList.add('active');
  });
});
</script>
</body>
</html>
