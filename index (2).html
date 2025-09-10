<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Azar Loans — Static HTML</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <meta name="color-scheme" content="light only">
  <style>
    html, body { background:#ffffff; color:#111827; }
    .route { display:none; }
    .route.active { display:block; }
  </style>
</head>
<body class="min-h-screen bg-white text-gray-900 antialiased">
  <!-- Header -->
  <header class="bg-blue-900 text-white p-4 shadow-md sticky top-0 z-40 border-b border-blue-800">
    <div class="max-w-6xl mx-auto flex items-center justify-between">
      <div class="flex items-center space-x-3 cursor-pointer" onclick="navigate('home')">
        <div class="w-12 h-12 rounded-lg flex items-center justify-center bg-white text-blue-900 font-extrabold text-lg">AZ</div>
        <div>
          <h1 class="font-bold text-xl tracking-tight">Azar Loans</h1>
          <div class="text-xs opacity-80">Fast • Reliable • Transparent</div>
        </div>
      </div>

      <nav class="hidden md:flex gap-2 items-center">
        <button class="navbtn text-sm px-3 py-2 rounded" data-target="home">Home</button>
        <button class="navbtn text-sm px-3 py-2 rounded" data-target="products">Products</button>
        <button class="navbtn text-sm px-3 py-2 rounded" data-target="apply">Apply Now</button>
        <button class="navbtn text-sm px-3 py-2 rounded" data-target="partners">Partners</button>
        <button class="navbtn text-sm px-3 py-2 rounded" data-target="about">About</button>
        <button class="text-sm px-3 py-2 rounded-md border border-white bg-white text-blue-900 hover:bg-gray-200" onclick="navigate('admin-login')">Admin</button>
      </nav>

      <div class="md:hidden">
        <select id="mobileNav" class="bg-blue-900 text-white p-2 rounded" onchange="navigate(this.value)">
          <option value="home">Home</option>
          <option value="products">Products</option>
          <option value="apply">Apply Now</option>
          <option value="partners">Partners</option>
          <option value="about">About</option>
          <option value="admin-login">Admin</option>
        </select>
      </div>
    </div>
  </header>

  <!-- Main -->
  <main class="p-6 max-w-6xl mx-auto">
    <!-- HOME -->
    <section id="route-home" class="route active">
      <div class="grid md:grid-cols-2 gap-8 items-center py-12">
        <div>
          <h2 class="text-4xl font-extrabold text-blue-900">Loans that move you forward</h2>
          <p class="mt-4 text-lg text-gray-700">Flexible personal, business and vehicle loans with simple paperwork and transparent pricing. Apply online and get a quick decision.</p>

          <div class="mt-6 flex gap-3">
            <button onclick="navigate('apply')" class="px-5 py-3 rounded-2xl bg-blue-900 text-white font-semibold hover:opacity-90">Apply Now</button>
            <button onclick="navigate('products')" class="px-5 py-3 rounded-2xl border border-blue-900 text-blue-900 hover:bg-blue-50">View Products</button>
          </div>

          <div class="mt-10">
            <h4 class="text-sm uppercase text-gray-500">Trusted by</h4>
            <div id="trustedPills" class="flex flex-wrap items-center gap-2 mt-3"></div>
          </div>
        </div>

        <div class="p-6 rounded-2xl bg-white border border-blue-200 shadow-sm">
          <div class="text-right text-xs text-gray-500">Quick estimate</div>
          <div class="mt-4">
            <p class="text-3xl font-bold text-blue-900">EMI Calculator</p>
            <p class="mt-2 text-gray-600">Estimate monthly payments for loan amounts and tenures.</p>
          </div>

          <div class="mt-6 grid grid-cols-2 gap-3">
            <label class="text-sm">
              <span class="text-xs text-gray-600">Amount</span>
              <input id="emiAmount" class="mt-1 rounded px-3 py-2 border border-gray-200 w-full" value="500000" />
            </label>
            <label class="text-sm">
              <span class="text-xs text-gray-600">Tenure (yrs)</span>
              <input id="emiYears" class="mt-1 rounded px-3 py-2 border border-gray-200 w-full" value="3" />
            </label>
            <label class="text-sm">
              <span class="text-xs text-gray-600">Rate (%)</span>
              <input id="emiRate" class="mt-1 rounded px-3 py-2 border border-gray-200 w-full" value="12" />
            </label>
            <div class="col-span-2 mt-2">
              <button onclick="calcEmi()" class="w-full py-3 rounded bg-blue-900 text-white font-semibold hover:opacity-90">Calculate</button>
            </div>
            <div class="col-span-2 mt-2 text-sm text-gray-700">
              <div>Estimated EMI: <span id="emiOut">—</span></div>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- PRODUCTS -->
    <section id="route-products" class="route">
      <h3 class="text-2xl font-bold text-blue-900">Our Loan Products</h3>
      <div id="productsGrid" class="mt-6 grid md:grid-cols-3 gap-4"></div>
    </section>

    <!-- APPLY -->
    <section id="route-apply" class="route">
      <div class="max-w-2xl mx-auto p-6 rounded-2xl shadow-sm bg-white border border-blue-200">
        <h3 class="text-2xl font-bold text-blue-900">Loan Application</h3>
        <p class="mt-2 text-sm text-gray-600">Fill in the details below. Our team will contact you within 24 hours.</p>

        <form id="applyForm" class="mt-6 grid gap-4">
          <div class="grid md:grid-cols-2 gap-4">
            <label class="text-sm">
              <span class="text-xs text-gray-600">Full Name</span>
              <input name="name" class="mt-1 rounded px-3 py-2 border border-gray-200 w-full" placeholder="Your name" />
            </label>
            <label class="text-sm">
              <span class="text-xs text-gray-600">Phone</span>
              <input name="phone" class="mt-1 rounded px-3 py-2 border border-gray-200 w-full" placeholder="10-digit mobile" />
            </label>
          </div>

          <label class="text-sm">
            <span class="text-xs text-gray-600">Email</span>
            <input name="email" class="mt-1 rounded px-3 py-2 border border-gray-200 w-full" placeholder="you@example.com" />
          </label>

          <div class="grid md:grid-cols-2 gap-4">
            <label class="text-sm">
              <span class="text-xs text-gray-600">Product</span>
              <select name="product" class="mt-1 rounded px-3 py-2 border border-gray-200 w-full" id="productSelect"></select>
            </label>
            <label class="text-sm">
              <span class="text-xs text-gray-600">Amount (₹)</span>
              <input name="amount" class="mt-1 rounded px-3 py-2 border border-gray-200 w-full" placeholder="e.g. 500000" />
            </label>
          </div>

          <div class="grid md:grid-cols-2 gap-4">
            <label class="text-sm">
              <span class="text-xs text-gray-600">Tenure (years)</span>
              <input name="tenure" class="mt-1 rounded px-3 py-2 border border-gray-200 w-full" placeholder="e.g. 3" />
            </label>
            <label class="text-sm">
              <span class="text-xs text-gray-600">Monthly Income (₹)</span>
              <input name="income" class="mt-1 rounded px-3 py-2 border border-gray-200 w-full" placeholder="e.g. 45000" />
            </label>
          </div>

          <button class="px-6 py-3 rounded-2xl bg-blue-900 text-white font-semibold hover:opacity-90">Submit</button>
        </form>
      </div>
    </section>

    <!-- PARTNERS -->
    <section id="route-partners" class="route py-8">
      <h3 class="text-2xl font-bold text-blue-900">Trusted by</h3>
      <p class="text-sm text-gray-600 mt-1">Listed partners are for representation only.</p>
      <div id="partnersPills" class="mt-4 flex flex-wrap gap-2"></div>
    </section>

    <!-- ABOUT -->
    <section id="route-about" class="route py-8">
      <h3 class="text-2xl font-bold text-blue-900">About Azar Loans</h3>
      <p class="mt-2 text-gray-700">We help individuals and businesses access credit quickly and responsibly. Transparent pricing, fast processing and human support are at the heart of what we do.</p>
      <ul class="list-disc pl-5 mt-3 text-gray-700 text-sm">
        <li>Paperwork assistance & doorstep pickup</li>
        <li>Multiple lenders to find your best fit</li>
        <li>Dedicated support from application to disbursal</li>
      </ul>
    </section>

    <!-- ADMIN LOGIN -->
    <section id="route-admin-login" class="route">
      <div class="max-w-md mx-auto p-6 rounded-2xl shadow-sm bg-white border border-blue-200">
        <h3 class="text-2xl font-bold text-blue-900">Admin Login</h3>
        <form id="adminLoginForm" class="mt-6 grid gap-4">
          <label class="text-sm">
            <span class="text-xs text-gray-600">Username</span>
            <input id="adminUser" class="mt-1 rounded px-3 py-2 border border-gray-200 w-full" />
          </label>
          <label class="text-sm">
            <span class="text-xs text-gray-600">Password</span>
            <input type="password" id="adminPass" class="mt-1 rounded px-3 py-2 border border-gray-200 w-full" />
          </label>
          <button class="px-6 py-3 rounded-2xl bg-blue-900 text-white font-semibold hover:opacity-90">Login</button>
          <p class="text-xs text-gray-500">
          </p>
        </form>
      </div>
    </section>

    <!-- ADMIN -->
    <section id="route-admin" class="route py-4">
      <div class="flex items-center justify-between">
        <h3 class="text-2xl font-bold text-blue-900">Applications</h3>
        <div class="flex gap-2">
          <button id="settingsBtn" class="px-4 py-2 rounded border border-blue-900 text-blue-900 hover:bg-blue-50">Settings</button>
          <button onclick="signOut()" class="px-4 py-2 rounded border border-blue-900 text-blue-900 hover:bg-blue-50">Sign out</button>
        </div>
      </div>

      <form id="settingsForm" class="hidden mt-4 p-4 border border-blue-200 rounded-lg bg-white grid md:grid-cols-3 gap-3">
        <label class="text-sm">
          <span class="text-xs text-gray-600">Admin Username</span>
          <input id="setUser" class="mt-1 rounded px-3 py-2 border border-gray-200 w-full" />
        </label>
        <label class="text-sm">
          <span class="text-xs text-gray-600">Admin Password</span>
          <input type="password" id="setPass" class="mt-1 rounded px-3 py-2 border border-gray-200 w-full" />
        </label>
        <div class="flex items-end">
          <button class="px-4 py-2 rounded bg-blue-900 text-white hover:opacity-90">Update</button>
        </div>
        <p class="md:col-span-3 text-xs text-gray-500">These credentials are stored in your browser's localStorage for demo purposes.</p>
      </form>

      <div id="appsEmpty" class="mt-6 text-gray-600">No submissions yet.</div>
      <div id="appsTableWrap" class="hidden overflow-x-auto mt-4 border border-blue-200 rounded-lg">
        <table class="min-w-full text-sm">
          <thead class="bg-blue-50 text-blue-900">
            <tr>
              <th class="text-left p-2">Name</th>
              <th class="text-left p-2">Phone</th>
              <th class="text-left p-2">Email</th>
              <th class="text-left p-2">Product</th>
              <th class="text-left p-2">Amount</th>
              <th class="text-left p-2">Tenure</th>
              <th class="text-left p-2">Income</th>
              <th class="text-left p-2">Actions</th>
            </tr>
          </thead>
          <tbody id="appsTbody"></tbody>
        </table>
      </div>
    </section>

    <!-- THANKS -->
    <section id="route-thanks" class="route">
      <div class="max-w-xl mx-auto text-center py-16">
        <h3 class="text-3xl font-bold text-blue-900">Thank you!</h3>
        <p class="mt-3 text-gray-700">Your application has been submitted. Our team will reach out shortly.</p>
      </div>
    </section>
  
    <!-- PRIVACY -->
    <section id="route-privacy" class="route py-8">
      <h3 class="text-2xl font-bold text-blue-900">Privacy Policy</h3>
      <p class="mt-2 text-gray-700">We respect your privacy and are committed to protecting your personal data. Information collected is used only for processing loan applications and support purposes.</p>
    </section>

    <!-- TERMS -->
    <section id="route-terms" class="route py-8">
      <h3 class="text-2xl font-bold text-blue-900">Terms & Conditions</h3>
      <p class="mt-2 text-gray-700">By using our services, you agree to provide accurate information and comply with loan eligibility rules. Loan approval is subject to lender discretion.</p>
    </section>

    <!-- SUPPORT -->
    <section id="route-support" class="route py-8">
      <h3 class="text-2xl font-bold text-blue-900">Support</h3>
      <p class="mt-2 text-gray-700">Need help? Contact us at <a href="mailto:support@azarloans.com" class="text-blue-900 underline">azarloans@gmail.com</a>.</p>
    </section>

  </main>

  <!-- Footer -->
  <footer class="mt-12 border-t border-gray-200">
    <div class="max-w-6xl mx-auto p-6 text-sm text-gray-600 flex flex-col md:flex-row gap-2 md:items-center md:justify-between">
      <div>© <span id="year"></span> Azar Loans. All rights reserved.</div>
      <div class="flex gap-4">
        <a class="hover:underline cursor-pointer" onclick="navigate('privacy')">Privacy</a>
        <a class="hover:underline cursor-pointer" onclick="navigate('terms')">Terms</a>
        <a class="hover:underline cursor-pointer" onclick="navigate('support')">Support</a>
      </div>
    </div>
  </footer>

  <script>
    // -----------------------
    // Data
    // -----------------------
    const TRUSTED_BY = [
      "HDFC Bank","ICICI Bank","Axis Bank","SBI Bank",
      "Kotak Mahindra Bank","Yes Bank","Bajaj Finserv","Tata Capital","All NBFC Finance Company's",
    ];

    const PRODUCTS = [
      { id:1, name:"Personal Loan", rate:"12–18%", desc:"For salaried & self‑employed. Quick processing." },
      { id:2, name:"Business Loan", rate:"13–20%", desc:"Working capital & expansion with flexible tenure." },
      { id:3, name:"Vehicle Loan", rate:"9–14%", desc:"New & used vehicles with easy EMIs." },
      { id:4, name:"Home Loan", rate:"8–12%", desc:"Buy your dream home with flexible repayment options." },
      { id:5, name:"Education Loan", rate:"10–15%", desc:"Support higher education with easy repayment plans." },
      { id:6, name:"Gold Loan", rate:"7–10%", desc:"Quick loan against gold with minimal paperwork." },
      { id:7, name:"Balance Transfer", rate:"8–14%", desc:"Reduce EMI by transferring your existing loan." },
      { id:8, name:"Top‑Up Loan", rate:"9–15%", desc:"Get extra funds on your existing home loan." },
      { id:9, name:"MSME/Agriculture Loan", rate:"11–18%", desc:"For micro & small businesses and agri needs." },
      { id:10, name:"Startup Loan", rate:"12–20%", desc:"Funding for new entrepreneurs and startups." },
      { id:11, name:"Wedding Loan", rate:"11–16%", desc:"Plan your special day without financial stress." },
      { id:12, name:"Travel Loan", rate:"10–15%", desc:"Finance your dream vacations easily." },
      { id:13, name:"Debt Consolidation Loan", rate:"10–16%", desc:"Combine multiple debts into one easy EMI." }
    ];

    const DEFAULT_ADMIN = { user: "azar", pass: "Azar@2025" };

    // -----------------------
    // Utilities
    // -----------------------
    function computeEmi(P, annualRatePct, years) {
      const principal = Number(P);
      const y = Number(years);
      const annual = Number(annualRatePct);
      if (!principal || !y || principal <= 0 || y <= 0) return null;
      const n = y * 12;
      if (!annual || annual <= 0) return +(principal / n).toFixed(2);
      const r = annual / 100 / 12;
      const pow = Math.pow(1 + r, n);
      const emi = (principal * r * pow) / (pow - 1);
      return +emi.toFixed(2);
    }

    function getAdminCreds() {
      try {
        const user = localStorage.getItem("azar_admin_user") || DEFAULT_ADMIN.user;
        const pass = localStorage.getItem("azar_admin_pass") || DEFAULT_ADMIN.pass;
        return { user, pass };
      } catch {
        return { ...DEFAULT_ADMIN };
      }
    }
    function setAdminCreds(user, pass) {
      try {
        localStorage.setItem("azar_admin_user", user);
        localStorage.setItem("azar_admin_pass", pass);
        return true;
      } catch {
        return false;
      }
    }

    function saveSubmissions(list) {
      localStorage.setItem("azar_submissions", JSON.stringify(list || []));
    }
    function loadSubmissions() {
      try { return JSON.parse(localStorage.getItem("azar_submissions") || "[]"); }
      catch { return []; }
    }

    function navigate(route) {
      // update sections
      document.querySelectorAll(".route").forEach(el => el.classList.remove("active"));
      const el = document.getElementById("route-" + route);
      if (el) el.classList.add("active");
      // header active states
      document.querySelectorAll(".navbtn").forEach(btn => {
        const active = btn.dataset.target === route;
        btn.className = "navbtn text-sm px-3 py-2 rounded " + (active ? "bg-white text-blue-900 font-semibold" : "hover:bg-blue-100");
      });
      const mobile = document.getElementById("mobileNav");
      if (mobile) mobile.value = route;
      // persist admin auth in session
      if (route === "admin" && !sessionStorage.getItem("azar_adminAuth")) {
        navigate("admin-login");
      }
      window.scrollTo({ top: 0, behavior: "smooth" });
    }

    // -----------------------
    // Page wiring
    // -----------------------
    function renderTrustedPills() {
      const wrap1 = document.getElementById("trustedPills");
      const wrap2 = document.getElementById("partnersPills");
      const pill = (name) => {
        const span = document.createElement("span");
        span.className = "text-sm px-3 py-1 rounded-full border border-blue-200 bg-blue-50 text-blue-700";
        span.textContent = name;
        return span;
      };
      [wrap1, wrap2].forEach(w => {
        if (!w) return;
        w.innerHTML = "";
        TRUSTED_BY.forEach(n => w.appendChild(pill(n)));
      });
    }

    function renderProducts() {
      const grid = document.getElementById("productsGrid");
      const select = document.getElementById("productSelect");
      grid.innerHTML = "";
      select.innerHTML = "";
      PRODUCTS.forEach(p => {
        // card
        const card = document.createElement("div");
        card.className = "p-4 border border-blue-200 rounded-lg shadow-sm bg-white";
        card.innerHTML = `
          <div class="flex items-center justify-between">
            <h4 class="font-semibold">${p.name}</h4>
            <div class="text-blue-700 font-bold">${p.rate}</div>
          </div>
          <p class="mt-2 text-sm text-gray-600">${p.desc}</p>
          <div class="mt-4 flex gap-2">
            <button class="px-4 py-2 rounded bg-blue-900 text-white hover:opacity-90">Apply</button>
            <button class="px-4 py-2 rounded border border-blue-900 text-blue-900 hover:bg-blue-50">Top</button>
          </div>
        `;
        const [applyBtn, topBtn] = card.querySelectorAll("button");
        applyBtn.addEventListener("click", () => navigate("apply"));
        topBtn.addEventListener("click", () => window.scrollTo({ top: 0, behavior: "smooth" }));
        grid.appendChild(card);

        // select option
        const opt = document.createElement("option");
        opt.value = p.name;
        opt.textContent = p.name;
        select.appendChild(opt);
      });
    }

    function calcEmi() {
      const amount = document.getElementById("emiAmount").value;
      const years = document.getElementById("emiYears").value;
      const rate = document.getElementById("emiRate").value;
      const val = computeEmi(amount, rate, years);
      const out = document.getElementById("emiOut");
      out.textContent = val == null ? "—" : ("₹ " + val.toLocaleString("en-IN", { maximumFractionDigits: 2 }));
    }

    function bindForms() {
      // Apply form
      const form = document.getElementById("applyForm");
      form.addEventListener("submit", (e) => {
        e.preventDefault();
        const data = Object.fromEntries(new FormData(form).entries());
        if (!data.name || !data.phone) {
          alert("Please add name & phone");
          return;
        }
        const entry = { id: Date.now(), ...data };
        const list = [entry, ...loadSubmissions()];
        saveSubmissions(list);
        form.reset();
        navigate("thanks");
        refreshAdminTable();
      });

      // Admin login
      document.getElementById("adminLoginForm").addEventListener("submit", (e) => {
        e.preventDefault();
        const u = document.getElementById("adminUser").value;
        const p = document.getElementById("adminPass").value;
        const { user, pass } = getAdminCreds();
        if (u === user && p === pass) {
          sessionStorage.setItem("azar_adminAuth", "true");
          navigate("admin");
          refreshAdminTable();
          // preload settings fields
          const c = getAdminCreds();
          document.getElementById("setUser").value = c.user;
          document.getElementById("setPass").value = c.pass;
        } else {
          alert("Invalid credentials. Please try again.");
        }
      });

      // Settings toggle & submit
      document.getElementById("settingsBtn").addEventListener("click", () => {
        const f = document.getElementById("settingsForm");
        f.classList.toggle("hidden");
      });
      document.getElementById("settingsForm").addEventListener("submit", (e) => {
        e.preventDefault();
        const user = document.getElementById("setUser").value.trim();
        const pass = document.getElementById("setPass").value;
        const ok = setAdminCreds(user, pass);
        alert(ok ? "Admin credentials updated." : "Failed to update credentials.");
      });
    }

    function signOut() {
      sessionStorage.removeItem("azar_adminAuth");
      navigate("home");
    }
    window.signOut = signOut;

    function refreshAdminTable() {
      const tbody = document.getElementById("appsTbody");
      const wrap = document.getElementById("appsTableWrap");
      const empty = document.getElementById("appsEmpty");
      const list = loadSubmissions();
      tbody.innerHTML = "";
      if (!list.length) {
        wrap.classList.add("hidden");
        empty.classList.remove("hidden");
        return;
      }
      wrap.classList.remove("hidden");
      empty.classList.add("hidden");

      list.forEach(row => {
        const tr = document.createElement("tr");
        tr.className = "border-t";
        tr.innerHTML = `
          <td class="p-2">${row.name || "-"}</td>
          <td class="p-2">${row.phone || "-"}</td>
          <td class="p-2">${row.email || "-"}</td>
          <td class="p-2">${row.product || "-"}</td>
          <td class="p-2">${row.amount || "-"}</td>
          <td class="p-2">${row.tenure || "-"}</td>
          <td class="p-2">${row.income || "-"}</td>
          <td class="p-2"><button class="px-3 py-1 rounded bg-red-600 text-white">Delete</button></td>
        `;
        tr.querySelector("button").addEventListener("click", () => {
          const updated = loadSubmissions().filter(x => x.id !== row.id);
          saveSubmissions(updated);
          refreshAdminTable();
        });
        tbody.appendChild(tr);
      });
    }

    // Init
    document.getElementById("year").textContent = new Date().getFullYear();
    renderTrustedPills();
    renderProducts();
    calcEmi();
    bindForms();
    refreshAdminTable();

    // Make header buttons navigate
    document.querySelectorAll(".navbtn").forEach(btn => {
      btn.addEventListener("click", () => navigate(btn.dataset.target));
    });

    // Restore admin session
    if (sessionStorage.getItem("azar_adminAuth")) {
      navigate("admin");
      const c = getAdminCreds();
      document.getElementById("setUser").value = c.user;
      document.getElementById("setPass").value = c.pass;
      refreshAdminTable();
    } else {
      navigate("home");
    }
  </script>
</body>
</html>
