<!DOCTYPE html>
<html lang="fr">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Mathieu Arakelian — Portfolio</title>
  <style>
    @import url('https://fonts.googleapis.com/css2?family=Syne:wght@400;600;700;800&family=Inter:wght@300;400;500;600&display=swap');

    *,
    *::before,
    *::after {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    :root {
      --blue: #5e9bff;
      --green: #4ecb71;
      --yellow: #ffc107;
      --purple: #c77dff;
      --orange: #ff9f43;
      --red: #ff6b6b;
      --bg: #000;
      --surface: #111;
      --surface2: #1a1a1a;
      --border: rgba(255, 255, 255, 0.07);
      --text: #f5f5f7;
      --muted: #a1a1a6;
      --dim: #555;
    }

    html {
      scroll-behavior: smooth;
      scroll-padding-top: 56px;
    }

    body {
      font-family: 'Inter', sans-serif;
      background: var(--bg);
      color: var(--text);
      overflow-x: hidden;
      cursor: none;
    }

    /* ── CURSOR ── */
    .cursor {
      position: fixed;
      pointer-events: none;
      z-index: 9999;
      mix-blend-mode: difference;
    }

    .cursor-dot {
      width: 8px;
      height: 8px;
      background: #fff;
      border-radius: 50%;
      transform: translate(-50%, -50%);
      transition: transform 0.1s;
    }

    .cursor-ring {
      width: 36px;
      height: 36px;
      border: 1.5px solid rgba(255, 255, 255, 0.5);
      border-radius: 50%;
      transform: translate(-50%, -50%);
      transition: width 0.25s, height 0.25s, border-color 0.25s, transform 0.08s;
    }

    body:has(a:hover) .cursor-ring,
    body:has(button:hover) .cursor-ring {
      width: 54px;
      height: 54px;
      border-color: rgba(255, 255, 255, 0.9);
    }

    /* ── NAV ── */
    nav {
      position: fixed;
      top: 0;
      width: 100%;
      z-index: 1000;
      background: rgba(0, 0, 0, 0.7);
      backdrop-filter: saturate(180%) blur(24px);
      border-bottom: 1px solid var(--border);
      transition: background 0.3s;
    }

    .nav-inner {
      max-width: 1200px;
      margin: 0 auto;
      padding: 0 32px;
      height: 56px;
      display: flex;
      align-items: center;
      justify-content: space-between;
    }

    .nav-logo {
      font-family: 'Syne', sans-serif;
      font-weight: 800;
      font-size: 18px;
      letter-spacing: -0.5px;
      text-decoration: none;
      color: var(--text);
    }

    .nav-links {
      display: flex;
      gap: 4px;
      list-style: none;
    }

    .nav-links a {
      color: var(--muted);
      text-decoration: none;
      font-size: 13px;
      font-weight: 500;
      padding: 6px 14px;
      border-radius: 20px;
      transition: color 0.2s, background 0.2s;
    }

    .nav-links a:hover,
    .nav-links a.active {
      color: var(--text);
      background: rgba(255, 255, 255, 0.08);
    }

    /* ── HERO ── */
    #accueil {
      min-height: 100vh;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      padding: 80px 32px 60px;
      position: relative;
      overflow: hidden;
      text-align: center;
    }

    .hero-bg {
      position: absolute;
      inset: 0;
      pointer-events: none;
      background: radial-gradient(ellipse 70% 50% at 50% 30%, rgba(94, 155, 255, 0.08) 0%, transparent 70%);
    }

    .hero-grid {
      position: absolute;
      inset: 0;
      pointer-events: none;
      opacity: 0.04;
      background-image: linear-gradient(rgba(255, 255, 255, 0.5) 1px, transparent 1px), linear-gradient(90deg, rgba(255, 255, 255, 0.5) 1px, transparent 1px);
      background-size: 60px 60px;
      mask-image: radial-gradient(ellipse 80% 80% at 50% 50%, black 0%, transparent 100%);
    }

    .hero-eyebrow {
      display: inline-flex;
      align-items: center;
      gap: 8px;
      background: rgba(94, 155, 255, 0.08);
      border: 1px solid rgba(94, 155, 255, 0.2);
      border-radius: 20px;
      padding: 6px 16px;
      font-size: 12px;
      color: var(--blue);
      font-weight: 600;
      text-transform: uppercase;
      letter-spacing: 1.5px;
      margin-bottom: 28px;
      opacity: 0;
      animation: fadeUp 0.8s 0.2s forwards;
    }

    .hero-eyebrow::before {
      content: '';
      width: 6px;
      height: 6px;
      background: var(--blue);
      border-radius: 50%;
      animation: pulse 2s infinite;
    }

    @keyframes pulse {

      0%,
      100% {
        opacity: 1;
        transform: scale(1);
      }

      50% {
        opacity: 0.4;
        transform: scale(0.7);
      }
    }

    .hero-title {
      font-family: 'Syne', sans-serif;
      font-size: clamp(56px, 8vw, 110px);
      font-weight: 800;
      letter-spacing: -4px;
      line-height: 0.95;
      background: linear-gradient(160deg, #fff 30%, #666 100%);
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
      background-clip: text;
      margin-bottom: 24px;
      opacity: 0;
      animation: fadeUp 0.9s 0.35s forwards;
    }

    .hero-subtitle {
      font-size: clamp(16px, 2.5vw, 22px);
      color: var(--muted);
      font-weight: 400;
      margin-bottom: 48px;
      max-width: 480px;
      opacity: 0;
      animation: fadeUp 0.8s 0.5s forwards;
    }

    .hero-actions {
      display: flex;
      gap: 12px;
      justify-content: center;
      flex-wrap: wrap;
      opacity: 0;
      animation: fadeUp 0.8s 0.65s forwards;
    }

    .btn-primary {
      display: inline-flex;
      align-items: center;
      gap: 8px;
      background: var(--blue);
      color: #fff;
      text-decoration: none;
      padding: 13px 26px;
      border-radius: 980px;
      font-size: 15px;
      font-weight: 600;
      transition: transform 0.2s, box-shadow 0.2s, background 0.2s;
    }

    .btn-primary:hover {
      transform: translateY(-2px);
      box-shadow: 0 12px 32px rgba(94, 155, 255, 0.35);
      background: #4d8aee;
    }

    .btn-ghost {
      display: inline-flex;
      align-items: center;
      gap: 8px;
      background: transparent;
      color: var(--text);
      text-decoration: none;
      padding: 13px 26px;
      border-radius: 980px;
      font-size: 15px;
      font-weight: 500;
      border: 1px solid rgba(255, 255, 255, 0.15);
      transition: transform 0.2s, background 0.2s, border-color 0.2s;
    }

    .btn-ghost:hover {
      transform: translateY(-2px);
      background: rgba(255, 255, 255, 0.06);
      border-color: rgba(255, 255, 255, 0.3);
    }

    .hero-scroll {
      position: absolute;
      bottom: 36px;
      left: 50%;
      transform: translateX(-50%);
      display: flex;
      flex-direction: column;
      align-items: center;
      gap: 8px;
      opacity: 0;
      animation: fadeUp 0.8s 1s forwards;
    }

    .hero-scroll span {
      font-size: 11px;
      color: var(--dim);
      text-transform: uppercase;
      letter-spacing: 2px;
      font-weight: 600;
    }

    .scroll-line {
      width: 1px;
      height: 40px;
      background: linear-gradient(to bottom, rgba(255, 255, 255, 0.3), transparent);
      animation: scrollLine 2s ease-in-out infinite;
    }

    @keyframes scrollLine {

      0%,
      100% {
        transform: scaleY(1);
        opacity: 0.4;
      }

      50% {
        transform: scaleY(1.5);
        opacity: 1;
      }
    }

    /* ── SECTION WRAPPER ── */
    .section-wrap {
      max-width: 1200px;
      margin: 0 auto;
      padding: 100px 32px;
    }

    .section-label {
      font-size: 11px;
      text-transform: uppercase;
      letter-spacing: 2px;
      color: var(--blue);
      font-weight: 700;
      margin-bottom: 12px;
      opacity: 0;
      transform: translateY(20px);
      transition: opacity 0.6s, transform 0.6s;
    }

    .section-title {
      font-family: 'Syne', sans-serif;
      font-size: clamp(36px, 5vw, 64px);
      font-weight: 800;
      letter-spacing: -2px;
      margin-bottom: 60px;
      color: var(--text);
      opacity: 0;
      transform: translateY(20px);
      transition: opacity 0.6s 0.1s, transform 0.6s 0.1s;
    }

    .in-view .section-label,
    .in-view .section-title {
      opacity: 1;
      transform: none;
    }

    /* ── PROJECTS ── */
    #projets {
      background: #000;
    }

    .projects-grid {
      display: grid;
      grid-template-columns: repeat(2, 1fr);
      gap: 20px;
    }

    .project-card {
      background: var(--surface);
      border-radius: 20px;
      overflow: hidden;
      border: 1px solid var(--border);
      display: flex;
      flex-direction: column;
      transition: transform 0.35s cubic-bezier(0.34, 1.56, 0.64, 1), box-shadow 0.35s;
      opacity: 0;
      transform: translateY(30px);
    }

    .project-card.in-view {
      opacity: 1;
      transform: none;
    }

    .project-card:hover {
      transform: translateY(-8px) scale(1.01);
      box-shadow: 0 24px 60px rgba(0, 0, 0, 0.6);
    }

    .card-header {
      padding: 32px 28px 24px;
      position: relative;
      overflow: hidden;
    }

    .card-glow {
      position: absolute;
      inset: 0;
      opacity: 0;
      transition: opacity 0.4s;
      pointer-events: none;
    }

    .project-card:hover .card-glow {
      opacity: 1;
    }

    .glow-blue {
      background: radial-gradient(ellipse 80% 60% at 30% 0%, rgba(94, 155, 255, 0.12) 0%, transparent 70%);
    }

    .glow-green {
      background: radial-gradient(ellipse 80% 60% at 30% 0%, rgba(78, 203, 113, 0.1) 0%, transparent 70%);
    }

    .glow-yellow {
      background: radial-gradient(ellipse 80% 60% at 30% 0%, rgba(255, 193, 7, 0.1) 0%, transparent 70%);
    }

    .glow-purple {
      background: radial-gradient(ellipse 80% 60% at 30% 0%, rgba(199, 125, 255, 0.1) 0%, transparent 70%);
    }

    .proj-badge {
      display: inline-flex;
      align-items: center;
      gap: 6px;
      font-size: 11px;
      font-weight: 700;
      text-transform: uppercase;
      letter-spacing: 1px;
      padding: 5px 12px;
      border-radius: 20px;
      margin-bottom: 16px;
      width: fit-content;
    }

    .b-blue {
      background: rgba(94, 155, 255, 0.12);
      color: var(--blue);
      border: 1px solid rgba(94, 155, 255, 0.25);
    }

    .b-green {
      background: rgba(78, 203, 113, 0.1);
      color: var(--green);
      border: 1px solid rgba(78, 203, 113, 0.25);
    }

    .b-yellow {
      background: rgba(255, 193, 7, 0.1);
      color: var(--yellow);
      border: 1px solid rgba(255, 193, 7, 0.25);
    }

    .b-purple {
      background: rgba(199, 125, 255, 0.1);
      color: var(--purple);
      border: 1px solid rgba(199, 125, 255, 0.25);
    }

    .card-header h3 {
      font-family: 'Syne', sans-serif;
      font-size: 22px;
      font-weight: 700;
      letter-spacing: -0.3px;
      margin-bottom: 10px;
    }

    .card-header p {
      font-size: 14px;
      color: var(--muted);
      line-height: 1.65;
    }

    .card-tools {
      padding: 18px 28px;
      border-top: 1px solid var(--border);
      display: flex;
      flex-wrap: wrap;
      gap: 6px;
    }

    .tool-chip {
      background: rgba(255, 255, 255, 0.04);
      border: 1px solid rgba(255, 255, 255, 0.08);
      border-radius: 8px;
      padding: 5px 10px;
      font-size: 11px;
      color: var(--muted);
      font-weight: 500;
      transition: background 0.2s, color 0.2s;
    }

    .project-card:hover .tool-chip {
      background: rgba(255, 255, 255, 0.07);
      color: var(--text);
    }

    .card-stats {
      display: flex;
      border-top: 1px solid var(--border);
    }

    .stat {
      flex: 1;
      padding: 14px 10px;
      text-align: center;
      border-right: 1px solid var(--border);
    }

    .stat:last-child {
      border-right: none;
    }

    .stat-val {
      font-size: 15px;
      font-weight: 700;
      font-family: 'Syne', sans-serif;
    }

    .stat-key {
      font-size: 10px;
      color: var(--dim);
      margin-top: 2px;
      text-transform: uppercase;
      letter-spacing: 0.5px;
    }

    .card-footer {
      padding: 16px 28px;
      border-top: 1px solid var(--border);
      margin-top: auto;
    }

    .proj-link {
      display: flex;
      align-items: center;
      justify-content: center;
      gap: 8px;
      background: rgba(255, 255, 255, 0.06);
      color: var(--text);
      text-decoration: none;
      border-radius: 12px;
      padding: 11px;
      font-size: 13px;
      font-weight: 600;
      border: 1px solid rgba(255, 255, 255, 0.1);
      transition: background 0.2s, border-color 0.2s, gap 0.2s;
    }

    .proj-link:hover {
      background: rgba(255, 255, 255, 0.1);
      border-color: rgba(255, 255, 255, 0.2);
      gap: 12px;
    }

    .proj-link svg {
      width: 14px;
      height: 14px;
      flex-shrink: 0;
    }

    /* ── STAGE ── */
    #stage {
      background: #050505;
    }

    .stage-block {
      display: grid;
      grid-template-columns: 1fr 1fr;
      border-radius: 24px;
      overflow: hidden;
      border: 1px solid var(--border);
      margin-bottom: 32px;
      opacity: 0;
      transform: translateY(40px);
      transition: opacity 0.7s, transform 0.7s;
    }

    .stage-block.in-view {
      opacity: 1;
      transform: none;
    }

    .stage-left {
      padding: 44px 48px;
      background: var(--surface);
      display: flex;
      flex-direction: column;
      gap: 36px;
    }

    .stage-badge {
      display: inline-flex;
      align-items: center;
      gap: 8px;
      font-size: 11px;
      font-weight: 700;
      text-transform: uppercase;
      letter-spacing: 1.5px;
      padding: 7px 16px;
      border-radius: 20px;
      width: fit-content;
    }

    .sb-blue {
      background: rgba(94, 155, 255, 0.1);
      color: var(--blue);
      border: 1px solid rgba(94, 155, 255, 0.25);
    }

    .sb-green {
      background: rgba(78, 203, 113, 0.1);
      color: var(--green);
      border: 1px solid rgba(78, 203, 113, 0.25);
    }

    .stage-left h3 {
      font-family: 'Syne', sans-serif;
      font-size: 30px;
      font-weight: 800;
      letter-spacing: -0.5px;
      margin-bottom: 6px;
    }

    .stage-period {
      font-size: 13px;
      color: var(--muted);
      margin-bottom: 14px;
    }

    .stage-desc {
      font-size: 15px;
      color: var(--muted);
      line-height: 1.7;
    }

    .activity-list {
      display: flex;
      flex-direction: column;
      gap: 0;
    }

    .act-label {
      font-size: 10px;
      text-transform: uppercase;
      letter-spacing: 1.5px;
      color: var(--dim);
      font-weight: 700;
      margin-bottom: 18px;
    }

    .act-item {
      display: flex;
      gap: 16px;
      padding-bottom: 22px;
      position: relative;
    }

    .act-item:last-child {
      padding-bottom: 0;
    }

    .act-item:not(:last-child)::before {
      content: '';
      position: absolute;
      left: 10px;
      top: 24px;
      bottom: 0;
      width: 1px;
      background: var(--border);
    }

    .act-dot {
      flex-shrink: 0;
      width: 22px;
      height: 22px;
      border-radius: 50%;
      border: 2px solid;
      display: flex;
      align-items: center;
      justify-content: center;
      margin-top: 2px;
    }

    .dot-b {
      border-color: var(--blue);
      background: rgba(94, 155, 255, 0.1);
    }

    .dot-g {
      border-color: var(--green);
      background: rgba(78, 203, 113, 0.1);
    }

    .act-dot svg {
      width: 9px;
      height: 9px;
      fill: none;
      stroke-width: 2.5;
      stroke-linecap: round;
    }

    .dot-b svg {
      stroke: var(--blue);
    }

    .dot-g svg {
      stroke: var(--green);
    }

    .act-body strong {
      font-size: 14px;
      font-weight: 600;
      display: block;
      margin-bottom: 2px;
    }

    .act-body span {
      font-size: 12px;
      color: var(--muted);
      line-height: 1.5;
    }

    .stage-right {
      background: #0d0d0d;
      border-left: 1px solid var(--border);
      display: flex;
      flex-direction: column;
    }

    .stage-photo {
      width: 100%;
      height: 220px;
      overflow: hidden;
      position: relative;
      flex-shrink: 0;
    }

    .stage-photo img {
      width: 100%;
      height: 100%;
      object-fit: cover;
      display: block;
      transition: transform 0.6s ease;
    }

    .stage-block:hover .stage-photo img {
      transform: scale(1.04);
    }

    .photo-caption {
      position: absolute;
      bottom: 0;
      left: 0;
      right: 0;
      padding: 14px 20px;
      background: linear-gradient(transparent, rgba(0, 0, 0, 0.75));
      font-size: 13px;
      font-weight: 500;
    }

    .tools-grid-wrap {
      padding: 26px 28px;
      flex: 1;
    }

    .tools-lbl {
      font-size: 10px;
      text-transform: uppercase;
      letter-spacing: 1.5px;
      color: var(--dim);
      font-weight: 700;
      margin-bottom: 16px;
    }

    .tools-grid {
      display: grid;
      grid-template-columns: repeat(3, 1fr);
      gap: 8px;
    }

    .tool-pill {
      display: flex;
      flex-direction: column;
      align-items: center;
      gap: 8px;
      background: rgba(255, 255, 255, 0.03);
      border: 1px solid var(--border);
      border-radius: 12px;
      padding: 14px 8px 12px;
      transition: background 0.2s, transform 0.2s;
    }

    .tool-pill:hover {
      background: rgba(255, 255, 255, 0.07);
      transform: translateY(-2px);
    }

    .tool-icon {
      width: 34px;
      height: 34px;
      border-radius: 8px;
      display: flex;
      align-items: center;
      justify-content: center;
      font-size: 18px;
    }

    .tool-pill span {
      font-size: 10px;
      color: var(--muted);
      text-align: center;
      font-weight: 500;
      line-height: 1.3;
    }

    .ic-b {
      background: rgba(94, 155, 255, 0.1);
    }

    .ic-g {
      background: rgba(78, 203, 113, 0.1);
    }

    .ic-o {
      background: rgba(255, 159, 67, 0.1);
    }

    .ic-p {
      background: rgba(199, 125, 255, 0.1);
    }

    .ic-y {
      background: rgba(255, 193, 7, 0.1);
    }

    .ic-t {
      background: rgba(0, 199, 190, 0.1);
    }

    .ic-x {
      background: rgba(255, 255, 255, 0.05);
    }

    .stage-nums {
      display: flex;
      border-top: 1px solid var(--border);
    }

    .stage-num {
      flex: 1;
      padding: 16px;
      text-align: center;
      border-right: 1px solid var(--border);
    }

    .stage-num:last-child {
      border-right: none;
    }

    .sn-val {
      font-family: 'Syne', sans-serif;
      font-size: 20px;
      font-weight: 700;
    }

    .sn-key {
      font-size: 10px;
      color: var(--dim);
      margin-top: 2px;
      text-transform: uppercase;
      letter-spacing: 0.5px;
    }

    /* ── STAGE BUTTONS ── */
    .stage-btn-row {
      display: flex;
      gap: 10px;
      flex-wrap: wrap;
      margin-top: 4px;
    }

    .btn-stage {
      display: inline-flex;
      align-items: center;
      gap: 8px;
      border-radius: 980px;
      padding: 10px 20px;
      font-size: 13px;
      font-weight: 600;
      text-decoration: none;
      cursor: pointer;
      border: none;
      font-family: 'Inter', sans-serif;
      transition: transform 0.2s, box-shadow 0.2s, background 0.2s, gap 0.2s;
    }

    .btn-stage-blue {
      background: rgba(94, 155, 255, 0.12);
      color: var(--blue);
      border: 1px solid rgba(94, 155, 255, 0.3);
    }

    .btn-stage-blue:hover {
      background: rgba(94, 155, 255, 0.22);
      transform: translateY(-2px);
      box-shadow: 0 8px 24px rgba(94, 155, 255, 0.2);
      gap: 12px;
    }

    .btn-stage-green {
      background: rgba(78, 203, 113, 0.1);
      color: var(--green);
      border: 1px solid rgba(78, 203, 113, 0.3);
    }

    .btn-stage-green:hover {
      background: rgba(78, 203, 113, 0.2);
      transform: translateY(-2px);
      box-shadow: 0 8px 24px rgba(78, 203, 113, 0.2);
      gap: 12px;
    }

    .btn-stage svg {
      width: 14px;
      height: 14px;
      flex-shrink: 0;
    }

    /* ── GALLERY MODAL ── */
    .gallery-overlay {
      position: fixed;
      inset: 0;
      z-index: 10000;
      background: rgba(0, 0, 0, 0.88);
      backdrop-filter: blur(24px) saturate(120%);
      display: flex;
      align-items: center;
      justify-content: center;
      padding: 24px;
      opacity: 0;
      pointer-events: none;
      transition: opacity 0.3s;
    }

    .gallery-overlay.open {
      opacity: 1;
      pointer-events: all;
    }

    .gallery-modal {
      background: #111;
      border: 1px solid rgba(255, 255, 255, 0.1);
      border-radius: 24px;
      max-width: 860px;
      width: 100%;
      max-height: 90vh;
      overflow-y: auto;
      scrollbar-width: thin;
      scrollbar-color: rgba(255, 255, 255, 0.1) transparent;
      transform: translateY(20px) scale(0.97);
      transition: transform 0.38s cubic-bezier(0.34, 1.56, 0.64, 1);
      box-shadow: 0 40px 100px rgba(0, 0, 0, 0.7);
    }

    .gallery-overlay.open .gallery-modal {
      transform: none;
    }

    .gallery-modal-header {
      display: flex;
      align-items: center;
      justify-content: space-between;
      padding: 22px 28px;
      border-bottom: 1px solid rgba(255, 255, 255, 0.07);
      position: sticky;
      top: 0;
      background: rgba(17, 17, 17, 0.97);
      backdrop-filter: blur(12px);
      z-index: 2;
      border-radius: 24px 24px 0 0;
    }

    .gallery-modal-title {
      font-family: 'Syne', sans-serif;
      font-size: 20px;
      font-weight: 700;
      letter-spacing: -0.3px;
      display: flex;
      align-items: center;
      gap: 10px;
    }

    .gallery-modal-title .title-badge {
      font-family: 'Inter', sans-serif;
      font-size: 11px;
      font-weight: 700;
      text-transform: uppercase;
      letter-spacing: 1.2px;
      background: rgba(94, 155, 255, 0.1);
      color: var(--blue);
      border: 1px solid rgba(94, 155, 255, 0.25);
      border-radius: 20px;
      padding: 3px 10px;
    }

    .gallery-close {
      width: 36px;
      height: 36px;
      border-radius: 50%;
      background: rgba(255, 255, 255, 0.06);
      border: 1px solid rgba(255, 255, 255, 0.1);
      cursor: pointer;
      display: flex;
      align-items: center;
      justify-content: center;
      color: var(--muted);
      font-size: 20px;
      line-height: 1;
      transition: background 0.2s, color 0.2s, transform 0.2s;
    }

    .gallery-close:hover {
      background: rgba(255, 255, 255, 0.12);
      color: var(--text);
      transform: rotate(90deg);
    }

    .gallery-grid {
      display: flex;
      flex-direction: column;
      gap: 16px;
      padding: 24px 28px 32px;
    }

    .gallery-item {
      border-radius: 16px;
      overflow: hidden;
      border: 1px solid rgba(255, 255, 255, 0.07);
      transition: border-color 0.3s, box-shadow 0.3s;
    }

    .gallery-item:hover {
      border-color: rgba(94, 155, 255, 0.2);
      box-shadow: 0 8px 32px rgba(0, 0, 0, 0.5);
    }

    .gallery-img-wrap {
      width: 100%;
      aspect-ratio: 16/9;
      background: #1a1a1a;
      display: flex;
      align-items: center;
      justify-content: center;
      overflow: hidden;
      position: relative;
    }

    .gallery-img-wrap img {
      width: 100%;
      height: 100%;
      object-fit: cover;
      display: block;
      transition: transform 0.5s ease;
    }

    .gallery-item:hover .gallery-img-wrap img {
      transform: scale(1.03);
    }

    /* Placeholder when no image */
    .gallery-placeholder {
      display: flex;
      flex-direction: column;
      align-items: center;
      gap: 14px;
      color: var(--dim);
      text-align: center;
      padding: 40px 20px;
    }

    .gallery-placeholder svg {
      opacity: 0.3;
    }

    .gallery-placeholder p {
      font-size: 13px;
      line-height: 1.6;
      max-width: 260px;
    }

    .gallery-placeholder strong {
      color: var(--muted);
      font-size: 14px;
    }

    .gallery-caption {
      padding: 14px 20px;
      background: #0d0d0d;
      border-top: 1px solid rgba(255, 255, 255, 0.05);
      display: flex;
      align-items: center;
      gap: 10px;
    }

    .gallery-caption-num {
      width: 26px;
      height: 26px;
      border-radius: 8px;
      flex-shrink: 0;
      background: rgba(94, 155, 255, 0.1);
      border: 1px solid rgba(94, 155, 255, 0.2);
      display: flex;
      align-items: center;
      justify-content: center;
      font-family: 'Syne', sans-serif;
      font-size: 12px;
      font-weight: 700;
      color: var(--blue);
    }

    .gallery-caption-text strong {
      font-size: 13px;
      font-weight: 600;
      display: block;
      margin-bottom: 2px;
    }

    .gallery-caption-text span {
      font-size: 11px;
      color: var(--muted);
    }

    /* ── VEILLE ── */
    #veille {
      background: #000;
    }

    .veille-grid {
      display: flex;
      flex-direction: column;
      gap: 28px;
      max-width: 900px;
      margin: 0 auto;
    }

    .veille-card {
      border-radius: 20px;
      overflow: hidden;
      border: 1px solid var(--border);
      opacity: 0;
      transform: translateY(30px);
      transition: opacity 0.7s, transform 0.7s;
    }

    .veille-card.in-view {
      opacity: 1;
      transform: none;
    }

    .veille-card:nth-child(2) {
      transition-delay: 0.15s;
    }

    .vc-header {
      padding: 28px 32px 24px;
      border-bottom: 1px solid var(--border);
      display: flex;
      gap: 18px;
      align-items: flex-start;
    }

    .vc-icon {
      width: 44px;
      height: 44px;
      border-radius: 12px;
      display: flex;
      align-items: center;
      justify-content: center;
      font-size: 22px;
      flex-shrink: 0;
    }

    .vc-meta {
      flex: 1;
    }

    .vc-kicker {
      font-size: 11px;
      text-transform: uppercase;
      letter-spacing: 1.5px;
      font-weight: 700;
      margin-bottom: 6px;
    }

    .vc-title {
      font-family: 'Syne', sans-serif;
      font-size: 22px;
      font-weight: 700;
      letter-spacing: -0.3px;
      margin-bottom: 12px;
    }

    .vc-tags {
      display: flex;
      flex-wrap: wrap;
      gap: 6px;
    }

    .vc-tag {
      font-size: 11px;
      font-weight: 600;
      padding: 4px 12px;
      border-radius: 20px;
    }

    .vc-body {
      padding: 28px 32px;
    }

    .vc-body p {
      font-size: 15px;
      color: #c8c8cc;
      line-height: 1.75;
      margin-bottom: 20px;
    }

    .vc-body p:last-of-type {
      margin-bottom: 24px;
    }

    .vc-metrics {
      display: grid;
      grid-template-columns: repeat(3, 1fr);
      gap: 10px;
      margin-bottom: 24px;
    }

    .metric {
      border-radius: 12px;
      padding: 16px;
      text-align: center;
      border: 1px solid;
      transition: transform 0.2s;
    }

    .metric:hover {
      transform: translateY(-2px);
    }

    .metric-val {
      font-family: 'Syne', sans-serif;
      font-size: 24px;
      font-weight: 700;
      letter-spacing: -1px;
    }

    .metric-lbl {
      font-size: 11px;
      color: var(--muted);
      margin-top: 4px;
    }

    .vc-timeline {
      background: rgba(255, 255, 255, 0.025);
      border: 1px solid var(--border);
      border-radius: 12px;
      padding: 18px 22px;
      margin-bottom: 24px;
    }

    .vc-tl-label {
      font-size: 10px;
      text-transform: uppercase;
      letter-spacing: 1.5px;
      color: var(--dim);
      font-weight: 700;
      margin-bottom: 14px;
    }

    .tl-row {
      display: flex;
      gap: 16px;
      align-items: flex-start;
      padding: 5px 0;
    }

    .tl-date {
      width: 72px;
      flex-shrink: 0;
      font-size: 12px;
      font-weight: 700;
    }

    .tl-text {
      font-size: 13px;
      color: var(--muted);
      line-height: 1.5;
    }

    .vc-footer {
      display: flex;
      align-items: center;
      justify-content: space-between;
      padding-top: 18px;
      border-top: 1px solid var(--border);
    }

    .vc-source {
      font-size: 12px;
      color: var(--dim);
    }

    .vc-link {
      display: inline-flex;
      align-items: center;
      gap: 6px;
      background: #0071e3;
      color: #fff;
      text-decoration: none;
      padding: 8px 16px;
      border-radius: 980px;
      font-size: 12px;
      font-weight: 600;
      transition: background 0.2s, gap 0.2s;
    }

    .vc-link:hover {
      background: #0077ed;
      gap: 8px;
    }

    .vc-link svg {
      width: 11px;
      height: 11px;
      stroke: currentColor;
      fill: none;
      stroke-width: 2.5;
      stroke-linecap: round;
    }

    /* ── BIO ── */
    #bio {
      background: #050505;
    }

    .bio-hero {
      display: grid;
      grid-template-columns: auto 1fr;
      gap: 40px;
      align-items: center;
      background: var(--surface);
      border: 1px solid var(--border);
      border-radius: 24px;
      padding: 40px 44px;
      margin-bottom: 24px;
      opacity: 0;
      transform: translateY(30px);
      transition: opacity 0.7s, transform 0.7s;
    }

    .bio-hero.in-view {
      opacity: 1;
      transform: none;
    }

    .bio-avatar {
      width: 100px;
      height: 100px;
      border-radius: 50%;
      flex-shrink: 0;
      background: linear-gradient(135deg, #667eea, #764ba2);
      display: flex;
      align-items: center;
      justify-content: center;
      font-family: 'Syne', sans-serif;
      font-size: 40px;
      font-weight: 800;
      color: #fff;
      position: relative;
    }

    .bio-avatar::after {
      content: '';
      position: absolute;
      inset: -4px;
      border-radius: 50%;
      border: 1px solid rgba(102, 126, 234, 0.3);
    }

    .bio-name {
      font-family: 'Syne', sans-serif;
      font-size: 30px;
      font-weight: 800;
      letter-spacing: -0.5px;
      margin-bottom: 4px;
    }

    .bio-role {
      font-size: 15px;
      color: var(--blue);
      font-weight: 600;
      margin-bottom: 14px;
    }

    .bio-desc {
      font-size: 14px;
      color: var(--muted);
      line-height: 1.7;
      margin-bottom: 18px;
      max-width: 560px;
    }

    .bio-tags {
      display: flex;
      flex-wrap: wrap;
      gap: 8px;
    }

    .bio-tag {
      font-size: 12px;
      font-weight: 600;
      padding: 5px 14px;
      border-radius: 20px;
      border: 1px solid;
    }

    .bt-blue {
      background: rgba(94, 155, 255, 0.08);
      color: var(--blue);
      border-color: rgba(94, 155, 255, 0.25);
    }

    .bt-green {
      background: rgba(78, 203, 113, 0.08);
      color: var(--green);
      border-color: rgba(78, 203, 113, 0.25);
    }

    .bt-gray {
      background: rgba(255, 255, 255, 0.04);
      color: var(--muted);
      border-color: rgba(255, 255, 255, 0.12);
    }

    .bio-stats-row {
      display: grid;
      grid-template-columns: repeat(4, 1fr);
      gap: 12px;
      margin-bottom: 24px;
      opacity: 0;
      transform: translateY(20px);
      transition: opacity 0.6s 0.1s, transform 0.6s 0.1s;
    }

    .bio-stats-row.in-view {
      opacity: 1;
      transform: none;
    }

    .bio-stat {
      background: var(--surface);
      border: 1px solid var(--border);
      border-radius: 12px;
      padding: 18px;
      text-align: center;
      transition: transform 0.2s, border-color 0.2s;
    }

    .bio-stat:hover {
      transform: translateY(-3px);
      border-color: rgba(255, 255, 255, 0.15);
    }

    .bs-val {
      font-family: 'Syne', sans-serif;
      font-size: 24px;
      font-weight: 700;
      margin-bottom: 4px;
    }

    .bs-key {
      font-size: 10px;
      color: var(--dim);
      text-transform: uppercase;
      letter-spacing: 1px;
      font-weight: 600;
    }

    .bio-grid {
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 20px;
      margin-bottom: 24px;
    }

    .bio-panel {
      background: var(--surface);
      border: 1px solid var(--border);
      border-radius: 18px;
      padding: 28px;
      opacity: 0;
      transform: translateY(20px);
      transition: opacity 0.6s, transform 0.6s;
    }

    .bio-panel.in-view {
      opacity: 1;
      transform: none;
    }

    .bio-panel:nth-child(2) {
      transition-delay: 0.1s;
    }

    .panel-label {
      font-size: 10px;
      text-transform: uppercase;
      letter-spacing: 1.5px;
      color: var(--dim);
      font-weight: 700;
      margin-bottom: 20px;
    }

    .timeline-item {
      display: flex;
      gap: 16px;
      padding-bottom: 22px;
      position: relative;
    }

    .timeline-item:last-child {
      padding-bottom: 0;
    }

    .timeline-item:not(:last-child)::before {
      content: '';
      position: absolute;
      left: 10px;
      top: 24px;
      bottom: 0;
      width: 1px;
      background: var(--border);
    }

    .tl-dot {
      width: 22px;
      height: 22px;
      border-radius: 50%;
      flex-shrink: 0;
      margin-top: 2px;
    }

    .tl-dot-empty {
      border: 2px solid var(--blue);
      background: rgba(94, 155, 255, 0.08);
    }

    .tl-dot-full {
      background: var(--blue);
      border: 2px solid var(--blue);
    }

    .tl-year {
      font-size: 11px;
      color: var(--blue);
      font-weight: 700;
      margin-bottom: 4px;
    }

    .tl-title {
      font-size: 14px;
      font-weight: 600;
      margin-bottom: 2px;
    }

    .tl-sub {
      font-size: 12px;
      color: var(--muted);
      line-height: 1.5;
    }

    .info-row {
      display: flex;
      gap: 12px;
      align-items: flex-start;
      padding: 10px 0;
      border-bottom: 1px solid var(--border);
    }

    .info-row:first-child {
      padding-top: 0;
    }

    .info-row:last-child {
      border-bottom: none;
    }

    .info-icon {
      width: 30px;
      height: 30px;
      border-radius: 8px;
      background: rgba(94, 155, 255, 0.06);
      border: 1px solid rgba(94, 155, 255, 0.18);
      display: flex;
      align-items: center;
      justify-content: center;
      font-size: 14px;
      flex-shrink: 0;
      margin-top: 2px;
    }

    .info-key {
      font-size: 10px;
      color: var(--dim);
      text-transform: uppercase;
      letter-spacing: 0.8px;
      font-weight: 700;
      margin-bottom: 3px;
    }

    .info-val {
      font-size: 13px;
    }

    .skills-panel {
      background: var(--surface);
      border: 1px solid var(--border);
      border-radius: 18px;
      padding: 28px;
      opacity: 0;
      transform: translateY(20px);
      transition: opacity 0.6s 0.2s, transform 0.6s 0.2s;
    }

    .skills-panel.in-view {
      opacity: 1;
      transform: none;
    }

    .skills-group {
      margin-bottom: 20px;
    }

    .skills-group:last-child {
      margin-bottom: 0;
    }

    .skills-group-label {
      font-size: 10px;
      text-transform: uppercase;
      letter-spacing: 1.5px;
      color: var(--dim);
      font-weight: 700;
      margin-bottom: 10px;
    }

    .skills-chips {
      display: flex;
      flex-wrap: wrap;
      gap: 6px;
    }

    .skill-chip {
      border-radius: 8px;
      padding: 5px 10px;
      font-size: 12px;
      font-weight: 500;
      border: 1px solid;
      transition: transform 0.2s;
    }

    .skill-chip:hover {
      transform: translateY(-2px);
    }

    .sc-blue {
      background: rgba(94, 155, 255, 0.07);
      color: var(--blue);
      border-color: rgba(94, 155, 255, 0.22);
    }

    .sc-gray {
      background: rgba(255, 255, 255, 0.04);
      color: var(--muted);
      border-color: rgba(255, 255, 255, 0.08);
    }

    .bio-actions {
      display: flex;
      gap: 12px;
      flex-wrap: wrap;
      opacity: 0;
      transform: translateY(20px);
      transition: opacity 0.6s 0.3s, transform 0.6s 0.3s;
    }

    .bio-actions.in-view {
      opacity: 1;
      transform: none;
    }

    /* ── ANIMATIONS ── */
    @keyframes fadeUp {
      from {
        opacity: 0;
        transform: translateY(24px);
      }

      to {
        opacity: 1;
        transform: translateY(0);
      }
    }

    /* ── FOOTER ── */
    footer {
      border-top: 1px solid var(--border);
      padding: 32px;
      text-align: center;
      font-size: 12px;
      color: var(--dim);
    }

    /* ── RESPONSIVE ── */
    @media (max-width: 900px) {
      .projects-grid {
        grid-template-columns: 1fr;
      }

      .stage-block {
        grid-template-columns: 1fr;
      }

      .stage-right {
        border-left: none;
        border-top: 1px solid var(--border);
      }

      .bio-hero {
        grid-template-columns: 1fr;
        text-align: center;
      }

      .bio-avatar {
        margin: 0 auto;
      }

      .bio-tags {
        justify-content: center;
      }

      .bio-stats-row {
        grid-template-columns: repeat(2, 1fr);
      }

      .bio-grid {
        grid-template-columns: 1fr;
      }

      .nav-links {
        gap: 2px;
      }

      .nav-links a {
        padding: 5px 10px;
        font-size: 12px;
      }

      .section-wrap {
        padding: 80px 20px;
      }

      .hero-title {
        letter-spacing: -2px;
      }

      body {
        cursor: auto;
      }

      .cursor {
        display: none;
      }

      .gallery-modal {
        max-height: 95vh;
      }

      .gallery-grid {
        padding: 16px 16px 24px;
      }

      .gallery-modal-header {
        padding: 18px 20px;
      }
    }

    @media print {

      nav,
      .cursor,
      .hero-scroll {
        display: none !important;
      }

      .project-card,
      .stage-block,
      .veille-card,
      .bio-hero,
      .bio-stats-row,
      .bio-panel,
      .skills-panel,
      .bio-actions {
        opacity: 1 !important;
        transform: none !important;
      }
    }
  </style>
</head>

<body>

  <!-- Gallery Modal -->
  <div class="gallery-overlay" id="galleryOverlay" role="dialog" aria-modal="true" aria-label="Galerie photos IMSA">
    <div class="gallery-modal">
      <div class="gallery-modal-header">
        <div class="gallery-modal-title">
          📸 Galerie IMSA
          <span class="title-badge">Stage 1 · 2024</span>
        </div>
        <button class="gallery-close" id="galleryClose" aria-label="Fermer">×</button>
      </div>
      <div class="gallery-grid">

        <!-- Photo 1 -->
        <div class="gallery-item">
          <div class="gallery-img-wrap">
            <img src="easyvista.png" alt="Service Manager IMSA"
              onerror="this.parentElement.innerHTML='<div class=\'gallery-placeholder\'><svg width=\'48\' height=\'48\' viewBox=\'0 0 24 24\' fill=\'none\' stroke=\'currentColor\' stroke-width=\'1.5\'><rect x=\'3\' y=\'3\' width=\'18\' height=\'18\' rx=\'3\'/><circle cx=\'8.5\' cy=\'8.5\' r=\'1.5\'/><path d=\'m21 15-5-5L5 21\'/></svg><div><strong>Photo 1</strong><p>Remplacez par votre image :<br><code>service-manager.jpg</code></p></div></div>'">
          </div>
          <div class="gallery-caption">
            <div class="gallery-caption-num">1</div>
            <div class="gallery-caption-text">
              <strong>Console Service Manager & gestion des incidents easyvista</strong>
              <span>IMSA Montauban — Support utilisateurs</span>
            </div>
          </div>
        </div>

        <!-- Photo 2 -->
        <div class="gallery-item">
          <div class="gallery-img-wrap">
            <img src="teamviewer.png" alt="Assistance TeamViewer IMSA"
              onerror="this.parentElement.innerHTML='<div class=\'gallery-placeholder\'><svg width=\'48\' height=\'48\' viewBox=\'0 0 24 24\' fill=\'none\' stroke=\'currentColor\' stroke-width=\'1.5\'><rect x=\'3\' y=\'3\' width=\'18\' height=\'18\' rx=\'3\'/><circle cx=\'8.5\' cy=\'8.5\' r=\'1.5\'/><path d=\'m21 15-5-5L5 21\'/></svg><div><strong>Photo 2</strong><p>Remplacez par votre image :<br><code>teamviewer.jpg</code></p></div></div>'">
          </div>
          <div class="gallery-caption">
            <div class="gallery-caption-num">2</div>
            <div class="gallery-caption-text">
              <strong>Assistance à distance & prise de contrôle TeamViewer</strong>
              <span>Support technique — Intervention utilisateurs</span>
            </div>
          </div>
        </div>

        <!-- Photo 3 -->
        <div class="gallery-item">
          <div class="gallery-img-wrap">
            <img src="Multilinessettings.png" alt="Système Mitel IMSA"
              onerror="this.parentElement.innerHTML='<div class=\'gallery-placeholder\'><svg width=\'48\' height=\'48\' viewBox=\'0 0 24 24\' fill=\'none\' stroke=\'currentColor\' stroke-width=\'1.5\'><rect x=\'3\' y=\'3\' width=\'18\' height=\'18\' rx=\'3\'/><circle cx=\'8.5\' cy=\'8.5\' r=\'1.5\'/><path d=\'m21 15-5-5L5 21\'/></svg><div><strong>Photo 3</strong><p>Remplacez par votre image :<br><code>mitel.jpg</code></p></div></div>'">
          </div>
          <div class="gallery-caption">
            <div class="gallery-caption-num">3</div>
            <div class="gallery-caption-text">
              <strong>Système téléphonique Mitel & communication unifiée</strong>
              <span>Infrastructure VoIP — Gestion des appels</span>
            </div>
          </div>
        </div>

      </div>
    </div>
  </div>

  <!-- Cursor -->
  <div class="cursor" id="cursor-ring" style="position:fixed;pointer-events:none;z-index:9999;top:0;left:0;">
    <div class="cursor-ring" style="position:absolute;"></div>
  </div>
  <div class="cursor" id="cursor-dot" style="position:fixed;pointer-events:none;z-index:9999;top:0;left:0;">
    <div class="cursor-dot" style="position:absolute;"></div>
  </div>

  <!-- Nav -->
  <nav id="nav">
    <div class="nav-inner">
      <a href="#accueil" class="nav-logo">MA</a>
      <ul class="nav-links">
        <li><a href="#accueil" class="active">Accueil</a></li>
        <li><a href="#projets">Projets</a></li>
        <li><a href="#stage">Stage</a></li>
        <li><a href="#veille">Veille</a></li>
        <li><a href="#bio">Bio</a></li>
      </ul>
    </div>
  </nav>

  <!-- HERO -->
  <section id="accueil">
    <div class="hero-bg"></div>
    <div class="hero-grid"></div>
    <div class="hero-eyebrow">BTS SIO · Option SLAM · Session 2026</div>
    <h1 class="hero-title">Mathieu<br>Arakelian</h1>
    <p class="hero-subtitle">Développeur logiciel</p>
    <div class="hero-actions">
      <a href="#projets" class="btn-primary">
        <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5" stroke-linecap="round">
          <path d="M3 12h18M13 6l6 6-6 6" />
        </svg>
        Voir mes projets
      </a>
      <a href="https://github.com/Mathieuarak" target="_blank" rel="noopener" class="btn-ghost">
        <svg width="16" height="16" viewBox="0 0 24 24" fill="currentColor">
          <path d="M12 2C6.477 2 2 6.477 2 12c0 4.418 2.865 8.166 6.839 9.489.5.092.682-.217.682-.482 0-.237-.009-.866-.013-1.7-2.782.603-3.369-1.342-3.369-1.342-.454-1.155-1.11-1.462-1.11-1.462-.908-.62.069-.608.069-.608 1.003.07 1.531 1.03 1.531 1.03.892 1.529 2.341 1.088 2.91.832.092-.647.35-1.088.636-1.338-2.22-.253-4.555-1.11-4.555-4.943 0-1.091.39-1.984 1.029-2.683-.103-.253-.446-1.27.098-2.647 0 0 .84-.269 2.75 1.025A9.578 9.578 0 0 1 12 6.836a9.59 9.59 0 0 1 2.504.337c1.909-1.294 2.747-1.025 2.747-1.025.546 1.377.203 2.394.1 2.647.64.699 1.028 1.592 1.028 2.683 0 3.842-2.339 4.687-4.566 4.935.359.309.678.919.678 1.852 0 1.336-.012 2.415-.012 2.743 0 .267.18.579.688.481C19.138 20.163 22 16.418 22 12c0-5.523-4.477-10-10-10z" />
        </svg>
        GitHub
      </a>
    </div>
    <div class="hero-scroll">
      <span>Scroll</span>
      <div class="scroll-line"></div>
    </div>
  </section>

  <!-- PROJETS -->
  <section id="projets">
    <div class="section-wrap">
      <div class="section-label">Réalisations</div>
      <h2 class="section-title">Mes Projets</h2>
      <div class="projects-grid">

        <!-- AP1 -->
        <div class="project-card">
          <div class="card-header">
            <div class="card-glow glow-blue"></div>
            <span class="proj-badge b-blue">AP1 · 1re année</span>
            <h3>Catalog</h3>
            <p>Site WordPress pour la vente de confitures artisanales : catalogue produits, fiches articles et gestion de contenu CMS.</p>
          </div>
          <div class="card-tools">
            <span class="tool-chip">🌐 WordPress</span>
            <span class="tool-chip">🎨 CSS</span>
            <span class="tool-chip">🔌 WooCommerce</span>
            <span class="tool-chip">📝 HTML</span>
          </div>
          <div class="card-stats">
            <div class="stat">
              <div class="stat-val" style="color:var(--blue)">4</div>
              <div class="stat-key">pages</div>
            </div>
            <div class="stat">
              <div class="stat-val" style="color:var(--blue)">2</div>
              <div class="stat-key">devs</div>
            </div>
            <div class="stat">
              <div class="stat-val" style="color:var(--blue)">E-com</div>
              <div class="stat-key">type</div>
            </div>
          </div>
          <div class="card-footer">
            <a class="proj-link" href="Document final projet Groupe Mathieu Cedric souareba.pdf" target="_blank" rel="noopener">
              <svg viewBox="0 0 24 24" fill="currentColor">
                <path d="M6 2h9l5 5v13a2 2 0 0 1-2 2H6a2 2 0 0 1-2-2V4a2 2 0 0 1 2-2zm9 3.5V9h3.5L15 5.5z" />
              </svg>
              Voir le projet
              <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5" stroke-linecap="round">
                <path d="M5 12h14M12 6l6 6-6 6" />
              </svg>
            </a>
          </div>
        </div>

        <!-- AP2 -->
        <div class="project-card">
          <div class="card-header">
            <div class="card-glow glow-green"></div>
            <span class="proj-badge b-green">AP2 · 1re année</span>
            <h3>eTrombi</h3>
            <p>Trombinoscope en ligne pour étudiants : annuaire visuel avec recherche, profils et gestion des photos de promotion.</p>
          </div>
          <div class="card-tools">
            <span class="tool-chip">🐘 PHP</span>
            <span class="tool-chip">🐬 MySQL</span>
            <span class="tool-chip">📝 HTML / CSS</span>
            <span class="tool-chip">⚡ JavaScript</span>
          </div>
          <div class="card-stats">
            <div class="stat">
              <div class="stat-val" style="color:var(--green)">CRUD</div>
              <div class="stat-key">fonctions</div>
            </div>
            <div class="stat">
              <div class="stat-val" style="color:var(--green)">4</div>
              <div class="stat-key">tech</div>
            </div>
            <div class="stat">
              <div class="stat-val" style="color:var(--green)">Web</div>
              <div class="stat-key">type</div>
            </div>
          </div>
          <div class="card-footer">
            <a class="proj-link" href="Projet_eTrombi.pdf" target="_blank" rel="noopener">
              <svg viewBox="0 0 24 24" fill="currentColor">
                <path d="M6 2h9l5 5v13a2 2 0 0 1-2 2H6a2 2 0 0 1-2-2V4a2 2 0 0 1 2-2zm9 3.5V9h3.5L15 5.5z" />
              </svg>
              Voir le projet
              <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5" stroke-linecap="round">
                <path d="M5 12h14M12 6l6 6-6 6" />
              </svg>
            </a>
          </div>
        </div>

        <!-- AP3 -->
        <div class="project-card">
          <div class="card-header">
            <div class="card-glow glow-yellow"></div>
            <span class="proj-badge b-yellow">AP3 · 2e année</span>
            <h3>Publicom Web</h3>
            <p>Application web permettant aux communes de gérer et diffuser des messages sur leurs panneaux d'affichage lumineux municipaux.</p>
          </div>
          <div class="card-tools">
            <span class="tool-chip">🐘 PHP</span>
            <span class="tool-chip">🐬 MySQL</span>
            <span class="tool-chip">⚡ JavaScript</span>
            <span class="tool-chip">🔀 Git</span>
          </div>
          <div class="card-stats">
            <div class="stat">
              <div class="stat-val" style="color:var(--yellow)">Multi</div>
              <div class="stat-key">communes</div>
            </div>
            <div class="stat">
              <div class="stat-val" style="color:var(--yellow)">4</div>
              <div class="stat-key">tech</div>
            </div>
            <div class="stat">
              <div class="stat-val" style="color:var(--yellow)">Web</div>
              <div class="stat-key">type</div>
            </div>
          </div>
          <div class="card-footer">
            <a class="proj-link" href="Rapport_AP3_Publicom.pdf" target="_blank" rel="noopener">
              <svg viewBox="0 0 24 24" fill="currentColor">
                <path d="M6 2h9l5 5v13a2 2 0 0 1-2 2H6a2 2 0 0 1-2-2V4a2 2 0 0 1 2-2zm9 3.5V9h3.5L15 5.5z" />
              </svg>
              Voir le projet
              <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5" stroke-linecap="round">
                <path d="M5 12h14M12 6l6 6-6 6" />
              </svg>
            </a>
          </div>
        </div>

        <!-- AP4 -->
        <div class="project-card">
          <div class="card-header">
            <div class="card-glow glow-purple"></div>
            <span class="proj-badge b-purple">AP4 · 2e année</span>
            <h3>PublicomClient</h3>
            <p>Application bureau Java Swing pour gérer les panneaux municipaux sans navigateur, avec authentification Active Directory.</p>
          </div>
          <div class="card-tools">
            <span class="tool-chip">☕ Java Swing</span>
            <span class="tool-chip">🗄️ BDD distante</span>
            <span class="tool-chip">🪟 Active Directory</span>
            <span class="tool-chip">🏛️ MVC</span>
          </div>
          <div class="card-stats">
            <div class="stat">
              <div class="stat-val" style="color:var(--purple)">3</div>
              <div class="stat-key">modules</div>
            </div>
            <div class="stat">
              <div class="stat-val" style="color:var(--purple)">AD</div>
              <div class="stat-key">auth</div>
            </div>
            <div class="stat">
              <div class="stat-val" style="color:var(--purple)">Desktop</div>
              <div class="stat-key">type</div>
            </div>
          </div>
          <div class="card-footer">
            <a class="proj-link" href="rendu_AP4_publicom.pdf" target="_blank" rel="noopener">
              <svg viewBox="0 0 24 24" fill="currentColor">
                <path d="M6 2h9l5 5v13a2 2 0 0 1-2 2H6a2 2 0 0 1-2-2V4a2 2 0 0 1 2-2zm9 3.5V9h3.5L15 5.5z" />
              </svg>
              Voir le projet
              <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5" stroke-linecap="round">
                <path d="M5 12h14M12 6l6 6-6 6" />
              </svg>
            </a>
          </div>
        </div>

      </div>
    </div>
  </section>

  <!-- STAGE -->
  <section id="stage">
    <div class="section-wrap">
      <div class="section-label">Expérience</div>
      <h2 class="section-title">Stages</h2>

      <!-- IMSA -->
      <div class="stage-block">
        <div class="stage-left">
          <div><span class="stage-badge sb-blue">Stage 1 · 2024</span></div>
          <div>
            <h3>IMSA — Montauban</h3>
            <div class="stage-period">📍 Montauban · Service Ticketing</div>
            <p class="stage-desc">Stage au sein de l'équipe de ticketing d'un établissement de santé. Missions variées allant de l'administration système à l'assistance utilisateurs et au déploiement de matériel.</p>
          </div>
          <div>
            <div class="act-label">Activités réalisées</div>
            <div class="activity-list">
              <div class="act-item">
                <div class="act-dot dot-b"><svg viewBox="0 0 24 24">
                    <path d="M5 12h14M12 5l7 7-7 7" />
                  </svg></div>
                <div class="act-body"><strong>Programmation de téléphones</strong><span>Configuration et déploiement des postes téléphoniques sur le réseau interne</span></div>
              </div>
              <div class="act-item">
                <div class="act-dot dot-b"><svg viewBox="0 0 24 24">
                    <path d="M5 12h14M12 5l7 7-7 7" />
                  </svg></div>
                <div class="act-body"><strong>Gestion Active Directory</strong><span>Création, modification et suppression de comptes utilisateurs dans l'AD</span></div>
              </div>
              <div class="act-item">
                <div class="act-dot dot-b"><svg viewBox="0 0 24 24">
                    <path d="M5 12h14M12 5l7 7-7 7" />
                  </svg></div>
                <div class="act-body"><strong>Console EasyVista</strong><span>Mise à jour et suppression de tickets sur la plateforme ITSM</span></div>
              </div>
              <div class="act-item">
                <div class="act-dot dot-b"><svg viewBox="0 0 24 24">
                    <path d="M5 12h14M12 5l7 7-7 7" />
                  </svg></div>
                <div class="act-body"><strong>Assistance &amp; interventions utilisateurs</strong><span>Support de proximité, déménagement et installation de matériel</span></div>
              </div>
              <div class="act-item">
                <div class="act-dot dot-b"><svg viewBox="0 0 24 24">
                    <path d="M5 12h14M12 5l7 7-7 7" />
                  </svg></div>
                <div class="act-body"><strong>Masterisation &amp; installation Windows 11</strong><span>Déploiement d'images système, vérification du matériel et mise en service</span></div>
              </div>
            </div>
          </div>
          <!-- ✦ BOUTON GALERIE IMSA -->
          <div class="stage-btn-row">
            <button class="btn-stage btn-stage-blue" id="openGallery" aria-label="Voir la galerie photos du stage IMSA">
              <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                <rect x="3" y="3" width="18" height="18" rx="3" />
                <circle cx="8.5" cy="8.5" r="1.5" />
                <path d="m21 15-5-5L5 21" />
              </svg>
              Voir les photos du stage
              <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5" stroke-linecap="round">
                <path d="M5 12h14M12 6l6 6-6 6" />
              </svg>
            </button>
          </div>
        </div>
        <div class="stage-right">
          <div class="stage-photo">
            <img src="0863a9dc-5c78-488b-8b35-ff5d9d5caa63.png" alt="IMSA Montauban" onerror="this.style.display='none'">
            <div class="photo-caption">IMSA · Montauban</div>
          </div>
          <div class="tools-grid-wrap">
            <div class="tools-lbl">Outils &amp; technologies</div>
            <div class="tools-grid">
              <div class="tool-pill">
                <div class="tool-icon ic-b">🪟</div><span>Active Directory</span>
              </div>
              <div class="tool-pill">
                <div class="tool-icon ic-p">🎫</div><span>EasyVista ITSM</span>
              </div>
              <div class="tool-pill">
                <div class="tool-icon ic-b">💻</div><span>Windows 11</span>
              </div>
              <div class="tool-pill">
                <div class="tool-icon ic-o">🖨️</div><span>Imprimantes réseau</span>
              </div>
              <div class="tool-pill">
                <div class="tool-icon ic-t">📞</div><span>Téléphonie IP</span>
              </div>
              <div class="tool-pill">
                <div class="tool-icon ic-x">🔧</div><span>Masterisation PC</span>
              </div>
            </div>
          </div>
          <div class="stage-nums">
            <div class="stage-num">
              <div class="sn-val" style="color:var(--blue)">5+</div>
              <div class="sn-key">missions</div>
            </div>
            <div class="stage-num">
              <div class="sn-val" style="color:var(--blue)">6</div>
              <div class="sn-key">outils</div>
            </div>
            <div class="stage-num">
              <div class="sn-val" style="color:var(--blue)">1re</div>
              <div class="sn-key">année</div>
            </div>
          </div>
        </div>
      </div>

      <!-- Tauge -->
      <div class="stage-block">
        <div class="stage-left">
          <div><span class="stage-badge sb-green">Stage 2 · 2025</span></div>
          <div>
            <h3>Écuries de la Tauge</h3>
            <div class="stage-period">📍 Développement web · Application de gestion</div>
            <p class="stage-desc">Conception et développement complet d'une application web métier pour la gestion d'une écurie : clients, chevaux, pensions, cours et horaires.</p>
          </div>
          <div>
            <div class="act-label">Activités réalisées</div>
            <div class="activity-list">
              <div class="act-item">
                <div class="act-dot dot-g"><svg viewBox="0 0 24 24">
                    <path d="M5 12h14M12 5l7 7-7 7" />
                  </svg></div>
                <div class="act-body"><strong>Conception de l'application</strong><span>Analyse des besoins, modélisation de la base de données (MCD/MLD)</span></div>
              </div>
              <div class="act-item">
                <div class="act-dot dot-g"><svg viewBox="0 0 24 24">
                    <path d="M5 12h14M12 5l7 7-7 7" />
                  </svg></div>
                <div class="act-body"><strong>Gestion des clients &amp; chevaux</strong><span>Module CRUD complet pour les profils clients et les fiches chevaux</span></div>
              </div>
              <div class="act-item">
                <div class="act-dot dot-g"><svg viewBox="0 0 24 24">
                    <path d="M5 12h14M12 5l7 7-7 7" />
                  </svg></div>
                <div class="act-body"><strong>Gestion des pensions &amp; installations</strong><span>Suivi des boxes, tarifs et disponibilités</span></div>
              </div>
              <div class="act-item">
                <div class="act-dot dot-g"><svg viewBox="0 0 24 24">
                    <path d="M5 12h14M12 5l7 7-7 7" />
                  </svg></div>
                <div class="act-body"><strong>Système de gestion des cours</strong><span>Horaires, niveaux, tarifs et organisation des activités équestres</span></div>
              </div>
              <div class="act-item">
                <div class="act-dot dot-g"><svg viewBox="0 0 24 24">
                    <path d="M5 12h14M12 5l7 7-7 7" />
                  </svg></div>
                <div class="act-body"><strong>Déploiement en production</strong><span>Mise en ligne sur <a href="https://lataugegestion.fr" target="_blank" rel="noopener" style="color:var(--green)">lataugegestion.fr</a></span></div>
              </div>
            </div>
          </div>
          <!-- ✦ BOUTON PDF EXPRESSION DE BESOIN -->
          <div class="stage-btn-row">
          <a class="btn-stage btn-stage-green" href="expression_de_besoin_tauge.html" target="_blank" rel="noopener" aria-label="Voir l'expression de besoin du stage Tauge">
            <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
              <path d="M6 2h9l5 5v13a2 2 0 0 1-2 2H6a2 2 0 0 1-2-2V4a2 2 0 0 1 2-2z"/>
              <path d="M14 2v5h5M9 13h6M9 17h6M9 9h1"/>
            </svg>
            Expression de besoin
            <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5" stroke-linecap="round"><path d="M5 12h14M12 6l6 6-6 6"/></svg>
          </a>
        </div>
      </div>
        <div class="stage-right">
          <div class="stage-photo">
            <img src="f5a4cf7e-c927-4f38-a631-1b6ba2072df9.png" alt="Écuries de la Tauge" onerror="this.style.display='none'">
            <div class="photo-caption">Écuries de la Tauge · Application web</div>
          </div>
          <div class="tools-grid-wrap">
            <div class="tools-lbl">Outils &amp; technologies</div>
            <div class="tools-grid">
              <div class="tool-pill">
                <div class="tool-icon ic-o">🐘</div><span>PHP</span>
              </div>
              <div class="tool-pill">
                <div class="tool-icon ic-b">🐬</div><span>MySQL</span>
              </div>
              <div class="tool-pill">
                <div class="tool-icon ic-y">⚡</div><span>JavaScript</span>
              </div>
              <div class="tool-pill">
                <div class="tool-icon ic-t">🌐</div><span>HTML / CSS</span>
              </div>
              <div class="tool-pill">
                <div class="tool-icon ic-x">🔀</div><span>Git / GitHub</span>
              </div>
              <div class="tool-pill">
                <div class="tool-icon ic-g">🚀</div><span>Déploiement</span>
              </div>
            </div>
          </div>
          <div class="stage-nums">
            <div class="stage-num">
              <div class="sn-val" style="color:var(--green)">5</div>
              <div class="sn-key">modules</div>
            </div>
            <div class="stage-num">
              <div class="sn-val" style="color:var(--green)">6</div>
              <div class="sn-key">technologies</div>
            </div>
            <div class="stage-num">
              <div class="sn-val" style="color:var(--green)">2e</div>
              <div class="sn-key">année</div>
            </div>
          </div>
        </div>
      </div>

    </div>
  </section>

  <!-- VEILLE -->
  <section id="veille">
    <div class="section-wrap">
      <div class="section-label">Actualité tech</div>
      <h2 class="section-title">Veille Technologique</h2>
      <div class="veille-grid">

        <!-- F1 + IA -->
        <div class="veille-card">
          <div class="vc-header" style="background:linear-gradient(135deg,rgba(255,159,67,0.07) 0%,transparent 100%);">
            <div class="vc-icon ic-o">🏎️</div>
            <div class="vc-meta">
              <div class="vc-kicker" style="color:var(--orange)">Intelligence Artificielle · 2024–2025</div>
              <h3 class="vc-title">F1 & Intelligence Artificielle : la course aux données</h3>
              <div class="vc-tags">
                <span class="vc-tag" style="background:rgba(255,159,67,0.1);color:var(--orange);border:1px solid rgba(255,159,67,0.2);">Machine Learning</span>
                <span class="vc-tag" style="background:rgba(255,255,255,0.04);color:var(--muted);border:1px solid var(--border);">Stratégie de course</span>
                <span class="vc-tag" style="background:rgba(255,255,255,0.04);color:var(--muted);border:1px solid var(--border);">Analyse en temps réel</span>
                <span class="vc-tag" style="background:rgba(255,255,255,0.04);color:var(--muted);border:1px solid var(--border);">Big Data</span>
              </div>
            </div>
          </div>
          <div class="vc-body">
            <p>La Formule 1 est aujourd'hui l'un des sports les plus technologiquement avancés au monde. Chaque voiture génère jusqu'à <strong style="color:var(--text)">300 Go de données par course</strong>, transmises en temps réel aux ingénieurs. L'IA et le Machine Learning sont devenus des piliers de la stratégie : ils prédisent les arrêts aux stands, analysent l'usure des pneus et simulent des milliers de scénarios de course.</p>
            <p>Des écuries comme <strong style="color:var(--text)">Mercedes, Ferrari ou Red Bull</strong> investissent massivement dans des modèles prédictifs. Oracle est partenaire officiel de Red Bull Racing pour l'analyse des données de course. AWS fournit à plusieurs équipes des outils de simulation basés sur le cloud, permettant de tester en quelques secondes des stratégies qui prendraient des heures à calculer manuellement.</p>
            <div class="vc-metrics">
              <div class="metric" style="background:rgba(255,159,67,0.06);border-color:rgba(255,159,67,0.15);">
                <div class="metric-val" style="color:var(--orange)">300 Go</div>
                <div class="metric-lbl">Données par course</div>
              </div>
              <div class="metric" style="background:rgba(255,159,67,0.06);border-color:rgba(255,159,67,0.15);">
                <div class="metric-val" style="color:var(--orange)">1 500+</div>
                <div class="metric-lbl">Capteurs par voiture</div>
              </div>
              <div class="metric" style="background:rgba(255,159,67,0.06);border-color:rgba(255,159,67,0.15);">
                <div class="metric-val" style="color:var(--orange)">∞</div>
                <div class="metric-lbl">Simulations en temps réel</div>
              </div>
            </div>
            <div class="vc-timeline">
              <div class="vc-tl-label">Points clés</div>
              <div class="tl-row">
                <span class="tl-date" style="color:var(--orange)">Arrêts</span>
                <span class="tl-text">L'IA prédit le moment optimal pour rentrer aux stands en analysant météo, trafic, dégradation des pneus et position des adversaires</span>
              </div>
              <div class="tl-row">
                <span class="tl-date" style="color:var(--orange)">Pneus</span>
                <span class="tl-text">Des modèles ML analysent l'usure des gommes tour par tour grâce aux capteurs embarqués, et alertent en temps réel les ingénieurs</span>
              </div>
              <div class="tl-row">
                <span class="tl-date" style="color:var(--orange)">Simulation</span>
                <span class="tl-text">Les équipes simulent des milliers de scénarios de course avant le départ pour choisir la stratégie de pneus et d'arrêts optimale</span>
              </div>
              <div class="tl-row">
                <span class="tl-date" style="color:var(--orange)">Équipes</span>
                <span class="tl-text">Mercedes, Ferrari et Red Bull utilisent des partenariats avec Oracle, AWS et Microsoft pour leurs modèles prédictifs</span>
              </div>
            </div>
            <div class="vc-footer">
              <span class="vc-source">Source : Motorsport.com — janvier 2025</span>
              <a href="https://fr.motorsport.com/f1/news/comment-ia-intelligence-artificielle-changer-f1/10660360/" target="_blank" rel="noopener" class="vc-link" style="background:var(--orange);">
                Lire l'article
                <svg viewBox="0 0 24 24">
                  <path d="M7 17L17 7M7 7h10v10" />
                </svg>
              </a>
            </div>
          </div>
        </div>
<!-- F1 + IA article 2 -->
<div class="veille-card">
  <div class="vc-header" style="background:linear-gradient(135deg,rgba(78,203,113,0.07) 0%,transparent 100%);">
    <div class="vc-icon ic-g">📊</div>
    <div class="vc-meta">
      <div class="vc-kicker" style="color:var(--green)">Prédiction · Mai 2025</div>
      <h3 class="vc-title">L'IA peut-elle vraiment prédire l'issue d'un Grand Prix ?</h3>
      <div class="vc-tags">
        <span class="vc-tag" style="background:rgba(78,203,113,0.1);color:var(--green);border:1px solid rgba(78,203,113,0.2);">Prédiction</span>
        <span class="vc-tag" style="background:rgba(255,255,255,0.04);color:var(--muted);border:1px solid var(--border);">Simulation</span>
        <span class="vc-tag" style="background:rgba(255,255,255,0.04);color:var(--muted);border:1px solid var(--border);">Big Data</span>
      </div>
    </div>
  </div>
  <div class="vc-body">
    <p>L'IA s'impose aujourd'hui comme un outil stratégique dans le monde de la F1. Elle croise des milliers de variables — météo, état du circuit, performances en essais, historique des pilotes — pour anticiper le déroulement d'une course. Sa force : elle apprend et s'adapte à chaque nouveau Grand Prix.</p>
    <p>Au-delà de l'analyse des données passées, l'IA <strong style="color:var(--text)">simule aussi l'avenir</strong> : elle génère des scénarios en temps réel pour aider les ingénieurs à ajuster leur stratégie en cours de course. Une capacité que l'analyse humaine seule ne peut pas égaler à cette vitesse.</p>
    <div class="vc-metrics">
      <div class="metric" style="background:rgba(78,203,113,0.06);border-color:rgba(78,203,113,0.15);">
        <div class="metric-val" style="color:var(--green)">8</div>
        <div class="metric-lbl">Nouveaux partenariats IA/F1 en 6 mois</div>
      </div>
      <div class="metric" style="background:rgba(78,203,113,0.06);border-color:rgba(78,203,113,0.15);">
        <div class="metric-val" style="color:var(--green)">2018</div>
        <div class="metric-lbl">Début du ML en F1</div>
      </div>
      <div class="metric" style="background:rgba(78,203,113,0.06);border-color:rgba(78,203,113,0.15);">
        <div class="metric-val" style="color:var(--green)">100%</div>
        <div class="metric-lbl">Des top équipes utilisent l'IA</div>
      </div>
    </div>
    <div class="vc-footer">
      <span class="vc-source">Source : LeBigData.fr — mai 2025</span>
      <a href="https://www.lebigdata.fr/lia-fiable-pour-predire-lissue-dune-course-de-formule-1" target="_blank" rel="noopener" class="vc-link">
        Lire l'article
        <svg viewBox="0 0 24 24"><path d="M7 17L17 7M7 7h10v10"/></svg>
      </a>
    </div>
  </div>
</div>
      </div>
    </div>
    
  </section>

  <!-- BIO -->
  <section id="bio">
    <div class="section-wrap">
      <div class="section-label">À propos</div>
      <h2 class="section-title">Bio</h2>

      <div class="bio-hero">
        <div class="bio-avatar">M</div>
        <div>
          <div class="bio-name">Mathieu Arakelian</div>
          <div class="bio-role">Développeur Logiciel · BTS SIO SLAM</div>
          <p class="bio-desc">Étudiant en 2e année de BTS SIO option SLAM. J'ai réalisé des projets couvrant des applications PHP/MySQL, des logiciels Java Swing et un déploiement en production.</p>
          <div class="bio-tags">
            <span class="bio-tag bt-blue">BTS SIO — option SLAM</span>
            <span class="bio-tag bt-blue">Session 2026</span>
            <span class="bio-tag bt-green">Dev Web &amp; Logiciel</span>
            <span class="bio-tag bt-gray">Montauban, France</span>
          </div>
        </div>
      </div>

      <div class="bio-stats-row">
        <div class="bio-stat">
          <div class="bs-val" style="color:var(--blue)">4</div>
          <div class="bs-key">Projets réalisés</div>
        </div>
        <div class="bio-stat">
          <div class="bs-val" style="color:var(--blue)">2</div>
          <div class="bs-key">Stages effectués</div>
        </div>
        <div class="bio-stat">
          <div class="bs-val" style="color:var(--green)">1</div>
          <div class="bs-key">App en production</div>
        </div>
        <div class="bio-stat">
          <div class="bs-val" style="color:var(--blue)">6</div>
          <div class="bs-key">Langages maîtrisés</div>
        </div>
      </div>

      <div class="bio-grid">
        <div class="bio-panel">
          <div class="panel-label">Formation</div>
          <div style="display:flex;flex-direction:column;gap:0;">
            <div class="timeline-item">
              <div class="tl-dot tl-dot-empty"></div>
              <div>
                <div class="tl-year">2022 – 2024</div>
                <div class="tl-title">Baccalauréat professionnel SN</div>
                <div class="tl-sub">Sciences &amp; Technologies de l'Industrie et du Développement Durable</div>
              </div>
            </div>
            <div class="timeline-item">
              <div class="tl-dot tl-dot-empty"></div>
              <div>
                <div class="tl-year">2024 — 1re année BTS SIO</div>
                <div class="tl-title">BTS SIO — option SLAM</div>
                <div class="tl-sub">Stage IMSA · ticketing, AD, masterisation Windows 11</div>
              </div>
            </div>
            <div class="timeline-item">
              <div class="tl-dot tl-dot-full"></div>
              <div>
                <div class="tl-year">2025 – 2026 · En cours</div>
                <div class="tl-title">BTS SIO — 2e année SLAM</div>
                <div class="tl-sub">Stage Écuries de la Tauge · App déployée en production</div>
              </div>
            </div>
          </div>
        </div>

        <div class="bio-panel">
          <div class="panel-label">Informations</div>
          <div class="info-row">
            <div class="info-icon">🎓</div>
            <div>
              <div class="info-key">Formation</div>
              <div class="info-val">BTS SIO — option SLAM · Session 2026</div>
            </div>
          </div>
          <div class="info-row">
            <div class="info-icon">🏫</div>
            <div>
              <div class="info-key">Établissement</div>
              <div class="info-val">Lycée général — Caussade</div>
            </div>
          </div>
          <div class="info-row">
            <div class="info-icon">📍</div>
            <div>
              <div class="info-key">Localisation</div>
              <div class="info-val">Montauban, Tarn-et-Garonne (82)</div>
            </div>
          </div>
          <div class="info-row">
            <div class="info-icon">🌐</div>
            <div>
              <div class="info-key">Projet en ligne</div>
              <div class="info-val"><a href="https://lataugegestion.fr" target="_blank" rel="noopener" style="color:var(--green);text-decoration:none;">lataugegestion.fr</a> — déployé en production</div>
            </div>
          </div>
        </div>
      </div>

      <div class="skills-panel">
        <div class="panel-label">Compétences techniques</div>
        <div style="display:grid;grid-template-columns:repeat(auto-fill,minmax(200px,1fr));gap:20px;">
          <div class="skills-group">
            <div class="skills-group-label">Langages</div>
            <div class="skills-chips">
              <span class="skill-chip sc-blue">PHP</span>
              <span class="skill-chip sc-blue">JavaScript</span>
              <span class="skill-chip sc-blue">HTML / CSS</span>
              <span class="skill-chip sc-gray">Python</span>
              <span class="skill-chip sc-gray">Java</span>
              <span class="skill-chip sc-gray">C#</span>
              <span class="skill-chip sc-gray">SQL</span>
            </div>
          </div>
          <div class="skills-group">
            <div class="skills-group-label">Bases de données</div>
            <div class="skills-chips">
              <span class="skill-chip sc-blue">MySQL</span>
              <span class="skill-chip sc-gray">MCD / MLD</span>
              <span class="skill-chip sc-gray">Requêtes SQL avancées</span>
            </div>
          </div>
          <div class="skills-group">
            <div class="skills-group-label">Frameworks &amp; CMS</div>
            <div class="skills-chips">
              <span class="skill-chip sc-blue">WordPress</span>
              <span class="skill-chip sc-gray">WooCommerce</span>
              <span class="skill-chip sc-gray">Java Swing (MVC)</span>
            </div>
          </div>
          <div class="skills-group">
            <div class="skills-group-label">Outils</div>
            <div class="skills-chips">
              <span class="skill-chip sc-blue">Git / GitHub</span>
              <span class="skill-chip sc-gray">Active Directory</span>
              <span class="skill-chip sc-gray">EasyVista ITSM</span>
              <span class="skill-chip sc-gray">Déploiement serveur</span>
              <span class="skill-chip sc-gray">Architecture MVC</span>
              <span class="skill-chip sc-gray">CRUD</span>
            </div>
          </div>
        </div>
      </div>

      <div class="bio-actions" style="margin-top:24px;">
        <a href="https://github.com/Mathieuarak?tab=repositories" target="_blank" rel="noopener" class="btn-primary">
          <svg width="16" height="16" viewBox="0 0 24 24" fill="currentColor">
            <path d="M12 2C6.477 2 2 6.477 2 12c0 4.418 2.865 8.166 6.839 9.489.5.092.682-.217.682-.482 0-.237-.009-.866-.013-1.7-2.782.603-3.369-1.342-3.369-1.342-.454-1.155-1.11-1.462-1.11-1.462-.908-.62.069-.608.069-.608 1.003.07 1.531 1.03 1.531 1.03.892 1.529 2.341 1.088 2.91.832.092-.647.35-1.088.636-1.338-2.22-.253-4.555-1.11-4.555-4.943 0-1.091.39-1.984 1.029-2.683-.103-.253-.446-1.27.098-2.647 0 0 .84-.269 2.75 1.025A9.578 9.578 0 0 1 12 6.836a9.59 9.59 0 0 1 2.504.337c1.909-1.294 2.747-1.025 2.747-1.025.546 1.377.203 2.394.1 2.647.64.699 1.028 1.592 1.028 2.683 0 3.842-2.339 4.687-4.566 4.935.359.309.678.919.678 1.852 0 1.336-.012 2.415-.012 2.743 0 .267.18.579.688.481C19.138 20.163 22 16.418 22 12c0-5.523-4.477-10-10-10z" />
          </svg>
          GitHub
        </a>
        <a href="https://lataugegestion.fr" target="_blank" rel="noopener" class="btn-ghost">
          🌐 lataugegestion.fr
        </a>
        <a href="https://www.linkedin.com/in/mathieu-arakelian-911989345/" target="_blank" rel="noopener" class="btn-ghost">
          🌐 linkedin
        </a>
        <a class="proj-link" href="t.pdf" target="_blank" rel="noopener">
          <svg viewBox="0 0 24 24" fill="currentColor">
            <path d="M6 2h9l5 5v13a2 2 0 0 1-2 2H6a2 2 0 0 1-2-2V4a2 2 0 0 1 2-2zm9 3.5V9h3.5L15 5.5z" />
          </svg>
          tableu synthese
          <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5" stroke-linecap="round">
            <path d="M5 12h14M12 6l6 6-6 6" />
          </svg>
        </a>
      </div>

    </div>
  </section>

  <footer>
    <p>© 2026 Mathieu Arakelian · BTS SIO SLAM</p>
  </footer>

  <script>
    // ── CURSOR ──
    const ring = document.getElementById('cursor-ring').firstElementChild;
    const dot = document.getElementById('cursor-dot').firstElementChild;
    let mx = -100,
      my = -100,
      rx = -100,
      ry = -100;
    document.addEventListener('mousemove', e => {
      mx = e.clientX;
      my = e.clientY;
    });
    (function loop() {
      rx += (mx - rx) * 0.14;
      ry += (my - ry) * 0.14;
      ring.parentElement.style.transform = `translate(${rx}px,${ry}px)`;
      dot.parentElement.style.transform = `translate(${mx}px,${my}px)`;
      requestAnimationFrame(loop);
    })();

    // ── NAV ACTIVE ──
    const sections = document.querySelectorAll('section[id]');
    const navLinks = document.querySelectorAll('.nav-links a');
    const io = new IntersectionObserver(entries => {
      entries.forEach(e => {
        if (e.isIntersecting) {
          navLinks.forEach(a => a.classList.remove('active'));
          const l = document.querySelector(`.nav-links a[href="#${e.target.id}"]`);
          if (l) l.classList.add('active');
        }
      });
    }, {
      threshold: 0.4
    });
    sections.forEach(s => io.observe(s));

    // ── SCROLL ANIMATIONS ──
    const animObs = new IntersectionObserver(entries => {
      entries.forEach(e => {
        if (e.isIntersecting) {
          const el = e.target;
          const delay = el.dataset.delay || 0;
          setTimeout(() => el.classList.add('in-view'), delay * 150);
        }
      });
    }, {
      threshold: 0.1
    });

    document.querySelectorAll('.section-wrap').forEach(wrap => {
      const label = wrap.querySelector('.section-label');
      const title = wrap.querySelector('.section-title');
      const obs2 = new IntersectionObserver(entries => {
        if (entries[0].isIntersecting) {
          if (label) label.style.cssText += 'opacity:1;transform:none;';
          if (title) title.style.cssText += 'opacity:1;transform:none;';
          obs2.disconnect();
        }
      }, {
        threshold: 0.1
      });
      obs2.observe(wrap);
    });

    document.querySelectorAll('.project-card').forEach((card, i) => {
      card.dataset.delay = i;
      animObs.observe(card);
    });

    document.querySelectorAll('.stage-block, .veille-card, .bio-hero, .bio-stats-row, .bio-panel, .skills-panel, .bio-actions').forEach(el => {
      animObs.observe(el);
    });

    // ── SMOOTH SCROLL ──
    document.querySelectorAll('a[href^="#"]').forEach(a => {
      a.addEventListener('click', e => {
        e.preventDefault();
        const target = document.querySelector(a.getAttribute('href'));
        if (target) target.scrollIntoView({
          behavior: 'smooth',
          block: 'start'
        });
      });
    });

    // ── GALLERY MODAL ──
    const overlay = document.getElementById('galleryOverlay');
    const openBtn = document.getElementById('openGallery');
    const closeBtn = document.getElementById('galleryClose');

    function openGallery() {
      overlay.classList.add('open');
      document.body.style.overflow = 'hidden';
      closeBtn.focus();
    }

    function closeGallery() {
      overlay.classList.remove('open');
      document.body.style.overflow = '';
      openBtn.focus();
    }

    openBtn.addEventListener('click', openGallery);
    closeBtn.addEventListener('click', closeGallery);

    // Close on overlay click (outside modal)
    overlay.addEventListener('click', e => {
      if (e.target === overlay) closeGallery();
    });

    // Close on Escape key
    document.addEventListener('keydown', e => {
      if (e.key === 'Escape' && overlay.classList.contains('open')) closeGallery();
    });
  </script>
</body>

</html>