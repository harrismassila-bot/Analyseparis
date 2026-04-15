<!DOCTYPE html>
<html lang="fr">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0, viewport-fit=cover, user-scalable=no">
<meta name="apple-mobile-web-app-capable" content="yes">
<meta name="apple-mobile-web-app-status-bar-style" content="black-translucent">
<meta name="apple-mobile-web-app-title" content="Stratège 1X2">
<meta name="theme-color" content="#070708">
<title>Stratège · Analyse 1X2</title>
<link href="https://fonts.googleapis.com/css2?family=DM+Serif+Display&family=DM+Mono:wght@400;500&family=DM+Sans:wght@400;500;600;700&display=swap" rel="stylesheet">
<style>
:root{
  --bg:#070708;--surface:#0f0f11;--card:#131316;--border:#1e1e24;--border2:#2a2a33;
  --gold:#c9a84c;--gold2:#e8c97a;--gold3:#f5e0a0;
  --green:#2ecc8a;--green2:#1a7a53;--red:#e05c5c;--red2:#7a2020;
  --amber:#e0962a;--amber2:#7a4f10;--blue:#4a8fd4;
  --muted:#555560;--dim:#333340;--text:#e8e8f0;--text2:#8888a0;
  --safe-t:env(safe-area-inset-top,0px);--safe-b:env(safe-area-inset-bottom,0px);
}
*{box-sizing:border-box;margin:0;padding:0;-webkit-tap-highlight-color:transparent}
html,body{height:100%;background:var(--bg);color:var(--text);font-family:'DM Sans',sans-serif;overscroll-behavior:none;font-size:15px}
#nav{position:fixed;top:0;left:0;right:0;z-index:100;background:rgba(7,7,8,.96);backdrop-filter:blur(20px);border-bottom:1px solid var(--border);padding-top:calc(var(--safe-t) + 6px)}
.nav-inner{display:flex;justify-content:space-between;align-items:center;padding:0 16px 10px}
.nav-logo{font-family:'DM Serif Display',serif;color:var(--gold);font-size:20px}
.nav-sub{font-size:10px;color:var(--muted);margin-top:1px}
.nav-badge{background:#c9a84c18;color:var(--gold);border:1px solid #c9a84c30;padding:3px 10px;border-radius:20px;font-size:11px;font-weight:600}
.tabs{display:flex;overflow-x:auto;scrollbar-width:none;padding:0 10px;gap:2px}
.tabs::-webkit-scrollbar{display:none}
.tab{flex-shrink:0;background:none;border:none;color:var(--muted);font-size:12px;font-weight:600;padding:8px 12px 9px;border-bottom:2px solid transparent;cursor:pointer;font-family:inherit;white-space:nowrap}
.tab.on{color:var(--gold);border-bottom-color:var(--gold)}
#root{padding-top:calc(var(--safe-t) + 100px);padding-bottom:calc(var(--safe-b) + 24px);padding-left:14px;padding-right:14px;max-width:600px;margin:0 auto}
.card{background:var(--card);border-radius:14px;padding:14px;margin-bottom:10px;border:1px solid var(--border)}
.card.ag{border-left:3px solid var(--gold)}
.ct{font-size:10px;font-weight:700;text-transform:uppercase;letter-spacing:1px;color:var(--muted);margin-bottom:10px}
.kgrid{display:grid;grid-template-columns:repeat(3,1fr);gap:8px;margin-bottom:10px}
.kcard{background:var(--card);border-radius:12px;padding:12px;border:1px solid var(--border);text-align:center}
.kcard-val{font-size:24px;font-weight:700;line-height:1.1;margin-bottom:3px}
.kcard-lbl{font-size:10px;color:var(--text2)}
.prog{background:#1a1a20;border-radius:99px;height:6px;overflow:hidden;margin:5px 0}
.prog-fill{height:100%;border-radius:99px;transition:width .5s cubic-bezier(.4,0,.2,1)}
.verdict{border-radius:14px;padding:14px 16px;margin-bottom:10px;border:1px solid}
.verdict-t{font-size:15px;font-weight:700;margin-bottom:4px}
.verdict-d{font-size:12px;line-height:1.6;opacity:.85}
.bl-row{display:flex;align-items:center;gap:10px;padding:10px 0;border-bottom:1px solid var(--border)}
.bl-row:last-child{border:none}
.bl-info{flex:1}
.bl-label{font-size:13px;font-weight:500;color:var(--text);line-height:1.4}
.bl-sub{font-size:11px;color:var(--text2);margin-top:2px;line-height:1.4}
.tog{width:46px;height:26px;border-radius:13px;border:1px solid var(--border2);background:var(--surface);cursor:pointer;font-size:10px;font-weight:700;color:var(--text2);font-family:inherit;flex-shrink:0;transition:all .2s}
.tog.ok{background:var(--green2);border-color:var(--green);color:var(--green)}
.tog.ko{background:var(--red2);border-color:var(--red);color:var(--red)}
.sc-row{display:flex;align-items:flex-start;gap:10px;padding:10px 0;border-bottom:1px solid var(--border)}
.sc-row:last-child{border:none}
.sc-info{flex:1}
.sc-label{font-size:13px;font-weight:500;color:var(--text);line-height:1.4}
.sc-guide{font-size:10px;color:var(--text2);margin-top:3px;line-height:1.5;font-family:'DM Mono',monospace}
.sc-ctrl{display:flex;align-items:center;gap:6px;flex-shrink:0}
.sc-btn{width:26px;height:26px;border-radius:50%;border:1px solid var(--border2);background:var(--surface);color:var(--text2);cursor:pointer;font-size:15px;display:flex;align-items:center;justify-content:center;font-family:inherit}
.sc-val{font-weight:700;font-size:15px;min-width:28px;text-align:center;color:var(--gold)}
.sc-max{font-size:10px;color:var(--muted)}
.sec-hdr{display:flex;justify-content:space-between;align-items:center;margin-bottom:10px}
.sec-pts{font-size:11px;font-weight:700;color:var(--gold);background:#c9a84c15;padding:2px 8px;border-radius:99px}
.hist-row{display:flex;align-items:center;gap:10px;padding:9px 0;border-bottom:1px solid var(--border)}
.hist-row:last-child{border:none}
.stat-grid{display:grid;grid-template-columns:1fr 1fr;gap:8px}
.stat-card{background:var(--surface);border-radius:10px;padding:12px;border:1px solid var(--border)}
.stat-val{font-size:20px;font-weight:700;color:var(--gold);margin-bottom:2px}
.stat-lbl{font-size:11px;color:var(--text2)}
.bk-row{display:flex;justify-content:space-between;align-items:center;padding:8px 0;border-bottom:1px solid var(--border)}
.bk-row:last-child{border:none}
.bk-lbl{font-size:13px;color:var(--text2)}
.bk-val{font-size:13px;font-weight:700;font-family:'DM Mono',monospace}
.btn-gold{background:var(--gold);color:#000;border:none;border-radius:10px;padding:11px 20px;font-weight:700;cursor:pointer;font-size:13px;font-family:inherit}
.btn-ghost{background:var(--surface);color:var(--text2);border:1px solid var(--border2);border-radius:10px;padding:9px 16px;font-size:12px;cursor:pointer;font-family:inherit}
.btn-red{background:#7a202020;color:var(--red);border:1px solid #e05c5c30;border-radius:10px;padding:9px 16px;font-size:12px;cursor:pointer;font-family:inherit}
.inp{background:var(--surface);border:1px solid var(--border2);border-radius:8px;padding:10px 12px;color:var(--text);font-size:14px;font-family:inherit;width:100%}
.inp:focus{outline:none;border-color:var(--gold)}
.tag{display:inline-block;padding:2px 8px;border-radius:99px;font-size:10px;font-weight:700}
.tg{background:#1a7a5320;color:var(--green)}
.tr{background:#7a202020;color:var(--red)}
.ta{background:#7a4f1020;color:var(--amber)}
.tx{background:#c9a84c18;color:var(--gold)}
.rule{display:flex;gap:12px;padding:12px 0;border-bottom:1px solid var(--border)}
.rule:last-child{border:none}
.rule-ico{font-size:18px;flex-shrink:0;margin-top:1px}
.rule-t{font-size:12px;font-weight:700;color:var(--gold);margin-bottom:3px}
.rule-d{font-size:12px;color:var(--text2);line-height:1.6}
@keyframes pop{0%{transform:scale(1)}40%{transform:scale(1.2)}100%{transform:scale(1)}}
.pop{animation:pop .25s ease}
</style>
</head>
<body>

<div id="nav">
  <div class="nav-inner">
    <div><div class="nav-logo">Stratège · 1X2</div><div class="nav-sub">Modèle d'analyse ultra-sélectif</div></div>
    <div class="nav-badge">⚡ Actif</div>
  </div>
  <div class="tabs">
    <button class="tab on" onclick="go('analyse')">🔍 Analyse</button>
    <button class="tab" onclick="go('historique')">📋 Historique</button>
    <button class="tab" onclick="go('bankroll')">💰 Bankroll</button>
    <button class="tab" onclick="go('regles')">⚡ Règles</button>
  </div>
</div>

<div id="root">

<!-- ANALYSE -->
<div id="pg-analyse">
  <div class="kgrid">
    <div class="kcard" style="border-top:3px solid var(--gold)"><div class="kcard-val" id="k-score" style="color:var(--gold)">0</div><div class="kcard-lbl">Score / 100</div></div>
    <div class="kcard" style="border-top:3px solid var(--red)"><div class="kcard-val" id="k-block" style="color:var(--red)">0</div><div class="kcard-lbl">Bloquants KO</div></div>
    <div class="kcard" style="border-top:3px solid var(--green)"><div class="kcard-val" id="k-verdict" style="color:var(--text2)">—</div><div class="kcard-lbl">Verdict</div></div>
  </div>

  <div class="card" style="padding:12px 14px">
    <div style="display:flex;justify-content:space-between;margin-bottom:4px">
      <span style="font-size:11px;color:var(--text2)">Score global</span>
      <span style="font-size:11px;font-weight:700" id="k-score-txt">0 / 100</span>
    </div>
    <div class="prog" style="height:8px"><div class="prog-fill" id="score-bar" style="width:0%;background:linear-gradient(90deg,var(--gold),var(--gold3))"></div></div>
    <div style="display:flex;justify-content:space-between;margin-top:5px">
      <span style="font-size:10px;color:var(--muted)">0 PASSER</span>
      <span style="font-size:10px;color:var(--amber)">55 PRUDENCE</span>
      <span style="font-size:10px;color:var(--green)">75+ GO</span>
    </div>
  </div>

  <div id="verdict-box" class="verdict" style="background:var(--card);border-color:var(--border)">
    <div class="verdict-t" id="v-title">Remplis le modèle</div>
    <div class="verdict-d" id="v-detail">Commence par les 6 filtres bloquants. Un seul KO annule le pari.</div>
  </div>

  <div class="card ag">
    <div class="ct">📝 Match à analyser</div>
    <div style="display:grid;grid-template-columns:1fr 1fr;gap:8px;margin-bottom:8px">
      <input class="inp" id="m-home" placeholder="Équipe domicile">
      <input class="inp" id="m-away" placeholder="Équipe extérieur">
    </div>
    <div style="display:grid;grid-template-columns:1fr 1fr 1fr;gap:8px">
      <input class="inp" id="m-date" type="date">
      <input class="inp" id="m-cote" placeholder="Cote (1.75)" type="number" step="0.01">
      <input class="inp" id="m-mise" placeholder="Mise (F)" type="number">
    </div>
  </div>

  <div class="card">
    <div class="sec-hdr">
      <div class="ct" style="margin:0">🚫 Filtres bloquants — 1 KO = annulé</div>
      <span id="b-status" class="tag ta">? / 6</span>
    </div>
    <div id="bl-list"></div>
  </div>

  <div class="card">
    <div class="sec-hdr"><div class="ct" style="margin:0">⚡ Forme récente</div><span class="sec-pts">/ 25 pts</span></div>
    <div id="s-forme"></div>
  </div>
  <div class="card">
    <div class="sec-hdr"><div class="ct" style="margin:0">⚔️ Confrontations directes</div><span class="sec-pts">/ 15 pts</span></div>
    <div id="s-h2h"></div>
  </div>
  <div class="card">
    <div class="sec-hdr"><div class="ct" style="margin:0">👥 Effectif & disponibilité</div><span class="sec-pts">/ 20 pts</span></div>
    <div id="s-eff"></div>
  </div>
  <div class="card">
    <div class="sec-hdr"><div class="ct" style="margin:0">🎯 Contexte & motivation</div><span class="sec-pts">/ 20 pts</span></div>
    <div id="s-ctx"></div>
  </div>
  <div class="card">
    <div class="sec-hdr"><div class="ct" style="margin:0">📊 Cote & marché</div><span class="sec-pts">/ 20 pts</span></div>
    <div id="s-mkt"></div>
  </div>

  <div style="display:flex;gap:8px;flex-wrap:wrap;margin-bottom:16px">
    <button class="btn-gold" onclick="savePari()">💾 Enregistrer</button>
    <button class="btn-ghost" onclick="resetAnalyse()">🔄 Réinitialiser</button>
  </div>
</div>

<!-- HISTORIQUE -->
<div id="pg-historique" style="display:none">
  <div class="stat-grid" style="margin-bottom:10px">
    <div class="stat-card"><div class="stat-val" id="h-total">0</div><div class="stat-lbl">Paris enregistrés</div></div>
    <div class="stat-card"><div class="stat-val" id="h-roi">—</div><div class="stat-lbl">ROI total</div></div>
    <div class="stat-card"><div class="stat-val" id="h-wins" style="color:var(--green)">0</div><div class="stat-lbl">Gagnés</div></div>
    <div class="stat-card"><div class="stat-val" id="h-losses" style="color:var(--red)">0</div><div class="stat-lbl">Perdus</div></div>
  </div>
  <div class="card"><div class="ct">📋 Historique des paris</div><div id="hist-list"><div style="color:var(--muted);font-size:12px;text-align:center;padding:20px 0">Aucun pari enregistré</div></div></div>
  <button class="btn-red" onclick="clearHistory()" style="width:100%;margin-top:4px">🗑 Effacer tout l'historique</button>
</div>

<!-- BANKROLL -->
<div id="pg-bankroll" style="display:none">
  <div class="card ag">
    <div class="ct">💰 Bankroll active</div>
    <div style="font-size:32px;font-weight:700;color:var(--gold);font-family:'DM Mono',monospace;margin-bottom:6px" id="bk-val">0 F</div>
    <div class="prog" style="height:8px"><div class="prog-fill" id="bk-bar" style="background:linear-gradient(90deg,var(--green),#2ecc8a80);width:0%"></div></div>
    <div style="font-size:11px;color:var(--text2);margin-top:6px" id="bk-sub">—</div>
  </div>
  <div class="card">
    <div class="ct">📐 Mises recommandées</div>
    <div class="bk-row"><span class="bk-lbl">Mise conservative (1%)</span><span class="bk-val" id="bk-1" style="color:var(--green)">—</span></div>
    <div class="bk-row"><span class="bk-lbl">Mise standard (2%)</span><span class="bk-val" id="bk-2" style="color:var(--gold)">—</span></div>
    <div class="bk-row"><span class="bk-lbl">Mise max absolue (3%)</span><span class="bk-val" id="bk-3" style="color:var(--amber)">—</span></div>
    <div class="bk-row"><span class="bk-lbl">⚠️ Seuil stop-loss (−20%)</span><span class="bk-val" id="bk-stop" style="color:var(--red)">—</span></div>
  </div>
  <div class="card">
    <div class="ct">⚙️ Mettre à jour</div>
    <div style="display:flex;gap:8px;margin-bottom:8px">
      <input class="inp" id="bk-inp" type="number" placeholder="Montant en F" style="flex:1">
      <button class="btn-gold" onclick="saveBankroll()">Valider</button>
    </div>
    <div style="display:flex;gap:8px;flex-wrap:wrap">
      <button class="btn-ghost" onclick="addBk(500)">+500</button>
      <button class="btn-ghost" onclick="addBk(1000)">+1 000</button>
      <button class="btn-ghost" onclick="addBk(2000)">+2 000</button>
      <button class="btn-ghost" onclick="addBk(5000)">+5 000</button>
      <button class="btn-red" onclick="addBk(-500)">−500</button>
      <button class="btn-red" onclick="addBk(-1000)">−1 000</button>
    </div>
  </div>
  <div class="card">
    <div class="ct">📜 Règles bankroll</div>
    <div class="rule"><div class="rule-ico">🔒</div><div><div class="rule-t">JAMAIS PLUS DE 3% PAR PARI</div><div class="rule-d">Peu importe la confiance. Non négociable.</div></div></div>
    <div class="rule"><div class="rule-ico">🛑</div><div><div class="rule-t">STOP-LOSS À −20%</div><div class="rule-d">Si la bankroll perd 20% : pause 30 jours minimum.</div></div></div>
    <div class="rule"><div class="rule-ico">🚫</div><div><div class="rule-t">ZÉRO RECHARGEMENT ÉMOTIONNEL</div><div class="rule-d">Après une perte, ne jamais recharger pour se refaire.</div></div></div>
    <div class="rule"><div class="rule-ico">📆</div><div><div class="rule-t">BILAN LE 1ER DU MOIS</div><div class="rule-d">Calculer ROI, analyser les perdus, ajuster le modèle.</div></div></div>
  </div>
</div>

<!-- RÈGLES -->
<div id="pg-regles" style="display:none">
  <div class="card" style="background:linear-gradient(135deg,#130b00,#080808);border:1px solid #3a2200;margin-bottom:10px">
    <div style="font-family:'DM Serif Display',serif;color:var(--gold3);font-size:18px;margin-bottom:6px">Manifeste du Stratège</div>
    <div style="font-size:12px;color:var(--text2);line-height:1.7">Ce modèle n'existe pas pour gagner chaque pari. Il existe pour ne jamais perdre le contrôle.</div>
  </div>
  <div class="card ag">
    <div class="ct">⚡ Les 8 commandements</div>
    <div class="rule"><div class="rule-ico">🎯</div><div><div class="rule-t">1–2 PARIS PAR SEMAINE MAX</div><div class="rule-d">Si aucun match ne dépasse 75/100 cette semaine → on ne parie pas.</div></div></div>
    <div class="rule"><div class="rule-ico">🚫</div><div><div class="rule-t">ZÉRO COMBINÉ</div><div class="rule-d">Les combinés multiplient l'espérance négative. Singles uniquement, à vie.</div></div></div>
    <div class="rule"><div class="rule-ico">📵</div><div><div class="rule-t">ZÉRO PARI LIVE</div><div class="rule-d">Le live est conçu pour l'impulsion. Aucun pari après le coup d'envoi.</div></div></div>
    <div class="rule"><div class="rule-ico">😴</div><div><div class="rule-t">JAMAIS SOUS ÉMOTION</div><div class="rule-d">Après victoire (euphorie) ou défaite (revanche) : pas de pari dans les 48h.</div></div></div>
    <div class="rule"><div class="rule-ico">📊</div><div><div class="rule-t">LE MODÈLE EST LA LOI</div><div class="rule-d">Ton instinct dit GO mais le score dit PASSER ? Tu passes. Sans exception.</div></div></div>
    <div class="rule"><div class="rule-ico">🏦</div><div><div class="rule-t">LA BANKROLL EST SACRÉE</div><div class="rule-d">Capital de travail, pas de l'argent de jeu. Géré comme un compte d'entreprise.</div></div></div>
    <div class="rule"><div class="rule-ico">📋</div><div><div class="rule-t">TOUT DOIT ÊTRE TRACÉ</div><div class="rule-d">Chaque pari dans l'historique. Chaque perte analysée. Pas de trace = pas de progrès.</div></div></div>
    <div class="rule"><div class="rule-ico">⏸️</div><div><div class="rule-t">LA PAUSE EST UNE VICTOIRE</div><div class="rule-d">Ne pas parier une semaine quand aucun match passe le filtre = discipline réelle.</div></div></div>
  </div>
  <div class="card">
    <div class="ct">📐 Ligues autorisées</div>
    <div class="rule"><div class="rule-ico">🇫🇷</div><div><div class="rule-t">LIGUE 1 — PRIORITÉ</div><div class="rule-d">Données accessibles, marché moins optimisé par les pros.</div></div></div>
    <div class="rule"><div class="rule-ico">🏴󠁧󠁢󠁥󠁮󠁧󠁿</div><div><div class="rule-t">CHAMPIONSHIP ANGLAIS</div><div class="rule-d">Volume élevé, patterns stables, bonne source de valeur.</div></div></div>
    <div class="rule"><div class="rule-ico">🇩🇪</div><div><div class="rule-t">BUNDESLIGA</div><div class="rule-d">La plus prévisible statistiquement. Favoris confirmés régulièrement.</div></div></div>
    <div class="rule"><div class="rule-ico">🚫</div><div><div class="rule-t">LIGUES INTERDITES</div><div class="rule-d">Coupes nationales · Sélections nationales · Ligues inférieures · Europa / Conference</div></div></div>
  </div>
  <div class="card">
    <div class="ct">📈 Objectif réaliste 12 mois</div>
    <div class="stat-grid">
      <div class="stat-card"><div class="stat-val" style="font-size:16px">5–8%</div><div class="stat-lbl">ROI cible annuel</div></div>
      <div class="stat-card"><div class="stat-val" style="font-size:16px">1–2</div><div class="stat-lbl">Paris/semaine max</div></div>
      <div class="stat-card"><div class="stat-val" style="font-size:16px">75+</div><div class="stat-lbl">Score minimum GO</div></div>
      <div class="stat-card"><div class="stat-val" style="font-size:16px">3%</div><div class="stat-lbl">Mise max / pari</div></div>
    </div>
  </div>
</div>

</div>

<script>
const BLOCKERS=[
  {id:'b1',label:"Cote comprise entre 1.55 et 2.20",sub:"En dehors = valeur trop faible ou risque trop élevé"},
  {id:'b2',label:"Pas un match de Coupe / élimination directe",sub:"Imprévisibilité maximale — favoris battus régulièrement"},
  {id:'b3',label:"Aucun match joué dans les 72h (les deux équipes)",sub:"Fatigue = sous-performance systématique"},
  {id:'b4',label:"Les deux équipes ont un enjeu réel dans ce match",sub:"Équipe déjà qualifiée ou reléguée = motivation nulle"},
  {id:'b5',label:"Blessés/suspendus vérifiés moins de 24h avant",sub:"Titulaire absent non confirmé = annulation automatique"},
  {id:'b6',label:"Mise ≤ 3% de la bankroll active",sub:"Gestion du capital non négociable"},
];
const CRIT={
  forme:[
    {id:'f1',label:"Victoires sur les 5 derniers matchs (toutes compétitions)",guide:"0–1 vic = 0 pt · 2–3 vic = 5 pts · 4–5 vic = 10 pts",max:10},
    {id:'f2',label:"Forme dom/ext selon contexte du match",guide:"0–1 vic sur 5 = 0 · 2–3 = 5 pts · 4–5 = 10 pts",max:10},
    {id:'f3',label:"Série invaincu en cours (3+ matchs)",guide:"Non = 0 pt · 3 matchs ou plus sans défaite = 5 pts",max:5},
  ],
  h2h:[
    {id:'h1',label:"Bilan H2H sur les 5 dernières rencontres",guide:"0–1 victoire = 0 · 2–3 = 5 pts · 4–5 = 10 pts",max:10},
    {id:'h2',label:"Victoire dans la dernière confrontation directe",guide:"Non = 0 pt · Oui = 5 pts",max:5},
  ],
  eff:[
    {id:'e1',label:"Titulaires clés disponibles (attaquants + milieux)",guide:"2+ absents clés = 0 · 1 absent clé = 5 · Tous dispo = 10 pts",max:10},
    {id:'e2',label:"Gardien titulaire confirmé",guide:"Non confirmé = 0 pt · Confirmé = 5 pts",max:5},
    {id:'e3',label:"Groupe stable (pas de rotation massive annoncée)",guide:"Forte rotation prévue = 0 · Équipe type = 5 pts",max:5},
  ],
  ctx:[
    {id:'c1',label:"Enjeu classement (top 4, maintien, titre)",guide:"Aucun enjeu = 0 · Enjeu modéré = 5 · Enjeu vital = 10 pts",max:10},
    {id:'c2',label:"Moral collectif (presse + déclarations coach)",guide:"Mauvais = 0 · Neutre = 3 · Positif = 5 pts",max:5},
    {id:'c3',label:"Avantage domicile confirmé (stats dom > 55% victoires)",guide:"Non = 0 pt · Confirmé statistiquement = 5 pts",max:5},
  ],
  mkt:[
    {id:'m1',label:"Mouvement de cote favorable (stable ou en baisse)",guide:"Cote montante = 0 · Stable = 5 · Baisse notable = 10 pts",max:10},
    {id:'m2',label:"Accord entre 3+ bookmakers sur le favori",guide:"Désaccord = 0 pt · Accord de 3 bookmakers ou plus = 5 pts",max:5},
    {id:'m3',label:"Valeur positive estimée (ta proba > proba implicite cote)",guide:"Non = 0 pt · Oui clairement identifiée = 5 pts",max:5},
  ]
};
const ALL_C=[...CRIT.forme,...CRIT.h2h,...CRIT.eff,...CRIT.ctx,...CRIT.mkt];

const gs=(k,d)=>{try{const v=localStorage.getItem(k);return v!==null?JSON.parse(v):d;}catch{return d;}};
const ss=(k,v)=>{try{localStorage.setItem(k,JSON.stringify(v));}catch{}};
let S={bl:gs('st_bl',{}),sc:gs('st_sc',{}),bk:gs('st_bk',10000),hist:gs('st_hist',[])};
const save=()=>{ss('st_bl',S.bl);ss('st_sc',S.sc);ss('st_bk',S.bk);ss('st_hist',S.hist);};
const fmt=n=>new Intl.NumberFormat('fr-FR').format(Math.round(n))+' F';

function go(p){
  ['analyse','historique','bankroll','regles'].forEach(id=>document.getElementById('pg-'+id).style.display=id===p?'':'none');
  document.querySelectorAll('.tab').forEach((b,i)=>b.classList.toggle('on',['analyse','historique','bankroll','regles'][i]===p));
  if(p==='historique')renderHist();
  if(p==='bankroll')renderBk();
}

function renderBlockers(){
  const el=document.getElementById('bl-list');el.innerHTML='';
  BLOCKERS.forEach(b=>{
    const v=S.bl[b.id];
    const div=document.createElement('div');div.className='bl-row';
    div.innerHTML=`<div class="bl-info"><div class="bl-label">${b.label}</div><div class="bl-sub">${b.sub}</div></div><button class="tog ${v===true?'ok':v===false?'ko':''}" id="tog-${b.id}" onclick="togBl('${b.id}')">${v===true?'OK':v===false?'KO':'?'}</button>`;
    el.appendChild(div);
  });
  updBlStatus();
}

function togBl(id){
  const cur=S.bl[id];
  S.bl[id]=cur===undefined||cur===null?true:cur===true?false:null;
  save();
  const v=S.bl[id];
  const btn=document.getElementById('tog-'+id);
  btn.className='tog'+(v===true?' ok':v===false?' ko':'');
  btn.textContent=v===true?'OK':v===false?'KO':'?';
  btn.classList.add('pop');setTimeout(()=>btn.classList.remove('pop'),250);
  updBlStatus();calc();
}

function updBlStatus(){
  const ko=Object.values(S.bl).filter(v=>v===false).length;
  const ok=Object.values(S.bl).filter(v=>v===true).length;
  const el=document.getElementById('b-status');
  el.textContent=ok+' / '+BLOCKERS.length;
  el.className='tag '+(ko>0?'tr':ok===BLOCKERS.length?'tg':'ta');
}

function renderSections(){
  [
    {key:'forme',id:'s-forme'},{key:'h2h',id:'s-h2h'},
    {key:'eff',id:'s-eff'},{key:'ctx',id:'s-ctx'},{key:'mkt',id:'s-mkt'}
  ].forEach(sec=>{
    const el=document.getElementById(sec.id);el.innerHTML='';
    CRIT[sec.key].forEach(c=>{
      const val=S.sc[c.id]||0;
      const pct=Math.min((val/c.max)*100,100);
      const div=document.createElement('div');div.className='sc-row';
      div.innerHTML=`<div class="sc-info"><div class="sc-label">${c.label}</div><div class="sc-guide">${c.guide}</div><div class="prog"><div class="prog-fill" id="pr-${c.id}" style="width:${pct}%;background:var(--gold)"></div></div></div><div class="sc-ctrl"><button class="sc-btn" onclick="adj('${c.id}',-1)">−</button><span class="sc-val" id="sv-${c.id}">${val}</span><button class="sc-btn" onclick="adj('${c.id}',1)">+</button><span class="sc-max">/${c.max}</span></div>`;
      el.appendChild(div);
    });
  });
}

function adj(id,d){
  const c=ALL_C.find(x=>x.id===id);
  S.sc[id]=Math.max(0,Math.min(c.max,(S.sc[id]||0)+d));
  save();
  document.getElementById('sv-'+id).textContent=S.sc[id];
  document.getElementById('pr-'+id).style.width=Math.min((S.sc[id]/c.max)*100,100)+'%';
  calc();
}

function calc(){
  const ko=Object.values(S.bl).filter(v=>v===false).length;
  const pend=Object.values(S.bl).filter(v=>v===null||v===undefined).length;
  const unkn=BLOCKERS.filter(b=>S.bl[b.id]===undefined).length;
  const score=Math.min(ALL_C.reduce((s,c)=>s+(S.sc[c.id]||0),0),100);
  document.getElementById('k-score').textContent=score;
  document.getElementById('k-block').textContent=ko;
  document.getElementById('k-score-txt').textContent=score+' / 100';
  const bar=document.getElementById('score-bar');
  bar.style.width=score+'%';
  bar.style.background=score>=75?'linear-gradient(90deg,var(--green),#2ecc8a80)':score>=55?'linear-gradient(90deg,var(--amber),#e0962a80)':'linear-gradient(90deg,var(--gold),var(--gold3))';
  let vk,vt,vd,bg,bc;
  if(ko>0){vk='KO';vt='Pari annulé — filtre bloquant actif';vd=ko+' filtre(s) KO. Ce pari ne se prend pas.';bg='#7a202015';bc='#e05c5c40';}
  else if(pend>0||unkn>0){vk='?';vt='Filtres incomplets';vd='Valide d\'abord tous les filtres bloquants.';bg='var(--card)';bc='var(--border)';}
  else if(score>=75){vk='GO';vt='Signal fort — pari validé';vd='Score '+score+'/100. Tous les filtres validés. Mise : 2–3% bankroll maximum. Zéro combiné.';bg='#1a7a5315';bc='#2ecc8a40';}
  else if(score>=55){vk='⚠️';vt='Signal modéré — mise réduite';vd='Score '+score+'/100. Pari possible avec prudence. Mise max : 1% bankroll.';bg='#7a4f1015';bc='#e0962a40';}
  else{vk='PASS';vt='Signal insuffisant — passer';vd='Score '+score+'/100. Pas assez d\'éléments. Attends un meilleur profil.';bg='#7a202015';bc='#e05c5c40';}
  document.getElementById('k-verdict').textContent=vk;
  document.getElementById('v-title').textContent=vt;
  document.getElementById('v-detail').textContent=vd;
  const box=document.getElementById('verdict-box');
  box.style.background=bg;box.style.borderColor=bc;
}

function savePari(){
  const home=document.getElementById('m-home').value.trim();
  const away=document.getElementById('m-away').value.trim();
  if(!home||!away){alert('Remplis les noms des équipes.');return;}
  const ko=Object.values(S.bl).filter(v=>v===false).length;
  const score=Math.min(ALL_C.reduce((s,c)=>s+(S.sc[c.id]||0),0),100);
  const verdict=ko>0?'KO':score>=75?'GO':score>=55?'PRUDENCE':'PASSER';
  S.hist.unshift({
    home,away,
    date:document.getElementById('m-date').value,
    cote:parseFloat(document.getElementById('m-cote').value)||0,
    mise:parseFloat(document.getElementById('m-mise').value)||0,
    score,verdict,result:null,ts:Date.now()
  });
  save();alert('Pari enregistré ! Va dans Historique pour marquer le résultat.');
}

function resetAnalyse(){
  S.bl={};S.sc={};save();
  renderBlockers();renderSections();calc();
  ['m-home','m-away','m-cote','m-mise'].forEach(id=>document.getElementById(id).value='');
  document.getElementById('m-date').value='';
}

function renderHist(){
  const el=document.getElementById('hist-list');
  if(!S.hist.length){el.innerHTML='<div style="color:var(--muted);font-size:12px;text-align:center;padding:20px 0">Aucun pari enregistré</div>';document.getElementById('h-total').textContent=0;document.getElementById('h-roi').textContent='—';document.getElementById('h-wins').textContent=0;document.getElementById('h-losses').textContent=0;return;}
  el.innerHTML='';
  let wins=0,losses=0,totMise=0,totRetour=0;
  S.hist.forEach((p,i)=>{
    const div=document.createElement('div');div.className='hist-row';
    const rTag=p.result===null?`<span class="tag ta" style="cursor:pointer" onclick="setResult(${i})">? résultat</span>`:p.result?'<span class="tag tg">✓ Gagné</span>':'<span class="tag tr">✗ Perdu</span>';
    const gain=p.result===true&&p.mise&&p.cote?'+'+Math.round(p.mise*(p.cote-1))+' F':p.result===false&&p.mise?'−'+p.mise+' F':p.mise?p.mise+' F':'—';
    const gc=p.result===true?'var(--green)':p.result===false?'var(--red)':'var(--muted)';
    div.innerHTML=`<div style="flex:1;min-width:0"><div style="font-size:13px;font-weight:600">${p.home} vs ${p.away}</div><div style="margin-top:3px;display:flex;gap:6px;align-items:center;flex-wrap:wrap"><span class="tag ${p.verdict==='GO'?'tg':p.verdict==='PRUDENCE'?'ta':'tr'}">${p.score}/100</span>${rTag}${p.date?'<span style="font-size:10px;color:var(--muted)">'+p.date+'</span>':''}</div></div><div style="text-align:right;flex-shrink:0"><div style="font-size:12px;font-weight:700;font-family:\'DM Mono\',monospace;color:${gc}">${gain}</div>${p.cote?'<div style="font-size:10px;color:var(--muted)">@'+p.cote+'</div>':''}</div>`;
    el.appendChild(div);
    if(p.result===true){wins++;totMise+=p.mise||0;totRetour+=(p.mise||0)*(p.cote||1);}
    if(p.result===false){losses++;totMise+=p.mise||0;}
  });
  document.getElementById('h-total').textContent=S.hist.length;
  document.getElementById('h-wins').textContent=wins;
  document.getElementById('h-losses').textContent=losses;
  const roi=totMise>0?Math.round(((totRetour-totMise)/totMise)*100):null;
  const re=document.getElementById('h-roi');
  re.textContent=roi!==null?roi+'%':'—';
  re.style.color=roi>0?'var(--green)':roi<0?'var(--red)':'var(--text2)';
}

function setResult(i){
  const r=confirm(S.hist[i].home+' vs '+S.hist[i].away+'\n\nTu as GAGNÉ ce pari ?');
  S.hist[i].result=r;save();renderHist();
}

function clearHistory(){
  if(confirm('Effacer tout l\'historique ? Irréversible.')){S.hist=[];save();renderHist();}
}

function renderBk(){
  const bk=S.bk;
  const start=gs('st_bk_start',bk);
  document.getElementById('bk-val').textContent=fmt(bk);
  document.getElementById('bk-bar').style.width=Math.min((bk/start)*100,100)+'%';
  document.getElementById('bk-sub').textContent='Capital initial : '+fmt(start);
  document.getElementById('bk-1').textContent=fmt(bk*0.01);
  document.getElementById('bk-2').textContent=fmt(bk*0.02);
  document.getElementById('bk-3').textContent=fmt(bk*0.03);
  document.getElementById('bk-stop').textContent=fmt(bk*0.8)+' (seuil)';
}

function saveBankroll(){
  const v=parseFloat(document.getElementById('bk-inp').value);
  if(!v||v<=0)return;
  ss('st_bk_start',v);S.bk=v;save();renderBk();document.getElementById('bk-inp').value='';
}

function addBk(n){S.bk=Math.max(0,S.bk+n);save();renderBk();}

renderBlockers();renderSections();calc();
</script>
</body>
</html>
