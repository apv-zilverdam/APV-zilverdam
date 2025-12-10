<!DOCTYPE html>
<html lang="nl">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Regelboek</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #0f0f0f;
      color: white;
      display: flex;
    }
    .sidebar {
      width: 260px;
      background: rgba(20,20,20,0.95);
      padding: 20px;
      border-right: 2px solid #222;
      position: fixed;
      height: 100vh;
      overflow-y: auto;
    }
    .sidebar h2 {
      margin-top: 0;
      font-size: 22px;
      letter-spacing: 1px;
    }
    .sidebar button {
      width: 100%;
      padding: 10px;
      margin: 6px 0;
      background: #1c1c1c;
      border: 1px solid #333;
      color: white;
      cursor: pointer;
    }
    .sidebar button:hover {
      background: #333;
    }

    .content {
      margin-left: 280px;
      padding: 20px 40px;
      width: 100%;
    }

    .logo {
      width: 100%;
      margin-bottom: 20px;
    }

    .ruleblock {
      display: none;
      background: rgba(255,255,255,0.04);
      padding: 20px;
      border-radius: 8px;
      margin-bottom: 30px;
      border: 1px solid rgba(255,255,255,0.1);
    }

    h1 {
      font-size: 28px;
      border-bottom: 2px solid #444;
      padding-bottom: 10px;
      margin-bottom: 20px;
    }

    h3 {
      margin-top: 25px;
    }
  </style>
</head>
<body>
  <div class="sidebar">
    <img class="logo" src="LOGO_HIER.png" />
    <h2>Regelmenu</h2>
    <button onclick="show('straffen')">Straffen</button>
    <button onclick="show('algemeen')">Algemene Regels</button>
    <button onclick="show('overheid')">Overheidsregels</button>
    <button onclick="show('onderwereld')">Onderwereld</button>
  </div>

  <div class="content">

    <!-- STRAFFEN -->
    <div id="straffen" class="ruleblock">
      <h1>Straffen</h1>
      <p>
        Cat 0 – Ongeldig scenario / waarschuwing<br>
        Cat 1 – Mondelinge waarschuwing<br>
        Cat 2 – Kick / waarschuwing<br>
        Cat 3 – 12 uur ban<br>
        Cat 4 – 24 uur ban<br>
        Cat 5 – 48 uur ban<br>
        Cat 6 – 72 uur ban<br>
        Cat 7 – 7 dagen ban<br>
        Cat 8 – 14 dagen ban<br>
        Cat 9 – Permanente ban mogelijk<br>
        Cat 10 – Direct permanente ban
      </p>
    </div>

    <!-- ALGEMENE REGELS -->
    <div id="algemeen" class="ruleblock">
      <h1>Algemene Regels</h1>

      <h3>Gedrag en Communicatie</h3>
      <p>
Art 1 – Respect — Straf: Cat. 1 / Cat. 4<br>
Art 2 – Taalgebruik (NL verplicht) — Straf: Cat. 1<br>
Art 3 – Overlast — Straf: Cat. 4<br>
Art 4 – Spammen / Onzin-reports — Straf: Cat. 2<br>
Art 5 – OOC praten — Straf: Cat. 2
      </p>

      <h3>Roleplay</h3>
      <p>
Art 6 – Fail RP — Straf: Cat. 5<br>
Art 7 – Verstoren RP — Straf: Cat. 3<br>
Art 8 – Metagaming — Straf: Cat. 4<br>
Art 9 – Streamsniping — Straf: Cat. 6<br>
Art 10 – NLR — Straf: Cat. 4<br>
Art 11 – NVOL — Straf: Cat. 6<br>
Art 12 – RDM — Straf: Cat. 5<br>
Art 13 – VDM — Straf: Cat. 4<br>
Art 14 – Combat-logout — Straf: Cat. 4 + wapen inleveren<br>
Art 15 – Combat-stash — Straf: Cat. 3 + wapen inleveren
      </p>

      <h3>Economie & Items</h3>
      <p>
Art 16 – Scammen — Cat. 4 + teruggeven<br>
Art 17 – IRL-Trading — Cat. 10<br>
Art 18 – Overheidskleding — Cat. 3<br>
Art 19 – Impersonatie overheid — Cat. 3<br>
Art 20 – Copbaiting — Cat. 3
      </p>

      <h3>Hulpdiensten & Veiligheid</h3>
      <p>
Art 21 – Ambulance aanvallen/gijzelen — Cat. 5<br>
Art 22 – Staff-imper — Cat. 5<br>
Art 23 – Microfoon verplicht — Cat. 1
      </p>

      <h3>Technisch</h3>
      <p>
Art 24 – Cheats — Cat. 10<br>
Art 25 – Exploits — Cat. 5 / Cat. 10
      </p>

      <h3>Communicatie & Media</h3>
      <p>
Art 26 – Discord RP — Cat. 5<br>
Art 27 – Twitter misbruik — Cat. 2
      </p>

      <h3>Voertuigen & Rijden</h3>
      <p>
Art 28 – Gebouwen inrijden — Cat. 3<br>
Art 29 – Basic outfit — Cat. 2<br>
Art 30 – GTA-style driving — Cat. 1 / Cat. 2<br>
Art 31 – Refund regels<br>
Art 32 – Donatie-auto’s niet verkopen — Cat. 4
      </p>

      <h3>Overig</h3>
      <p>
Art 33 – Bodylooten — Cat. 3<br>
Art 34 – Afmaken — Cat. 3<br>
Art 35 – Uit auto schieten — Cat. 2<br>
Art 36 – Ziekte schelden — Cat. 4<br>
Art 37 – Lieg tegen staff — Cat. 5<br>
Art 38 – Stemherkenning — Cat. 3<br>
Art 39 – Wachtkamer misbruik — Cat. 0<br>
Art 40 – Gangkleding — verboden
      </p>
    </div>

    <!-- OVERHEID -->
    <div id="overheid" class="ruleblock">
      <h1>Overheidsregels</h1>
      <p>
OH 1 – Hostages & eisen<br>
OH 2 – Verboden eisen<br>
OH 3 – Huiszoekingen (50%)<br>
OH 4 – Pit actie regels<br>
OH 5 – Ganginvallen<br>
OH 6 – Advocaten regels<br>
OH 7 – Combat gedrag<br>
OH 8 – Combat rollen<br>
OH 9 – Aanhoudingen<br>
OH 10 – Proportionaliteit
      </p>
    </div>

    <!-- ONDERWERELD -->
    <div id="onderwereld" class="ruleblock">
      <h1>Onderwereld Regels</h1>
      <p>
OW 1 – Rippen regels<br>
OW 2 – Hostages<br>
OW 3 – Ganginvallen<br>
OW 4 – Eiland<br>
OW 5 – Benen (10 sec)<br>
OW 6 – Banden schieten<br>
OW 7 – Gangs max 20<br>
OW 8 – Counteren<br>
OW 9 – Terug-rippen binnen 30m<br>
OW 10 – Hit & Run 10 min stay<br>
OW 11 – Verkoop/pluk/verpak risico<br>
OW 12 – Gijzelen op hulpdiensten<br>
OW 13 – Setups 5 min<br>
OW 14 – Hostage minima
      </p>
    </div>

  </div>

  <script>
    function show(id) {
      document.querySelectorAll('.ruleblock').forEach(el => el.style.display = 'none');
      document.getElementById(id).style.display = 'block';
    }
  </script>
</body>
</html>
