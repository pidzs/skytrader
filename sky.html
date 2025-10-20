<!doctype html>
<html lang="id">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>SkyTrade </title>
  <meta name="description" content="Marketplace pesawat modern — listing, detail, dan kontak dealer." />
  <link rel="icon" href="data:;base64,iVBORw0KGgo=" />
  <style>
    :root{
      --bg:#0f1724; /* dark navy */
      --card:#0b1220;
      --accent:#1e90ff;
      --muted:#9aa6bf;
      --glass: rgba(255,255,255,0.04);
      --success:#2dd4bf;
      --danger:#ff6b6b;
      --radius:14px;
      font-family: Inter, ui-sans-serif, system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial;
    }
    *{box-sizing:border-box}
    html,body{height:100%}
    body{
      margin:0;
      background:linear-gradient(180deg,var(--bg) 0%, #061022 100%);
      color:#e6eef8;
      -webkit-font-smoothing:antialiased;
      -moz-osx-font-smoothing:grayscale;
      padding:32px;
      line-height:1.4;
    }

    /* Container */
    .container{max-width:1200px;margin:0 auto}

    header{
      display:flex;align-items:center;justify-content:space-between;margin-bottom:28px
    }
    .brand{display:flex;gap:14px;align-items:center}
    .logo{
      height:56px;width:56px;border-radius:12px;background:linear-gradient(135deg,var(--accent),#7dd3fc);
      display:grid;place-items:center;font-weight:700;color:#012030
    }
    .brand h1{font-size:20px;margin:0}
    nav{display:flex;gap:12px;align-items:center}
    .nav-link{color:var(--muted);text-decoration:none;padding:8px 12px;border-radius:10px}
    .nav-link:hover{background:var(--glass);color:#fff}

    /* Hero */
    .hero{display:grid;grid-template-columns:1fr 420px;gap:24px;align-items:center;margin-bottom:28px}
    .hero-card{background:linear-gradient(180deg, rgba(255,255,255,0.02), transparent);padding:28px;border-radius:var(--radius);box-shadow:0 8px 30px rgba(2,6,23,0.6)}
    .hero h2{margin:0 0 8px 0;font-size:28px}
    .hero p{margin:0 0 18px;color:var(--muted)}
    .search{display:flex;gap:8px}
    .search input, .search select{flex:1;padding:12px 14px;border-radius:12px;border:1px solid rgba(255,255,255,0.04);background:transparent;color:inherit}
    .btn{background:var(--accent);color:#012030;padding:12px 16px;border-radius:12px;border:0;font-weight:600;cursor:pointer}

    /* Cards grid */
    .filters{display:flex;gap:10px;margin-bottom:12px}
    .grid{display:grid;grid-template-columns:repeat(auto-fill,minmax(260px,1fr));gap:18px}
    .card{background:var(--card);border-radius:14px;overflow:hidden;box-shadow:0 6px 22px rgba(2,6,23,0.6);border:1px solid rgba(255,255,255,0.03)}
    .card .media{height:160px;background-size:cover;background-position:center}
    .card .body{padding:14px}
    .card h3{margin:0 0 6px 0;font-size:18px}
    .muted{color:var(--muted);font-size:13px}
    .price{font-weight:700;margin-top:10px}
    .card .actions{display:flex;gap:8px;margin-top:12px}
    .btn-ghost{background:transparent;border:1px solid rgba(255,255,255,0.06);padding:10px 12px;border-radius:10px;color:var(--muted);cursor:pointer}

    /* modal */
    .overlay{position:fixed;inset:0;background:rgba(2,6,23,0.6);display:none;align-items:center;justify-content:center;padding:20px}
    .modal{max-width:900px;width:100%;background:linear-gradient(180deg,#071027, #071827);border-radius:12px;padding:18px;border:1px solid rgba(255,255,255,0.04)}
    .modal-grid{display:grid;grid-template-columns:1fr 320px;gap:16px}
    .spec{display:flex;flex-direction:column;gap:8px}
    .spec .row{display:flex;justify-content:space-between;color:var(--muted)}
    .close{background:transparent;border:0;color:var(--muted);cursor:pointer}

    footer{margin-top:28px;color:var(--muted);font-size:13px;display:flex;justify-content:space-between}

    /* responsive */
    @media (max-width:900px){
      .hero{grid-template-columns:1fr;}
      .modal-grid{grid-template-columns:1fr}
      body{padding:18px}
    }

    /* small utilities */
    .pill{background:rgba(255,255,255,0.03);padding:6px 10px;border-radius:999px;font-weight:600}
  </style>
</head>
<body>
  <div class="container">
    <header>
      <div class="brand">
        <div class="logo">ST</div>
        <div>
          <h1>SkyTrade</h1>
          <div style="color:var(--muted);font-size:13px">Marketplace Pesawat — Jual & Beli</div>
        </div>
      </div>
      <nav>
        <a class="nav-link" href="#list">Pesawat</a>
        <a class="nav-link" href="#about">Tentang</a>
        <a class="nav-link" href="#contact">Kontak</a>
        <a class="nav-link pill" href="#add">Tambah Listing</a>
      </nav>
    </header>

    <section class="hero-card hero">
      <div>
        <h2>Temukan pesawat yang cocok untuk bisnis atau koleksi Anda</h2>
        <p>Cari berdasarkan tipe, tahun, harga atau lokasi. Listing diverifikasi dan siap terbang.</p>

        <div class="search">
          <input id="q" placeholder="Cari model, tipe, atau fitur (mis. Cessna, jet, turboprop)" />
          <select id="region"><option value="">Semua wilayah</option><option>Amerika</option><option>Eropa</option><option>Asia</option></select>
          <button class="btn" onclick="applyFilter()">Cari</button>
        </div>

        <div style="display:flex;gap:10px;margin-top:16px">
          <div class="pill">Verifikasi Dokumen</div>
          <div class="pill">Inspeksi Pra-Pembelian</div>
          <div class="pill">Support Pengiriman</div>
        </div>
      </div>

      <aside>
        <div style="border-radius:12px;overflow:hidden;background:linear-gradient(180deg,#07203a,#04202c);padding:16px">
          <h3 style="margin:0 0 6px 0">Hubungi Dealer</h3>
          <p class="muted" style="margin:0 0 12px">Butuh bantuan memilih? Tim kami siap bantu negosiasi & inspeksi.</p>
          <div style="display:flex;gap:8px">
            <button class="btn" onclick="openContact()">Kirim Pesan</button>
            <button class="btn-ghost" onclick="phoneCall()">📞 +62 857 4841 8694</button>
          </div>
        </div>

        <div style="margin-top:12px;padding:12px;border-radius:12px;background:var(--glass)">
          <div class="muted">Filter cepat</div>
          <div style="display:flex;gap:8px;margin-top:8px">
            <select id="typeFilter"><option value="">Tipe (Semua)</option><option>Jet</option><option>Turboprop</option><option>Piston</option></select>
            <select id="yearFilter"><option value="">Tahun (Semua)</option><option>Before 2000</option><option>2000-2010</option><option>2011-2020</option><option>2021+</option></select>
          </div>
        </div>
      </aside>
    </section>

    <section id="list">
      <div style="display:flex;justify-content:space-between;align-items:end;margin-bottom:10px">
        <div>
          <h2 style="margin:0">Listing Terbaru</h2>
          <div class="muted">Menampilkan pesawat terpopuler dan baru masuk</div>
        </div>
        <div class="filters">
          <div class="muted">Urutkan:</div>
          <select id="sort" onchange="sortGrid()"><option value="new">Terbaru</option><option value="price-asc">Harga: Rendah → Tinggi</option><option value="price-desc">Harga: Tinggi → Rendah</option></select>
        </div>
      </div>

      <div class="grid" id="grid">
        <!-- Cards di-populate via JS -->
      </div>
    </section>

    <footer>
      <div>© <span id="year"></span> SkyTrade — Semua hak dilindungi.</div>
      <div class="muted">Butuh fitur khusus? Chat dengan kami melalui tombol kontak.</div>
    </footer>
  </div>

  <!-- Modal detail -->
  <div class="overlay" id="overlay">
    <div class="modal" role="dialog" aria-modal="true">
      <div style="display:flex;justify-content:space-between;align-items:center;margin-bottom:8px">
        <h3 id="modalTitle">Detail Pesawat</h3>
        <button class="close" onclick="closeModal()">✕</button>
      </div>

      <div class="modal-grid">
        <div>
          <div id="modalMedia" style="height:300px;border-radius:10px;background-size:cover;background-position:center;margin-bottom:12px"></div>
          <p id="modalDesc" class="muted"></p>
          <div style="display:flex;gap:8px;margin-top:12px">
            <button class="btn" onclick="contactSeller()">Hubungi Penjual</button>
            <button class="btn-ghost" onclick="fav()">♥ Simpan</button>
          </div>
        </div>
        <aside style="padding:12px;background:rgba(255,255,255,0.02);border-radius:8px">
          <div class="spec">
            <div class="row"><div class="muted">Harga</div><div id="modalPrice" style="font-weight:700"></div></div>
            <div class="row"><div class="muted">Tipe</div><div id="modalType"></div></div>
            <div class="row"><div class="muted">Tahun</div><div id="modalYear"></div></div>
            <div class="row"><div class="muted">Lokasi</div><div id="modalLoc"></div></div>
            <hr style="border:none;border-top:1px solid rgba(255,255,255,0.03)" />
            <div class="muted">Kontak Dealer</div>
            <div style="font-weight:700">PT. AeroDeals</div>
            <div class="muted">skytrade.com</div>
            <div class="muted">+62 857 4841 8694</div>
          </div>
        </aside>
      </div>
    </div>
  </div>

  <script>
    // sample data (replace with API in production)
    const planes = [
      {id:1,title:'Cessna 172 Skyhawk',type:'Piston',year:2008,price:185000,loc:'Jakarta, ID',img:'cessna.jpg',desc:'Pesawat latih & pribadi, 4-seat, efisien.'},
      {id:2,title:'Beechcraft King Air 350',type:'Turboprop',year:2016,price:4800000,loc:'Singapore',img:'beecrhaft.jpg',desc:'Turboprop twin-engine, ideal untuk korporat.'},
      {id:3,title:'Gulfstream G280',type:'Jet',year:2019,price:27000000,loc:'Dubai, UAE',img:'gulfstream.jpg',desc:'Super mid-size business jet, kabin mewah.'},
      {id:4,title:'Pilatus PC-12',type:'Turboprop',year:2014,price:4200000,loc:'Bangkok, TH',img:'pilatus.jpg',desc:'Serbaguna, cargo door, range jauh.'},
      {id:5,title:'Cirrus SR22',type:'Piston',year:2021,price:725000,loc:'Surabaya, ID',img:'cirrus.jpg',desc:'Teknologi modern & parachute system.'},
      {id:6,title:'F-16',type:'Jet',year:2023,price:107800,loc:'Frances, US',img:'jet1.jpg',desc:'Pesawat jet pribadi untuk menjelajah dunia'},
      {id:7,title:'Jet',type:'Jet',year:2021,price:774050,loc:'London, GBP',img:'sukhoi.jpg',desc:'pesawat tempur multirole generasi kelima; mampu bertempur udara-ke-udara, serangan ke darat, dan target laut'},
      {id:8,title:'ATR 72',type:'Turboprop',year:1997,price:149.533200000,loc:'Frances',img:'atr72.jpg',desc:'pesawat penumpang regional bermesin turboprop ganda yang dikembangkan dan diproduksi oleh produsen ATR, sebuah perusahaan patungan Prancis-Italia'},
    ];

    function formatPrice(v){
      if(v>=1000000) return 'US$ '+(v/1000000).toLocaleString(undefined,{maximumFractionDigits:2})+'M';
      return 'US$ '+v.toLocaleString();
    }

    function renderGrid(list){
      const grid = document.getElementById('grid');
      grid.innerHTML='';
      list.forEach(p=>{
        const card = document.createElement('div');card.className='card';
        card.innerHTML = `
          <div class="media" style="background-image:url(${p.img})"></div>
          <div class="body">
            <h3>${p.title}</h3>
            <div class="muted">${p.type} • ${p.year} • ${p.loc}</div>
            <div class="price">${formatPrice(p.price)}</div>
            <div class="actions">
              <button class="btn-ghost" onclick="openModal(${p.id})">Lihat</button>
              <button class="btn" onclick="buyNow(${p.id})">Beli</button>
            </div>
          </div>
        `;
        grid.appendChild(card);
      })
    }

    function openModal(id){
      const p = planes.find(x=>x.id===id);
      if(!p) return;
      document.getElementById('modalTitle').textContent=p.title;
      document.getElementById('modalMedia').style.backgroundImage=`url(${p.img})`;
      document.getElementById('modalDesc').textContent=p.desc;
      document.getElementById('modalPrice').textContent=formatPrice(p.price);
      document.getElementById('modalType').textContent=p.type;
      document.getElementById('modalYear').textContent=p.year;
      document.getElementById('modalLoc').textContent=p.loc;
      document.getElementById('overlay').style.display='flex';
    }
    function closeModal(){document.getElementById('overlay').style.display='none'}

    function buyNow(id){
      const p = planes.find(x=>x.id===id);
      if(!p) return alert('Pesawat tidak ditemukan');
      // Simple flow: open modal and prefill contact
      openModal(id);
      alert('Flow pembelian dimulai untuk: '+p.title+' — tim kami akan menghubungi Anda.');
    }

    function applyFilter(){
      const q = document.getElementById('q').value.toLowerCase();
      const region = document.getElementById('region').value;
      const type = document.getElementById('typeFilter').value;
      const yearSel = document.getElementById('yearFilter').value;
      let filtered = planes.filter(p=>{
        if(q && !(p.title.toLowerCase().includes(q) || p.type.toLowerCase().includes(q) || p.desc.toLowerCase().includes(q))) return false;
        if(region && !p.loc.toLowerCase().includes(region.toLowerCase())) return false;
        if(type && p.type!==type) return false;
        if(yearSel){
          if(yearSel==='Before 2000' && p.year>=2000) return false;
          if(yearSel==='2000-2010' && !(p.year>=2000 && p.year<=2010)) return false;
          if(yearSel==='2011-2020' && !(p.year>=2011 && p.year<=2020)) return false;
          if(yearSel==='2021+' && !(p.year>=2021)) return false;
        }
        return true;
      });
      renderGrid(filtered);
    }

    function sortGrid(){
      const s = document.getElementById('sort').value;
      let arr = [...planes];
      if(s==='price-asc') arr.sort((a,b)=>a.price-b.price);
      else if(s==='price-desc') arr.sort((a,b)=>b.price-a.price);
      else arr.sort((a,b)=>b.year-a.year);
      renderGrid(arr);
    }

    function contactSeller(){
      alert('Email dikirim ke ismarahtawu@gmail.com — Anda akan dihubungi dalam 1-2 hari kerja.');
    }

    function fav(){alert('Disimpan ke favorit Anda')}
    function openContact(){document.getElementById('overlay').style.display='flex';document.getElementById('modalTitle').textContent='Hubungi Dealer';document.getElementById('modalDesc').textContent='Isi email atau nomor telepon, tim kami akan menghubungi Anda.';document.getElementById('modalMedia').style.backgroundImage='url(https://picsum.photos/seed/contact/800/500)';document.getElementById('modalPrice').textContent='—';document.getElementById('modalType').textContent='—';document.getElementById('modalYear').textContent='—';document.getElementById('modalLoc').textContent='—';}
    function phoneCall(){alert('Menghubungi +62 857 4841 8694')}

    document.getElementById('year').textContent = new Date().getFullYear();
    // initial render
    renderGrid(planes);
    
  </script>
</body>
</html>
