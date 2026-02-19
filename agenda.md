---
title: Agenda
menu_title: Agenda
menu_icon: clock
---

<style>
  .agenda-grid {
    width: 100%;
    border-collapse: collapse;
    font-size: 14px;
    table-layout: fixed;
  }

  .agenda-grid td,
  .agenda-grid th {
    border: 1px solid #999;
    padding: 6px 8px;
    vertical-align: middle;
    box-sizing: border-box;
  }

  /* Allow long titles to wrap correctly */
  .agenda-grid td {
    white-space: normal;
    word-break: normal;
    overflow-wrap: break-word;
  }


  /* Keep time columns on one line */
  .agenda-grid td:nth-child(1),
  .agenda-grid td:nth-child(2) {
    white-space: nowrap;
  }

  /* Header and row colors */
  .dayhdr { background:#eee; font-weight:bold; }

  .purple { background:#9b00ff; font-weight:bold; text-align:center; color:#000; }
  .cyan { background:#00f0f0; font-weight:bold; }
  .lightblue { background:#d6e4ff; }
  .yellow { background:#f6e9b6; }
  .softgray { background:#f5f5f5; }
  .lightgreen { background:#dff3df; }

  /* Force color onto TDs (important for table-layout:fixed) */
  .agenda-grid tr.cyan td { background:#00f0f0; }
  .agenda-grid tr.yellow td { background:#f6e9b6; }
  .agenda-grid tr.lightblue td { background:#d6e4ff; }
  .agenda-grid tr.purple td { background:#9b00ff; color:#000; }
  .agenda-grid tr.softgray td { background:#f5f5f5; }
  .agenda-grid tr.lightgreen td { background:#dff3df; }

  .center { text-align:center; }

  .green, .blue, .red {
    color:#000;
    font-weight:700;
  }
</style>

<table class="agenda-grid">

<colgroup>
  <col style="width:10%">
  <col style="width:10%">
  <col style="width:15%">
  <col style="width:15%">
  <col style="width:15%">
  <col style="width:15%">
  <col style="width:10%">
  <col style="width:10%">
</colgroup>



  <!-- ===================== DAY 1 ===================== -->
  <tr class="dayhdr">
    <td colspan="8"><strong>Day 1 — Feb 19, 2026</strong></td>
  </tr>

  <tr>
    <td>7:30 AM</td><td>8:30 AM</td>
    <td colspan="6">
      <strong>Registration and Beakfast</strong>
    </td>
  </tr>

  <tr>
    <td>8:30 AM</td><td>8:45 AM</td>
    <td colspan="6">Welcome and Introductions: <strong>Anthony Maciejewski</strong> (DD ECCS), NSF Program Directors</td>
  </tr>

  <tr>
    <td>8:45 AM</td><td>9:00 AM</td>
    <td colspan="6">Workshop Overview: <strong>Sergei V. Kalinin</strong></td>
  </tr>

  <tr class="yellow">
    <td rowspan="3">9:00 AM</td>
    <td rowspan="3">10:00 AM</td>
    <td colspan="4"><strong>Session 1: Opening and Vision</strong></td>
    <td class="center green" colspan="2">Chair: Adina Luican-Mayer</td>
  </tr>

  <tr>
    <td colspan="2">Speaker 1: 9:00 AM – 9:30 AM</td>
    <td colspan="4"><strong>David Awschalom</strong>: Emerging opportunities with quantum-engineered semiconductors<br> and molecules</td>
    <td colspan="2"></td>
  </tr>

  <tr>
    <td colspan="2">Speaker 2: 9:30 AM – 10:00 AM</td>
    <td colspan="4"><strong>Susanne Stemmer</strong>: Topological materials for quantum information systems</td>
    <td colspan="2"></td>
  </tr>

  <tr class="lightblue">
    <td>10:00 AM</td><td>10:30 AM</td>
    <td colspan="6">Coffee Break</td>
  </tr>


  <tr class="yellow">
    <td rowspan="4">10:30 AM</td><td rowspan="4">12:00 PM</td>
    <td colspan="4"><strong>Session 2: Quantum from Semiconductor and Molecular Perspectives</strong></td>
    <td class="center green" colspan="2">Chair: Shashank Misra</td>
  </tr>

  <tr>
    <td colspan="2">Speaker 3: 10:30 AM – 11:00 AM</td>
    <td colspan="4"><strong>Michael R Wasielewski</strong>: Exploiting Molecules and Molecular Materials for Quantum<br> Information Science</td>
    <td colspan="2"></td>
  </tr>

  <tr>
    <td colspan="2">Speaker 4: 11:00 AM – 11:30 AM</td>
    <td colspan="4"><strong>John Randall</strong> / <strong>James Owen</strong>: Scaling throughput of Atomically-Precise Lithography<br> for APAM and other Quantum Devices</td>
    <td colspan="2"></td>
  </tr>

  <tr>
    <td colspan="2">Speaker 5: 11:30 AM – 12:00 PM</td>
    <td colspan="4"><strong>Oleg Gang</strong>: Towards 3D Nanofabrication through Programmable Self-Assembly</td>
    <td colspan="2"></td>
  </tr>

  <tr class="lightblue">
      <td>12:00 PM</td><td>1:00 PM</td>
      <td colspan="6"><strong>Lunch/Yves Idzerda</strong>: Transitioning 2D Technologies at the MonArk Quantum Foundry</td>
  </tr>

  <!-- Breakout Sessions (Day 1) -->
  <tr class="purple">
    <td colspan="8"><strong>Breakout Sessions</strong></td>
  </tr>

  <tr class="center softgray">
    <td></td>
    <td>1:00 PM</td><td>2:30 PM</td>
    <td>1:00 PM</td><td>2:30 PM</td>
    <td>1:00 PM</td><td>2:30 PM</td>
    <td></td>
  </tr>

  <tr class="center">
    <td></td>
    <td colspan="2" class="yellow"><strong>Breakout 1:</strong> Photonic Sensing and<br> Integration</td>
    <td colspan="2" class="lightgreen"><strong>Breakout 2:</strong> Soft Quantum Matter</td>
    <td colspan="2" class="lightblue"><strong>Breakout 3:</strong> AI for Molecular Discovery and Automated Synthesis</td>
    <td></td>
  </tr>

  <tr class="center">
    <td></td>
    <td colspan="2">Chair: <strong>Dmitri Basov</strong></td>
    <td colspan="2">Chair: <strong>Ulrich Wiesner</strong></td>
    <td colspan="2">Chair: <strong>Aram Amassian</strong></td>
    <td></td>
  </tr>

  <tr class="lightblue">
    <td>2:30 PM</td><td>3:00 PM</td>
    <td colspan="6">Coffee Break</td>
  </tr>

  <tr class="yellow">
    <td rowspan="5">3:00 PM</td><td rowspan="5">4:00 PM</td>
    <td colspan="4"><strong>Session 3: Industry and National Labs</strong></td>
    <td class="center green" colspan="2">Chair: Jeremy Levy</td>
  </tr>

  <tr>
    <td colspan="2">Speaker 1: 3:00 PM – 3:15 PM</td>
    <td colspan="4"><strong>David Menasche</strong>: Quantum technology: industry watch</td>
  </tr>

  <tr>
    <td colspan="2">Speaker 2: 3:15 PM – 3:30 PM</td>
    <td colspan="4"><strong>Kevin Roccapriore</strong>: Deterministic atomic engineering with electron<br> beams at scale</td>
  </tr>

  <tr>
    <td colspan="2">Speaker 3: 3:30 PM – 3:45 PM</td>
    <td colspan="4"><strong>Vivien Zapf</strong>: Quantum information and molecular magnetism</td>
  </tr>

  <tr>
    <td colspan="2">Speaker 4: 3:45 PM – 4:00 PM</td>
    <td colspan="4"><strong>Dusan Vobornik</strong>: Inverted-Mode Scanning Tunneling <br>Microscopy for Atomically Precise Fabrication</td>
  </tr>

  <tr class="yellow">
    <td rowspan="5">4:10 PM</td><td rowspan="5">5:30 PM</td>
    <td colspan="4"><strong>Session 4: Integration between molecules and semiconductors</strong></td>
    <td class="center green" colspan="2">Chair: Vincent Meunier</td>
  </tr>

  <tr>
    <td colspan="2">Speaker 1: 4:10 PM – 4:30 PM</td>
    <td colspan="4"><strong>Ulrich Wiesner</strong>: The Promise of Soft Matter enabled Quantum Devices</td>
  </tr>

  <tr>
    <td colspan="2">Speaker 2: 4:30 PM – 4:50 PM</td>
    <td colspan="4"><strong>Dmitri Basov</strong>: Hyperbolic Materials for Quantum Information Science<br> and Technology</td>
  </tr>

  <tr>
    <td colspan="2">Speaker 3: 4:50 PM – 5:10 PM</td>
    <td colspan="4"><strong>Aram Amassian</strong>: Illuminating Process Histories: Uncovering <br>Process–Structure–Property Causality via In‑Situ and <br>Multi‑Modal Characterization in Self‑Driving Labs</td>
  </tr>

  <tr>
    <td colspan="2">Speaker 4: 5:10 PM – 5:30 PM</td>
    <td colspan="4"><strong>Peter Maurer</strong>: From diamond to proteins qubits</td>
  </tr>

  <tr class = "lightblue">
    <td>6:00 PM</td><td>8:00 PM</td>
    <td colspan="6"><strong>Dinner/Dinner Keynote: </strong><strong>Rahul Sarpeshkar</strong>: Analog and Probabilistic Computers: From Quantum Atom To Living Body</td>
  </tr>

  <!-- spacer -->
  <tr><td colspan="8" style="border:none;height:14px;"></td></tr>

  <!-- ===================== DAY 2 ===================== -->
  <tr class="dayhdr">
    <td colspan="8"><strong>Day 2 — Feb 20, 2026</strong></td>
  </tr>

  <tr>
    <td>7:30 AM</td><td>8:20 AM</td>
    <td colspan="6"><strong>Registration and Beakfast</strong></td>
  </tr>

  <tr class="yellow">
    <td rowspan="6">8:20 AM</td><td rowspan="6">10:00 AM</td>
    <td colspan="4"><strong>Session 5: Silicon for Quantum and Novel Semiconductor Functionalities</strong></td>
    <td class="center green" colspan="2">Chair: Robert Butera</td>
  </tr>

  <tr>
    <td colspan="2">Speaker 1: 8:20 AM – 8:40 AM</td>
    <td colspan="4"><strong>Shashank Misra</strong>: Why is silicon quantum computing taking so long?</td>
  </tr>

  <tr>
    <td colspan="2">Speaker 2: 8:40 AM – 9:00 AM</td>
    <td colspan="4"><strong>Marco Loncar</strong>: Quantum Optical Interconnects</td>
  </tr>

  <tr>
    <td colspan="2">Speaker 3: 9:00 AM – 9:20 AM</td>
    <td colspan="4"><strong>Gregory David Fuchs</strong>: Quantum sensing and quantum magnonics using diamond<br> spins and vanadium tetracyanoethylene</td>
  </tr>

  <tr>
    <td colspan="2">Speaker 4: 9:20 AM – 9:40 AM</td>
    <td colspan="4"><strong>Michael Manfra</strong>: Quantum Devices Enabled with Hybrid<br> Superconductor-Semiconductor Heterostructures</td>
  </tr>

  <tr>
    <td colspan="2">Speaker 5: 9:40 AM – 10:00 AM</td>
    <td colspan="4"><strong>Xiuling Li</strong>: Quantum Sensing with Spin Defects in III-Nitrides</td>
  </tr>

  <tr class="lightblue">
    <td>10:00 AM</td><td>10:20 AM</td>
    <td colspan="6">Coffee Break</td>
  </tr>

  <tr class="yellow">
    <td rowspan="6">10:20 AM</td><td rowspan="6">12:00 PM</td>
    <td colspan="4"><strong>Session 6: Molecules and AI assisted synthesis</strong></td>
    <td class="center green" colspan="2">Chair: Benjamin Lawrie</td>
  </tr>

  <tr>
    <td colspan="2">Speaker 1: 10:20 AM – 10:40 AM</td>
    <td colspan="4"><strong>Danna Freedman</strong>: Molecular Color Centers</td>
  </tr>

  <tr>
    <td colspan="2">Speaker 2: 10:40 AM – 11:00 AM</td>
    <td colspan="4">
    <strong>Marija Drndic</strong>: Coupled Nanopores for Sensing and Other Applications</td>
  </tr>

  <tr>
    <td colspan="2">Speaker 3: 11:00 AM – 11:20 AM</td>
    <td colspan="4"><strong>Masha Kamenetska</strong>: Quantum Properties of Molecular Circuits</td>
  </tr>

  <tr>
    <td colspan="2">Speaker 4: 11:20 AM – 11:40 AM</td>
    <td colspan="4"><strong>Justin Caram</strong>: Atomic physics in a beaker?</td>
  </tr>

  <tr>
    <td colspan="2">Speaker 5: 11:40 AM – 12:00 PM</td>
    <td colspan="4"><strong>Grigory Tikhomirov</strong>: Democratizing Nanofabrication of Quantum Systems<br> via Molecular Self-assembly</td>
  </tr>

  <tr class="lightblue">
    <td>12:10 PM</td><td>1:00 PM</td>
    <td colspan="6"><strong>Lunch/</strong><strong>Paul Weiss</strong>: Connecting and Quantifying Quantum Molecular and Hybrid Systems</td>
  </tr>

  <!-- Breakout Sessions (Day 2) -->
  <tr>
    <td></td>
    <td colspan="7" class="purple">Breakout Sessions</td>
  </tr>

  <tr class="center softgray">
    <td></td>
    <td>1:00 PM</td><td>2:30 PM</td>
    <td>1:00 PM</td><td>2:30 PM</td>
    <td>1:00 PM</td><td>2:30 PM</td>
    <td></td>
  </tr>

  <tr class="center">
    <td></td>
    <td colspan="2" class="yellow"><strong>Breakout 1</strong>: From direct Beam and Probe<br> Fabrication into semiconductor pipelines</td>
    <td colspan="2" class="lightgreen"><strong>Breakout 2</strong>: Molecular Building Blocks<br> and Hybrid Quantum Platforms</td>
    <td colspan="2" class="lightblue"><strong>Breakout 3</strong>: Scaffold-driven self-assembly<br> of quantum devices</td>
    <td></td>
  </tr>

  <tr class="center">
    <td></td>
    <td colspan="2">Chair: <strong>Robert Wolkow</strong> and <br><strong>Steven Spurgeon</strong></td>
    <td colspan="2">Chair: <strong>Marko Lončar</strong></td>
    <td colspan="2">Chair: <strong>Greg Tikhomirov</strong></td>
    <td></td>
  </tr>

  <tr class="lightblue">
    <td>2:30 PM</td><td>3:00 PM</td>
    <td colspan="6">Coffee Break</td>
  </tr>

  <tr class="yellow">
    <td rowspan="4">3:00 PM</td><td rowspan="4">4:00 PM</td>
    <td colspan="4"><strong>Session 7: Local Probing, Direct Atomic Fabrication Methods, and Integration into Classical Device Pipelines</strong></td>
    <td class="center green" colspan="2">Chair: Greg Fuchs</td>
  </tr>

  <tr>
    <td colspan="2">Speaker 1: 3:00 PM – 3:20 PM</td>
    <td colspan="4"><strong>Michael Flatte</strong>: Spatial Anisotropy of Acceptor Wave Functions in Silicon</td>
  </tr>

  <tr>
    <td colspan="2">Speaker 2: 3:20 PM – 3:40 PM</td>
    <td colspan="4"><strong>Adina Lucan-Maier</strong>: Quantum functionality of nanoscale-controlled 2D materials</td>
  </tr>

  <tr>
    <td colspan="2">Speaker 3: 3:40 PM – 4:00 PM</td>
    <td colspan="4"><strong>Robert Wolkow</strong>: Pico Perfect Placement</td>
  </tr>

</table>
