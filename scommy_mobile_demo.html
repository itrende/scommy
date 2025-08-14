<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1, maximum-scale=1, user-scalable=no" />
<title>Scommy – Mobile Demo</title>
<style>
  :root{--blue:#1E88E5;--lime:#C6FF00;--navy:#0D1B2A;--bg:#F5F8FA;--text:#1c2833;--muted:#7a8a9b;--radius:14px}
  *{box-sizing:border-box; -webkit-tap-highlight-color: transparent;}
  html,body{height:100%}
  body{margin:0;font-family:Inter, system-ui, -apple-system, Segoe UI, Roboto, Helvetica, Arial, "Noto Sans Thai", sans-serif;color:var(--text);background:var(--bg)}
  .app{display:flex;flex-direction:column;min-height:100%}
  header{background:#fff;border-bottom:1px solid #e6eef5;display:flex;align-items:center;gap:10px;padding:12px 14px;position:sticky;top:0;z-index:5}
  .brand{display:flex;align-items:center;gap:10px}
  .logo{width:34px;height:34px;border-radius:10px;background:linear-gradient(135deg,var(--blue),#3aa0ff);display:grid;place-items:center;color:#fff;font-weight:900}
  .title{line-height:1}
  .title b{font-size:16px}
  .title small{display:block;color:var(--muted);font-size:12px;margin-top:2px}

  /* content */
  .wrap{flex:1 1 auto;max-width:900px;margin:0 auto;padding:12px 12px 80px}
  .card{background:#fff;border:1px solid #e6eef5;border-radius:14px;padding:14px;margin:8px 0}
  .pill{display:inline-block;padding:6px 10px;background:#eef6ff;color:var(--blue);border-radius:999px;font-weight:600;font-size:12px}
  .btn{display:inline-flex;align-items:center;justify-content:center;gap:8px;border:none;background:var(--blue);color:#fff;padding:12px 14px;border-radius:12px;cursor:pointer;font-weight:700;min-height:44px}
  .btn.block{width:100%}
  .btn.lime{background:var(--lime);color:#0d1b2a}
  .row{display:grid;grid-template-columns:1fr;gap:10px}
  input,select{border:1px solid #e0e8ef;padding:12px;border-radius:12px;font-size:16px;min-height:44px;width:100%}
  .muted{color:var(--muted);font-size:13px}
  .list{display:grid;gap:10px}
  .item{display:flex;gap:10px;align-items:center;justify-content:space-between;padding:12px;border:1px solid #e6eef5;border-radius:12px;background:#fff}
  .item .meta{display:flex;flex-direction:column;gap:4px}
  h2,h3{margin:6px 0 10px 0}
  .kpis{display:grid;grid-template-columns:repeat(2,1fr);gap:8px}
  .kpis .card{padding:12px}

  /* booking grid */
  .slots{display:grid;grid-template-columns:1fr 1fr;gap:8px;margin-top:8px}
  .slot{border:1px solid #e6eef5;border-radius:12px;background:#fff;padding:10px;display:grid;gap:6px}
  .slot b{font-size:14px}
  .slot .muted{font-size:11px}

  /* bottom tab bar */
  .tabs{position:fixed;bottom:0;left:0;right:0;z-index:10;background:#fff;border-top:1px solid #e6eef5;display:grid;grid-template-columns:repeat(5,1fr)}
  .tab{appearance:none;background:none;border:none;padding:10px 4px;font-size:12px;color:#334;display:grid;place-items:center;gap:6px}
  .tab.active{color:var(--blue)}
  .tab .dot{width:6px;height:6px;border-radius:50%;background:transparent}
  .tab.active .dot{background:var(--blue)}
  .tab span{font-size:11px}
  .icon{width:22px;height:22px;border-radius:6px;background:#eef6ff;display:grid;place-items:center;color:var(--blue);font-weight:900}

  /* drawer / checkout */
  .drawer{position:fixed;left:0;right:0;bottom:0;background:#fff;border-top-left-radius:16px;border-top-right-radius:16px;box-shadow:0 -8px 24px rgba(13,27,42,.15);display:none;z-index:20}
  .drawer header{padding:12px 14px;background:#0D1B2A;color:#fff;border-top-left-radius:16px;border-top-right-radius:16px;display:flex;justify-content:space-between;align-items:center}
  .drawer .body{padding:14px;display:grid;gap:10px}
  .chip{border:1px solid #e6eef5;border-radius:999px;padding:6px 10px;display:inline-block;margin-right:8px}
  .chip.active{border-color:var(--blue);color:var(--blue);background:#eef6ff}
  .total{display:flex;align-items:center;justify-content:space-between;padding-top:8px;border-top:1px dashed #e6eef5}

  /* utilities */
  .hidden{display:none}
  @media(min-width:720px){
    .row{grid-template-columns:1fr 1fr}
    .slots{grid-template-columns:repeat(4,1fr)}
  }
</style>
</head>
<body>
<div class="app">
  <header>
    <div class="brand">
      <div class="logo">S</div>
      <div class="title"><b>Scommy</b><small>Sport + Community</small></div>
    </div>
  </header>

  <main class="wrap">
    <!-- HOME -->
    <section id="home" class="page">
      <div class="card">
        <div class="pill">Community First</div>
        <h2>Find your team. Play your game.</h2>
        <p class="muted">Match with players, book a court/coach, and rent gear — all in one place.</p>
        <div class="row">
          <button class="btn" onclick="go('match')">Find Players</button>
          <button class="btn" onclick="go('book')">Book a Court</button>
          <button class="btn lime" onclick="go('gear')">Gear Rental</button>
        </div>
      </div>

      <div class="kpis">
        <div class="card"><b>Active players</b><div id="kpiPlayers" style="font-size:22px;margin-top:6px">—</div><div class="muted">this month</div></div>
        <div class="card"><b>Matches created</b><div id="kpiMatches" style="font-size:22px;margin-top:6px">—</div><div class="muted">community</div></div>
        <div class="card"><b>Points</b><div id="kpiPoints" style="font-size:22px;margin-top:6px">0</div><div class="muted">your balance</div></div>
        <div class="card"><b>Venues onboarded</b><div style="font-size:22px;margin-top:6px">58</div><div class="muted">pilot phase</div></div>
      </div>

      <div class="card">
        <h3>Upcoming community matches</h3>
        <div class="list" id="matchList"></div>
      </div>
    </section>

    <!-- FIND -->
    <section id="match" class="page hidden">
      <div class="card">
        <h3>Find players & join a match</h3>
        <div class="row">
          <select id="filterSport"><option>All sports</option><option>Tennis</option><option>Badminton</option><option>Futsal</option></select>
          <select id="filterLevel"><option>Any level</option><option>Beginner</option><option>Intermediate</option><option>Advanced</option></select>
        </div>
        <div class="list" id="discoverList" style="margin-top:12px"></div>
      </div>
      <div class="card">
        <h3>Quick create a match</h3>
        <div class="row">
          <select id="sport"><option>Tennis</option><option>Badminton</option><option>Futsal</option></select>
          <input id="when" type="datetime-local"/>
        </div>
        <div class="row">
          <input id="where" placeholder="Venue (e.g., Scommy Arena, Rama 9)"/>
          <select id="level"><option>Beginner</option><option>Intermediate</option><option>Advanced</option></select>
        </div>
        <button class="btn block" onclick="createMatch()">Create Match (+50 pts)</button>
      </div>
    </section>

    <!-- BOOK COURT -->
    <section id="book" class="page hidden">
      <div class="card">
        <h3>Book a Court</h3>
        <div class="row">
          <select id="bkSport"><option>Tennis</option><option>Badminton</option><option>Futsal</option><option>Basketball</option></select>
          <input id="bkDate" type="date"/>
        </div>
        <div class="row">
          <select id="bkVenue"><option>Scommy Arena – Rama 9</option><option>City Badminton – Sukhumvit</option><option>Bangna Futsal Park</option></select>
          <select id="bkPlayers"><option>2 players</option><option>4 players</option><option>5 players</option><option>10 players</option></select>
        </div>
        <div class="slots" id="bkSlots"></div>
      </div>
    </section>

    <!-- COACH -->
    <section id="coach" class="page hidden">
      <div class="card">
        <h3>Book a coach</h3>
        <div class="list" id="coachList"></div>
      </div>
    </section>

    <!-- GEAR -->
    <section id="gear" class="page hidden">
      <div class="card">
        <h3>Gear & Apparel Rental</h3>
        <div class="row">
          <select id="gearCat"><option value="Tennis">Tennis</option><option value="Badminton">Badminton</option><option value="Football">Football</option><option value="Fitness">Fitness</option></select>
          <select id="gearWhen"><option>Today 18:00 - 20:00</option><option>Tomorrow 10:00 - 12:00</option><option>Tomorrow 18:00 - 20:00</option></select>
        </div>
        <div class="list" id="gearList" style="margin-top:12px"></div>
      </div>
    </section>

    <!-- LOYALTY -->
    <section id="loyalty" class="page hidden">
      <div class="card">
        <h3>Loyalty & Rewards</h3>
        <div class="list" id="rewards"></div>
      </div>
    </section>

    <!-- OWNER -->
    <section id="owner" class="page hidden">
      <div class="card">
        <h3>Owner Dashboard (Demo)</h3>
        <div class="list" id="ownerList"></div>
      </div>
    </section>
  </main>

  <!-- bottom tabs -->
  <nav class="tabs">
    <button class="tab active" data-tab="home"><div class="icon">🏠</div><span>Home</span><div class="dot"></div></button>
    <button class="tab" data-tab="match"><div class="icon">👥</div><span>Players</span><div class="dot"></div></button>
    <button class="tab" data-tab="book"><div class="icon">🎾</div><span>Book</span><div class="dot"></div></button>
    <button class="tab" data-tab="gear"><div class="icon">🎒</div><span>Gear</span><div class="dot"></div></button>
    <button class="tab" data-tab="loyalty"><div class="icon">⭐</div><span>Loyalty</span><div class="dot"></div></button>
  </nav>
</div>

<!-- Drawer: Checkout -->
<div class="drawer" id="checkout">
  <header><div><b>Checkout</b> • <span id="coTitle">Item</span></div><button class="btn" style="background:#fff;color:#0D1B2A;padding:6px 10px" onclick="closeCheckout()">Close</button></header>
  <div class="body">
    <div class="muted" id="coMeta">When / Where</div>
    <input id="coName" placeholder="Full name"/>
    <input id="coEmail" placeholder="Email"/>
    <div><span class="chip active" data-method="card" onclick="selPay(this)">Card</span> <span class="chip" data-method="promptpay" onclick="selPay(this)">PromptPay</span> <span class="chip" data-method="apple" onclick="selPay(this)">Apple Pay</span></div>
    <div id="cardForm"><input placeholder="Card number"/><div class="row"><input placeholder="MM/YY"/><input placeholder="CVC"/></div></div>
    <div class="total"><b>Total</b><div><span id="coPrice">0</span> THB</div></div>
    <button class="btn block" onclick="payNow()">Pay & Confirm</button>
    <p class="muted" style="text-align:center">By paying, you agree to Scommy Terms & Community Rules.</p>
  </div>
</div>

<script>
  const $ = id => document.getElementById(id);
  const state = {
    points: Number(localStorage.getItem('scommy_points')||0),
    players: 12450, matches: 382,
    matchesData: [
      {sport:'Tennis', when:'Today 19:00', where:'Lumpini Sports', level:'Intermediate', spots:1},
      {sport:'Badminton', when:'Today 20:00', where:'Rama IX Court', level:'Beginner', spots:2},
      {sport:'Futsal', when:'Tomorrow 18:00', where:'Bangna Arena', level:'Any', spots:5}
    ],
    coaches: [
      {name:'Coach May', sport:'Badminton', rating:4.9, price:600},
      {name:'Coach Beam', sport:'Tennis', rating:4.8, price:900},
      {name:'Coach Art', sport:'Football', rating:4.7, price:700}
    ],
    gear: {
      Tennis:[{name:'Wilson Ultra Racket', price:150},{name:'Tennis Shoes (38-44)', price:120}],
      Badminton:[{name:'Yonex Astrox Racket', price:120},{name:'Indoor Court Shoes', price:100}],
      Football:[{name:'Adidas Goalie Gloves', price:100},{name:'Football (Match)', price:60}],
      Fitness:[{name:'Yoga Mat', price:50},{name:'Dumbbell Set', price:80}]
    },
    owners:[
      {venue:'Scommy Arena – Rama 9', occ:'72%', rev:'145,200 THB / mo', promo:'Weekday -15%'},
      {venue:'City Badminton – Sukhumvit', occ:'64%', rev:'92,500 THB / mo', promo:'Student Pack'}
    ],
    checkout:null
  };

  // NAV
  function go(id){
    document.querySelectorAll('.page').forEach(p=>p.classList.add('hidden'));
    document.querySelectorAll('.tab').forEach(t=>t.classList.remove('active'));
    document.querySelector(`.tab[data-tab="${id}"]`)?.classList.add('active');
    document.getElementById(id).classList.remove('hidden');
    if(id==='gear') renderGear();
    if(id==='match') renderDiscover();
    if(id==='coach') renderCoaches();
    if(id==='book') renderBookSlots();
    if(id==='home') renderKPIs();
  }
  document.addEventListener('click', (e)=>{
    if(e.target.closest('.tab')) go(e.target.closest('.tab').dataset.tab);
  });

  // KPIs & lists
  function renderKPIs(){ $('kpiPlayers').textContent = state.players.toLocaleString(); $('kpiMatches').textContent = state.matches.toLocaleString(); $('kpiPoints').textContent = state.points.toLocaleString(); }
  function row(title, meta, cta, action, lime=false){
    const el = document.createElement('div'); el.className='item';
    el.innerHTML = `<div class="meta"><b>${title}</b><span class="muted">${meta}</span></div><button class="btn ${lime?'lime':''}" onclick="${action}">${cta}</button>`;
    return el;
  }
  function renderMatches(){
    const box = $('matchList'); box.innerHTML='';
    state.matchesData.forEach((m,i)=> box.appendChild(row(`${m.sport} • ${m.when}`, `${m.where} • Level: ${m.level}`, `Join (${m.spots} left)`, `joinMatch(${i})`)));
  }
  function createMatch(){
    const sport = $('sport').value, when = $('when').value || 'Soon', where = $('where').value || 'TBD', level = $('level').value;
    state.matchesData.unshift({sport, when, where, level, spots:3}); state.matches++; addPoints(50); renderMatches(); renderDiscover(); renderKPIs();
    openCheckout({type:'Match fee', title:`${sport} Community Match`, meta:`${when} • ${where}`, price:80});
  }
  function joinMatch(i){
    state.matchesData[i].spots = Math.max(0, state.matchesData[i].spots-1); addPoints(10); renderMatches(); renderDiscover();
    openCheckout({type:'Match fee', title: state.matchesData[i].sport+' Community Match', meta: state.matchesData[i].when+' • '+state.matchesData[i].where, price:80});
  }

  // Discover
  function renderDiscover(){
    const fs = $('filterSport').value, fl = $('filterLevel').value, list = $('discoverList'); list.innerHTML='';
    state.matchesData.filter(m => (fs==='All sports'||m.sport===fs) && (fl==='Any level'||m.level===fl)).forEach((m,i)=> list.appendChild(row(`${m.sport} • ${m.when}`, `${m.where} • Level: ${m.level}`, 'Join', `joinMatch(${i})`)));
  }
  document.getElementById('filterSport').addEventListener('change', renderDiscover);
  document.getElementById('filterLevel').addEventListener('change', renderDiscover);

  // Coaches
  function renderCoaches(){
    const list = $('coachList'); list.innerHTML='';
    state.coaches.forEach((c,i)=> list.appendChild(row(`${c.name} • ${c.sport}`, `Rating ${c.rating} • ${c.price} THB/hr`, 'Book', `bookCoach(${i})`)));
  }
  function bookCoach(i){ const c = state.coaches[i]; openCheckout({type:'Coach', title:`${c.name} (${c.sport})`, meta:'1 hour session', price:c.price}); }

  // Gear
  function renderGear(){
    const cat = $('gearCat').value, list = $('gearList'); list.innerHTML='';
    (state.gear[cat]||[]).forEach((g,i)=> list.appendChild(row(g.name, `${cat} • ${g.price} THB / 2h`, 'Rent', `rentGear('${cat}', ${i})`, true)));
  }
  function rentGear(cat,i){ const item = state.gear[cat][i]; openCheckout({type:'Gear Rental', title:item.name, meta:`${cat} • ${$('gearWhen').value}`, price:item.price}); }
  document.getElementById('gearCat').addEventListener('change', renderGear);
  document.getElementById('gearWhen').addEventListener('change', renderGear);

  // Owner
  function renderOwners(){
    const list = $('ownerList'); list.innerHTML='';
    state.owners.forEach(o=>{ const el = document.createElement('div'); el.className='item'; el.innerHTML = `<div class="meta"><b>${o.venue}</b><span class="muted">Occupancy ${o.occ} • Revenue ${o.rev}</span></div><span class="pill">${o.promo||''}</span>`; list.appendChild(el); });
  }

  // Booking grid
  const courtPrices = { Tennis:300, Badminton:250, Futsal:800, Basketball:600 };
  function renderBookSlots(){
    const sport=$('bkSport').value, date=$('bkDate').value||'Today', venue=$('bkVenue').value, box=$('bkSlots');
    const times=['16:00-17:00','17:00-18:00','18:00-19:00','19:00-20:00','20:00-21:00','21:00-22:00','Sat 10:00-11:00','Sat 11:00-12:00'];
    const price=courtPrices[sport]||300; box.innerHTML='';
    times.forEach(t=>{ const el=document.createElement('div'); el.className='slot';
      el.innerHTML = `<b>${t}</b><span class="muted">${sport} • ${venue}</span><button class="btn" onclick="bookCourt('${sport}','${venue}','${date} ${t}',${price})">Book • ${price} THB</button>`;
      box.appendChild(el);
    });
  }
  document.getElementById('bkSport').addEventListener('change', renderBookSlots);
  document.getElementById('bkDate').addEventListener('change', renderBookSlots);
  document.getElementById('bkVenue').addEventListener('change', renderBookSlots);
  document.getElementById('bkPlayers').addEventListener('change', renderBookSlots);

  // Checkout
  function openCheckout(p){ state.checkout=p; $('coTitle').textContent=p.title; $('coMeta').textContent=p.meta; $('coPrice').textContent=p.price.toLocaleString(); document.getElementById('checkout').style.display='block'; }
  function closeCheckout(){ document.getElementById('checkout').style.display='none'; state.checkout=null; }
  function selPay(el){ document.querySelectorAll('.chip').forEach(c=>c.classList.remove('active')); el.classList.add('active'); $('cardForm').style.display=(el.dataset.method==='card')?'grid':'none'; }
  function payNow(){ if(!state.checkout) return; addPoints(20); alert('Payment success (+20 pts)'); closeCheckout(); }
  function addPoints(n){ state.points += n; localStorage.setItem('scommy_points', state.points); renderKPIs(); }

  // Init page
  function init(){
    renderKPIs(); renderMatches(); renderDiscover(); renderCoaches(); renderOwners(); renderGear(); renderBookSlots();
  }
  init();
</script>
</body>
</html>
