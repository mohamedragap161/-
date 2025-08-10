<!doctype html>
<html lang="ar" dir="rtl">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>مركز التخاطب والتعليم — موارد وتمارين</title>
  <meta name="description" content="موقع لمساعدة ذوي الاحتياجات الخاصة في التخاطب: تمارين، موارد، فيديوهات، ومواد قابلة للتحميل." />
  <style>
    :root{--accent:#2b7a78;--muted:#f3f4f6;--card:#ffffff;--text:#111827}
    *{box-sizing:border-box}
    body{font-family:system-ui,-apple-system,Segoe UI,Roboto,'Noto Kufi Arabic',Tahoma,Arial;line-height:1.5;margin:0;background:linear-gradient(180deg,#fbfeff 0%, #f7fbfb 100%)}
    header{background:var(--accent);color:white;padding:18px 12px;display:flex;gap:12px;align-items:center;justify-content:space-between}
    .brand{display:flex;gap:12px;align-items:center}
    .logo{width:48px;height:48px;border-radius:8px;background:#fff7;padding:6px;display:flex;align-items:center;justify-content:center;color:var(--accent);font-weight:700}
    nav a{color:white;text-decoration:none;margin-left:12px}
    main{max-width:1000px;margin:22px auto;padding:0 12px}
    .grid{display:grid;grid-template-columns:1fr 320px;gap:18px}
    .card{background:var(--card);padding:16px;border-radius:12px;box-shadow:0 6px 18px rgba(16,24,40,0.06)}
    h1,h2{margin:0 0 8px 0}
    .hero{display:flex;gap:12px;align-items:center}
    .hero p{margin:0;color:#0f172a}
    .btn{display:inline-block;padding:10px 14px;border-radius:10px;background:var(--accent);color:white;text-decoration:none}
    .small{font-size:14px;color:#546070}
    .articles{display:flex;flex-direction:column;gap:12px}
    .article{padding:12px;border-radius:10px;border:1px solid #eef2f6}
    .meta{font-size:13px;color:#6b7280}
    .sidebar .resource{display:flex;gap:10px;align-items:center;padding:10px;border-radius:8px;border:1px dashed #e6eef0}
    footer{max-width:1000px;margin:18px auto;padding:12px;color:#475569;font-size:14px}
    @media(max-width:880px){.grid{grid-template-columns:1fr}.sidebar{order:2}}
    .ltr{direction:ltr;text-align:left}
  </style>
</head>
<body>
  <header>
    <div class="brand">
      <div class="logo">تخ</div>
      <div>
        <div style="font-weight:700">مركز التخاطب</div>
        <div style="font-size:13px;opacity:.9">موارد وتمارين لذوي الاحتياجات الخاصة</div>
      </div>
    </div>
    <nav>
      <a href="#home">الرئيسية</a>
      <a href="#articles">مقالات</a>
      <a href="#downloads">تحميلات</a>
      <a href="#contact">تواصل</a>
    </nav>
  </header>
  <main>
    <section class="card hero" id="home">
      <div style="flex:1">
        <h1>مرحبا بك في مركز التخاطب</h1>
        <p class="small">دروس وتمارين وأدوات مجانية تساعد الأطفال والبالغين على تحسين النطق ومهارات التواصل.</p>
        <div style="margin-top:12px">
          <a class="btn" href="#articles">ابدأ بالتمارين</a>
          <a class="btn" style="background:#fff;color:var(--accent);margin-right:8px;border:1px solid rgba(255,255,255,0.15)" href="#downloads">تحميل مواد مجانية</a>
        </div>
      </div>
      <div style="width:220px;text-align:center">
        <img src="data:image/svg+xml;utf8,<svg xmlns='http://www.w3.org/2000/svg' width='180' height='120'><rect width='100%' height='100%' rx='12' fill='%232b7a78'/><text x='50%' y='50%' font-size='20' fill='white' text-anchor='middle' dominant-baseline='middle'>صورة توضيحية</text></svg>" alt="أيقونة" style="width:100%;border-radius:8px"/>
      </div>
    </section>
    <div class="grid" style="margin-top:18px">
      <section class="card" id="articles">
        <h2>مقالات وتمارين مفيدة</h2>
        <div class="articles" id="articlesList"></div>
        <div style="margin-top:12px">
          <strong>أضف مقالة تجريبية (محليًا)</strong>
          <div style="display:flex;gap:8px;margin-top:8px;flex-wrap:wrap">
            <input id="aTitle" placeholder="عنوان المقالة" style="flex:1;padding:8px;border-radius:8px;border:1px solid #e6eef0" />
            <button class="btn" onclick="addArticle()">أضف</button>
          </div>
          <div class="small" style="margin-top:8px">المقالات تحفظ مؤقتًا في متصفحك (localStorage) للتجربة. للنشر الحقيقي ستحتاج لوحة تحكم أو رفع ملفات على الخادم.</div>
        </div>
      </section>
      <aside class="sidebar card">
        <h3>موارد سريعة</h3>
        <div class="resource" style="margin-top:8px">
          <div style="flex:1">
            <div style="font-weight:700">كتيب تمارين نطق (PDF)</div>
            <div class="small">تحميل مجاني للطباعة</div>
          </div>
          <a href="#downloads" class="btn" style="padding:6px 8px">تحميل</a>
        </div>
        <div style="margin-top:12px">
          <h4>فيديوهات تعليمية</h4>
          <div class="small">روّج لقناة يوتيوب أو أدرج فيديوهات توضيحية هنا.</div>
        </div>
        <div style="margin-top:12px">
          <h4>روابط مفيدة</h4>
          <ul style="padding-left:14px;margin:6px 0">
            <li><a href="#">موقع جمعية التخاطب</a></li>
            <li><a href="#">أدوات نطق مجانية</a></li>
          </ul>
        </div>
        <div style="margin-top:14px;border-top:1px dashed #eef2f6;padding-top:12px">
          <div class="small">إعلان تجريبي (مكان مخصص لإعلانات AdSense)</div>
          <div style="margin-top:8px;padding:10px;border-radius:8px;background:linear-gradient(180deg,#fbfbfb,#fff);text-align:center;color:#334155">[مكان إعلان]</div>
        </div>
      </aside>
    </div>
    <section class="card" id="downloads" style="margin-top:18px">
      <h2>تحميلات مجانية</h2>
      <div style="display:grid;grid-template-columns:repeat(auto-fit,minmax(220px,1fr));gap:12px;margin-top:12px">
        <div class="card">
          <h4>كتيب تمارين نطق — المستوى الأساسي</h4>
          <p class="small">ملف PDF يحتوي تمارين منزلية بسيطة.</p>
          <a class="btn" href="#">تحميل PDF</a>
        </div>
        <div class="card">
          <h4>كروت كلمات جاهزة للطباعة</h4>
          <p class="small">مجموعة بطاقات صور وكلمات لتقوية المفردات.</p>
          <a class="btn" href="#">تحميل</a>
        </div>
      </div>
    </section>
    <section class="card" id="contact" style="margin-top:18px">
      <h2>تواصل معنا</h2>
      <p class="small">للاستفسارات أو طلب استشارة (هذه النموذج يرسل إلى البريد الإلكتروني في حال وصل إلى خادم فعلي).</p>
      <form onsubmit="event.preventDefault();submitContact()" style="display:flex;flex-direction:column;gap:8px;max-width:620px">
        <input id="name" placeholder="الاسم" required style="padding:10px;border-radius:8px;border:1px solid #eef2f6" />
        <input id="email" placeholder="البريد الإلكتروني" required class="ltr" style="padding:10px;border-radius:8px;border:1px solid #eef2f6" />
        <textarea id="message" placeholder="نص الرسالة" rows="4" style="padding:10px;border-radius:8px;border:1px solid #eef2f6"></textarea>
        <div style="display:flex;gap:8px">
          <button class="btn" type="submit">أرسل</button>
          <button type="button" onclick="clearForm()" style="background:#ef4444;color:#fff;border-radius:8px;padding:10px;border:none">مسح</button>
        </div>
        <div id="contactResult" class="small"></div>
      </form>
    </section>
  </main>
  <footer>
    © حقوق النشر — مركز التخاطب. هذا موقع تجريبي للتعلم. لا يعرض محتوى طبي احترافي.
  </footer>
  <script>
    const demoArticles = [
      {id:1,title:'تمارين نطق للحروف الساكنة',excerpt:'سلسلة تمارين منزلية لتقوية مخرجات الحروف الساكنة.',date:'2025-08-10'},
      {id:2,title:'أنشطة لتقوية التواصل غير اللفظي',excerpt:'ألعاب بسيطة لتشجيع التواصل البصري والتعابير.',date:'2025-08-10'}
    ];
    function loadArticles(){
      const raw = localStorage.getItem('site_articles');
      let list = raw ? JSON.parse(raw) : demoArticles;
      const container = document.getElementById('articlesList');
      container.innerHTML = '';
      list.slice().reverse().forEach(a=>{
        const el = document.createElement('div');
        el.className='article';
        el.innerHTML = `<div style="display:flex;justify-content:space-between;align-items:center"><div><strong>${escapeHtml(a.title)}</strong><div class='meta'>${a.date}</div></div><div><button onclick="viewArticle(${a.id})" style='padding:6px 8px;border-radius:8px'>عرض</button></div></div><p class='small' style='margin-top:8px'>${escapeHtml(a.excerpt || '')}</p>`;
        container.appendChild(el);
      });
    }
    function addArticle(){
      const title = document.getElementById('aTitle').value.trim();
      if(!title) return alert('أدخل عنوانًا');
      const raw = localStorage.getItem('site_articles');
      let list = raw ? JSON.parse(raw) : demoArticles.slice();
      const id = Date.now();
      list.push({id,title,excerpt:'مقال تجريبي. حرر هذا النص من خلال لوحة التحكم.',date:new Date().toISOString().slice(0,10)});
      localStorage.setItem('site_articles',JSON.stringify(list));
      document.getElementById('aTitle').value = '';
      loadArticles();
    }
    function viewArticle(id){
      const raw = localStorage.getItem('site_articles');
      const list = raw ? JSON.parse(raw) : demoArticles;
      const a = list.find(x=>x.id==id);
      if(!a) return alert('المقال غير موجود');
      alert(a.title + '\n\n' + (a.excerpt||'لا يوجد محتوى مفصل — هذه نسخة تجريبية'));
    }
    function submitContact(){
      const name = document.getElementById('name').value.trim();
      const email = document.getElementById('email').value.trim();
      const message = document.getElementById('message').value.trim();
      if(!name || !email || !message) return document.getElementById('contactResult').textContent='الرجاء تعبئة الحقول';
      document.getElementById('contactResult').textContent='تم الإرسال (تجريبي) — في موقع حقيقي سيُرسل إلى بريدك.';
      document.getElementById('name').value='';document.getElementById('email').value='';document.getElementById('message').value='';
    }
    function clearForm(){
      document.getElementById('name').value='';document.getElementById('email').value='';document.getElementById('message').value='';
      document.getElementById('contactResult').textContent='';
    }
    function escapeHtml(text){
      return (text||'').replace(/[&<>\"']/g,function(c){return {'&':'&amp;','<':'&lt;','>':'&gt;','\"':'&quot;',"'":'&#39;'}[c]});
    }
    loadArticles();
  </script>
</body>
</html>
