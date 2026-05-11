<style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Inter', system-ui, -apple-system, 'Segoe UI', Roboto, 'Helvetica Neue', sans-serif;
      background-color: #9D2A2A;
      color: #1a1a2e;
      line-height: 1.4;
    }

    .container {
      max-width: 1280px;
      margin: 0 auto;
      padding: 0 48px;
    }

    header {
      background-color: #F39B9B;
      padding: 20px 0;
      border-bottom: 3px solid #ffcd3c;
      position: sticky;
      top: 0;
      z-index: 100;
      box-shadow: 0 4px 20px rgba(0, 0, 0, 0.1);
    }

    .nav-bar {
      display: flex;
      justify-content: center;
      gap: 2.8rem;
      flex-wrap: wrap;
      list-style: none;
    }

    .nav-btn {
      background: none;
      border: none;
      font-size: 1.2rem;
      font-weight: 600;
      color: #2c1a1a;
      cursor: pointer;
      padding: 8px 4px;
      transition: all 0.2s ease;
      font-family: inherit;
      letter-spacing: 0.3px;
      position: relative;
    }

    .nav-btn:hover {
      color: #ffffff;
    }

    .nav-btn.active {
      color: #ffffff;
    }

    .nav-btn.active::after {
      content: '';
      position: absolute;
      bottom: -2px;
      left: 0;
      width: 100%;
      height: 3px;
      background-color: #ffcd3c;
      border-radius: 2px;
    }

    .page {
      display: none;
      animation: fadeIn 0.3s ease;
      padding: 48px 0 80px;
    }

    .page.active-page {
      display: block;
    }

    @keyframes fadeIn {
      from {
        opacity: 0;
        transform: translateY(8px);
      }
      to {
        opacity: 1;
        transform: translateY(0);
      }
    }

    .card-bg {
      background: #F39B9B;
      border-radius: 28px;
      box-shadow: 0 12px 28px rgba(0, 0, 0, 0.15);
      padding: 32px 36px;
      margin-top: 24px;
      color: #2c1a1a;  
    }

    .info-block {
      background: #F39B9B;
      border-radius: 28px;
      padding: 20px;
      flex: 1;
      border: 1px solid rgba(255, 240, 210, 0.5);
      color: #2c1a1a;
    }

    .achievement-card {
      background: #e68484;
      border-radius: 28px;
      box-shadow: 0 10px 20px rgba(0, 0, 0, 0.1);
      padding: 28px 24px;
      flex: 1 1 220px;
      text-align: center;
      transition: transform 0.2s, box-shadow 0.2s;
      border: 1px solid rgba(255, 220, 170, 0.6);
      color: #2c1a1a;
    }

    .achievement-card:hover {
      transform: translateY(-5px);
      box-shadow: 0 24px 36px rgba(0, 0, 0, 0.2);
      background: #ffaeae;
    }

    .resource-item {
      background: #e68484;
      border-radius: 60px;
      padding: 14px 24px;
      display: flex;
      align-items: center;
      flex-wrap: wrap;
      gap: 16px;
      font-size: 1.1rem;
      font-weight: 500;
      transition: background 0.2s;
      color: #2c1a1a;
    }

    .resource-item:hover {
      background: #ffa5a5;
    }

    .resource-link {
      text-decoration: none;
      color: #2c1a1a;
      font-weight: 600;
      word-break: break-all;
      background: #fff0e0bb;
      padding: 6px 14px;
      border-radius: 40px;
      font-size: 0.9rem;
      transition: 0.2s;
    }

    .resource-link:hover {
      background: #ffcd3c;
      color: #1f1a2e;
    }

    .team-list {
      display: flex;
      flex-direction: column;
      gap: 20px;
      max-height: 65vh;
      overflow-y: auto;
      padding-right: 12px;
      margin-top: 24px;
      border-radius: 28px;
    }

    .team-list::-webkit-scrollbar {
      width: 6px;
    }

    .team-list::-webkit-scrollbar-track {
      background: #c05353;
      border-radius: 10px;
    }

    .team-list::-webkit-scrollbar-thumb {
      background: #ffcd3c;
      border-radius: 10px;
    }

    .team-member-card {
      background: #F39B9B;
      border-radius: 24px;
      padding: 20px 28px;
      box-shadow: 0 4px 12px rgba(0, 0, 0, 0.08);
      border: 1px solid #ffcdb0;
      transition: all 0.2s;
      display: flex;
      align-items: center;
      gap: 20px;
      flex-wrap: wrap;
      color: #2c1a1a;
    }

    .team-member-card:hover {
      background: #ffaaaa;
    }

    .member-avatar {
      width: 56px;
      height: 56px;
      background: linear-gradient(145deg, #ffcd3c, #ffb347);
      border-radius: 40px;
      display: flex;
      align-items: center;
      justify-content: center;
      font-size: 1.8rem;
      font-weight: bold;
      color: #1e1a2f;
    }

    .member-name {
      font-weight: 800;
      font-size: 1.25rem;
      color: #2c1a1a;
    }

    .member-role {
      color: #3f2a2a;
      margin-top: 4px;
      font-weight: 500;
    }

    h1 {
      font-size: 3.2rem;
      font-weight: 800;
      margin-bottom: 16px;
      color: #2c1a1a;
      letter-spacing: -0.5px;
      text-shadow: 0 1px 2px rgba(255,205,60,0.3);
    }

    h2 {
      font-size: 2rem;
      font-weight: 700;
      margin-bottom: 24px;
      color: #2c1a1a;
      border-left: 6px solid #ffcd3c;
      padding-left: 20px;
    }

    h3 {
      font-size: 1.5rem;
      font-weight: 600;
      margin: 20px 0 12px 0;
      color: #2c1a1a;
    }

    .hero-text {
      font-size: 1.2rem;
      line-height: 1.5;
      color: #2c1a1a;
      background: rgba(0,0,0,0.02);
      border-radius: 32px;
    }

    .subhead {
      font-size: 1.15rem;
      color: #3f2a2a;
      margin-bottom: 16px;
      font-weight: 500;
    }

    footer {
      background: #b13e3e;
      color: #fff0d0;
      text-align: center;
      padding: 28px 16px;
      font-size: 0.85rem;
      border-top: 1px solid #ffcd7a;
      margin-top: 40px;
    }

    .btn-soft {
      background: #e27c7c;
      border-radius: 999px;
      padding: 8px 18px;
      font-size: 0.9rem;
    }

    @media (max-width: 800px) {
      .container {
        padding: 0 24px;
      }
      .nav-bar {
        gap: 1.2rem;
      }
      h1 {
        font-size: 2.4rem;
      }
      .card-bg {
        padding: 24px 20px;
      }
    }

    .flex-row {
      display: flex;
      gap: 20px;
      flex-wrap: wrap;
      justify-content: space-between;
      margin-top: 32px;
    }

    .about-highlight {
      background: #e27c7c;
      border-radius: 32px;
      padding: 24px;
      text-align: center;
    }

    .resource-item span {
      font-weight: 700;
    }
  </style>
