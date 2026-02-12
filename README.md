# Portafolio-Web-
Proyecto personal de la creación de un portafolio multimedia web a través del Blog “Space Hey”. // Laura Yiseth Reyes Arias

<style>

/* ===== EFECTO SCANLINES ===== */
body::before {
  content: "";
  display: block;
  position: fixed;
  inset: 0;
  background: linear-gradient(
    rgba(18, 16, 16, 0) 50%,
    rgba(0, 0, 0, 0.25) 50%
  );
  background-size: 100% 2px;
  z-index: 2;
  pointer-events: none;
}

/* ===== FONDO GENERAL ===== */
body {
  margin: 0;

  background-image: url("https://i.pinimg.com/1200x/7b/cf/e1/7bcfe1345282032045d1aa232f24bd87.jpg");
  background-repeat: no-repeat;      
  background-position: center center;  
  background-size: cover;             
  background-attachment: fixed;
}

/* ===== CONTENEDOR PERFIL ===== */
.profile {
  background-color: #546961;
  color: #d8f3dc;
  border: 1.5px solid #52b788;
  box-shadow: 0px 30px 30px #52b788;
}

/* ===== BANNER SUPERIOR ===== */
main:before {
    width: 400;
    margin-bottom: 0px;
    border: 1px solid #bc66ed;
    height: 99px;
    display: block;
    content: "";
    box-shadow: 0px 40px 40px #bc66ed;
    background-image: url(https://i.pinimg.com/1200x/93/62/31/936231a95115433c74f2c731ceacdf07.jpg);
    background-position: center center;
    background-size: cover;
}

/* ===== ESTADO ONLINE ===== */
.online {
  color: #52b788;
}

/* ===== NAVBAR ===== */
nav .top {
  background-color: transparent;
}

nav .links {
  background-color: #b75252;
  font-family: monospace;
  font-size: 12px;
  text-align: center;
}

nav .links a {
  color: #081c15;
}

nav .links li:not(:last-child)::after {
  content: "";
}

/* ===== TITULOS DE SECCIONES ===== */
.profile .blurbs .heading,
.profile .friends .heading,
.profile .contact .heading,
.profile .table-section .heading {
  background-color: #ffffff;
  color: #ffffff;
  display: block;
}

/* ===== SUBTITULOS ===== */
.profile .blurbs .inner h4 {
  color: #52b788;
  font-weight: 700;
}

/* ===== TEXTO ===== */
.profile .blurbs .inner {
  font-family: monospace;
}

/* ===== LINKS ===== */
a {
  color: #52b788;
}

a:hover,
.count {
  color: #95d5b2;
  font-style: italic;
  text-decoration: none;
}




/* ===== TABLAS ===== */
table.details-table,
.details-table td {
  background-color: #afe3c7;
  border-color: #081c15;
}

.details-table td:first-child {
  background: #52b788;
  color: #52b788;
  font-family: monospace;
  font-size: 2px;
  width: 20px;
}

.profile .url-info,
.profile .contact {
  border-color: #081c15;
}

/* ===== COMENTARIOS ===== */
.comments-table td {
  background-color: #081c15;
  font-size: 11px;
}

.comments-table td:first-child {
  background-color: #52b788;
}

.comments-table td:first-child a {
  color: #081c15;
}

.comments-table td a {
  color: #d8f3dc;
}

.comment-replies {
  border-color: #081c15;
}

</style>











<div style="&#10;  background:#eef7ea;&#10;  background-image:radial-gradient(#b9ddb8 1px, transparent 1px);&#10;  background-size:18px 18px;&#10;  border-radius:18px;&#10;  padding:20px;&#10;  font-family:Verdana, Arial, sans-serif;&#10;  color:#2f4f3b;&#10;">

<h2 style="&#10;  color:#4f7f5f;&#10;  border-bottom:2px dashed #b9ddb8;&#10;  padding-bottom:6px;&#10;  margin-bottom:12px;&#10;  font-size:16px;&#10;">
✦ (Titulo Aqui) ✦
</h2>


<!--  -->
<div style="border:2px solid #74c69d; padding:10px; margin-bottom:15px; background:#ffffff;">

  <h3 style="color:#40916c; text-align:center;">(Titulo aqui)</h3>

  <p style="font-size:13px; line-height:1.6;">
    (Info aqui)
    <br/><br/>
  </p>

  <div style="&#10;    display:grid;&#10;    grid-template-columns: repeat(2, 1fr);&#10;    gap:10px;&#10;    justify-items:center;&#10;  ">
    <img src="(Imagenes aqui)" style="width:135px; height:270px; object-fit:cover; border-radius:8px;"/>
    <img src="(Imagenes aqui)" style="width:135px; height:270px; object-fit:cover; border-radius:8px;"/>
    <img src="(Imagenes aqui)" style="width:135px; height:270px; object-fit:cover; border-radius:8px;"/>
    <img src="(Imagenes aqui)" style="width:135px; height:270px; object-fit:cover; border-radius:8px;"/>
  </div>

  <p style="margin-top:10px;">
    (Info aqui)
    <a href="(Link aqui)" target="_blank">
      Drive
    </a>
  </p>

</div>


<p align="center">
  <img src="https://66.media.tumblr.com/9356a5343569692547be79f4fe460829/tumblr_mit6meq11R1rfjowdo1_500.gif" width="200"/>
</p>



<!--  -->
<div style="border:2px solid #74c69d; padding:10px; margin-bottom:15px; background:#ffffff;">

  <h3 style="color:#40916c; text-align:center;">(Titulo aqui)</h3>

  <p style="font-size:13px; line-height:1.6;">
    (Info aqui)
    <br/><br/>
  </p>

  <div style="&#10;    display:grid;&#10;    grid-template-columns: repeat(2, 1fr);&#10;    gap:10px;&#10;    justify-items:center;&#10;  ">
    <img src="(Imagenes aqui)" style="width:135px; height:270px; object-fit:cover; border-radius:8px;"/>
    <img src="(Imagenes aqui)" style="width:135px; height:270px; object-fit:cover; border-radius:8px;"/>
    <img src="(Imagenes aqui)" style="width:135px; height:270px; object-fit:cover; border-radius:8px;"/>
  </div>

  <p style="margin-top:10px;">
    9Info aqui)
    <a href="(Link aqui)" target="_blank">
      Drive
    </a>
  </p>

</div>


<!--  -->
<div style="border:2px solid #74c69d; padding:10px; margin-bottom:15px; background:#ffffff;">

  <h3 style="color:#40916c; text-align:center;">(Titulo aqui)</h3>

  <p style="font-size:13px; line-height:1.6;">
    (Info aqui)
    <br/><br/>
  </p>

  <div style="&#10;    display:grid;&#10;    grid-template-columns: repeat(2, 1fr);&#10;    gap:10px;&#10;    justify-items:center;&#10;  ">
    <img src="(Imagenes aqui)" style="width:135px; height:270px; object-fit:cover; border-radius:8px;"/>
    <img src="(Imagenes aqui)" style="width:135px; height:270px; object-fit:cover; border-radius:8px;"/>
    <img src="(Imagenes aqui)" style="width:135px; height:270px; object-fit:cover; border-radius:8px;"/>
    <img src="(Imagenes aqui)" style="width:135px; height:270px; object-fit:cover; border-radius:8px;"/>
  </div>

  <p style="margin-top:10px;">
    (Info aqui)
    <a href="(Link aqui)" target="_blank">
      Drive
    </a>
  </p>

</div>


  <!--  -->
  <div style="border:2px solid #74c69d; padding:10px; margin-bottom:15px; background:#ffffff;">
    <h3 style="color:#40916c; text-align:center;">(Info aqui)</h3>
<p style="font-size:13px; line-height:1.6;">
  (Info aqui)
  <br/><br/>
</p>
    <img src="(Imagenes aqui)" width="400"/>
    <img src="(Imagenes aqui)" width="400"/>
    <img src="(Imagenes aqui)" width="300"/>
    <p>
      Proceso completo en:
      <a href="(Link aqui)" target="_blank">
        Drive
      </a>
    </p>
  </div>

<p align="center">
  <img src="https://i.pinimg.com/originals/4e/7e/ea/4e7eeaf84daa7a9e8de904a5a26ad186.gif" width="200"/>
</p>

<!--  -->
<div style="border:2px solid #74c69d; padding:10px; margin-bottom:15px; background:#ffffff;">

  <h3 style="color:#40916c; text-align:center;">(Info aqui)</h3>

  <p style="font-size:13px; line-height:1.6;">
    (Info aqui)
    <br/><br/>
  </p>

  <div style="&#10;    display:grid;&#10;    grid-template-columns: repeat(auto-fill, minmax(200px, 1fr));&#10;    gap:10px;&#10;    justify-items:center;&#10;  ">
    <img src="(Imagenes aqui)" style="width:200px; height:200px; object-fit:cover; border-radius:8px;"/>
    <img src="(Imagenes aqui)" style="width:200px; height:200px; object-fit:cover; border-radius:8px;"/>
    <img src="(Imagenes aqui)" style="width:200px; height:200px; object-fit:cover; border-radius:8px;"/>
    <img src="(Imagenes aqui)" style="width:200px; height:200px; object-fit:cover; border-radius:8px;"/>
    <img src="(Imagenes aqui)" style="width:200px; height:200px; object-fit:cover; border-radius:8px;"/>
    <img src="(Imagenes aqui)" style="width:200px; height:200px; object-fit:cover; border-radius:8px;"/>
    <img src="(Imagenes aqui)" style="width:200px; height:200px; object-fit:cover; border-radius:8px;"/>
    <img src="(Imagenes aqui)" style="width:200px; height:200px; object-fit:cover; border-radius:8px;"/>
    <img src="(Imagenes aqui)" style="width:200px; height:200px; object-fit:cover; border-radius:8px;"/>
  </div>

  <p style="margin-top:10px;">
    (Info aqui)
    <a href=(Link aqui) target="_blank">
      Drive
    </a>
  </p>
</div>


  <!--  -->
  <div style="border:2px solid #74c69d; padding:10px; margin-bottom:15px; background:#ffffff;">
    <h3 style="color:#40916c; text-align:center;">(Info aqui)</h3>
<p style="font-size:13px; line-height:1.6;">
  (Info aqui)
  <br/><br/>
</p>
    <img src="(Imagenes aqui)" width="400"/>
    <p>
      Ver en:
      <a href=(Link aqui) target="_blank">
        Drive
      </a>
    </p>
  </div>

<p align="center">
  <img src="https://i.pinimg.com/originals/e8/d0/f1/e8d0f1794e2520ac2367c1d21c0966e9.gif" width="200"/>
</p>

  <!--  -->
  <div style="border:2px solid #74c69d; padding:10px; margin-bottom:15px; background:#ffffff;">
    <h3 style="color:#40916c; text-align:center;">(Info aqui)</h3>
<p style="font-size:13px; line-height:1.6;">
  (Info aqui)
  <br/><br/>
</p>
    <img src="(Imagenes aqui)" width="400"/>
    <p>
      (Info aqui)
      <a href=9Link aqui) target="_blank">
        Drive
      </a>
    </p>
  </div>


  <p>
    📁 <strong> ✦ (Info aqui)</strong>
    <a href=(Link aqui) target="_blank">
      Ver aquí
    </a>
  </p>

<p align="center">
  <img src="https://media4.giphy.com/media/v1.Y2lkPTZjMDliOTUycWU5dzdrMDBjZWF2amIxeGJ1cTZra2lnemplcGdoNGMxamRkc2ZmdSZlcD12MV9zdGlja2Vyc19zZWFyY2gmY3Q9cw/ao9DUiTKH60XS/200w.gif" width="200"/>
</p>

  <h2 style="color:#2d6a4f;"> ✦ (Info aqui) ✦ </h2>

<!-- HC2 -->
<div style="border:2px solid #52b788; padding:10px; background:#ffffff;">

  <h3 style="color:#40916c; text-align:center;">(Info aqui)</h3>

  <p>
    (Info aqui)
  </p>
   <br/><br/>
  <div style="&#10;    display:grid;&#10;    grid-template-columns: repeat(1, 1fr);&#10;    gap:10px;&#10;    justify-items:center;&#10;  ">
    <img src="(Imagenes aqui)" style="width:200px; height:200px; object-fit:cover; border-radius:8px;"/>
    <img src="(Imagenes aqui)" style="width:200px; height:200px; object-fit:cover; border-radius:8px;"/>
  </div>

  <p style="margin-top:10px;">
    (Info aqui)
    <a href=(Link aqui) target="_blank">
      Drive
    </a>
  </p>

</div>


  <!--  -->
  <div style="border:2px solid #52b788; padding:10px; margin-top:15px; background:#ffffff;">
    <h3 style="color:#40916c; text-align:center;">(Info aqui)</h3>
    <p>
     (Info aqui)
    </p>
  </div>

<h2 style="&#10;  color:#74b89c;&#10;  border-bottom:2px dashed #b9ddb8;&#10;  padding-bottom:6px;&#10;  margin:20px 0 12px;&#10;  font-size:16px;&#10;">
✿ (Info aqui) ✿
</h2>

<ul style="&#10;  list-style:none;&#10;  padding:0;&#10;  margin:0;&#10;  font-size:13px;&#10;  line-height:1.7;&#10;">
  <li style="margin-bottom:8px;">
    ✦ <strong>(Info aqui)</strong> (Info aqui)<br/>
    ↳ <a href=(Link aqui) target="_blank" style="color:#74b89c; font-weight:bold;">View project →</a>
  </li>

  <li style="margin-bottom:8px;">
    ✦ <strong>(Info aqui)</strong> (Info aqui)<br/>
    ↳ <a href=(Link aqui) target="_blank" style="color:#74b89c; font-weight:bold;">View project →</a>
  </li>

  <li style="margin-bottom:8px;">
    ✦ <strong>(Info aqui)</strong> (Info aqui)<br/>
    ↳ <a href=(Link aqui) target="_blank" style="color:#74b89c; font-weight:bold;">View project →</a>
  </li>

  <li style="margin-bottom:8px;">
    ✦ <strong>(Info aqui)</strong> (Info aqui)<br/>
    ↳ <a href=(Link aqui) target="_blank" style="color:#74b89c; font-weight:bold;">View project →</a>
  </li>

  <li>
    ✦ <strong>(Info aqui)</strong> (Info aqui)<br/>
    ↳ <a href=(Link aqui) target="_blank" style="color:#74b89c; font-weight:bold;">View project →</a>
  </li>

<li style="margin-bottom:8px;">
    ✦ <strong>(Info aqui)</strong> (Info aqui)<br/>
    ↳ <a href=(Link aqui) target="_blank" style="color:#74b89c; font-weight:bold;">View CV →</a>
  </li>
</ul>

<h2 style="color:#2d6a4f;"> ✦ (Info aqui) ✦ </h2>

<!--  -->
<div style="border:2px solid #74c69d; padding:10px; margin-bottom:20px; background:#ffffff;">

  <h3 style="color:#40916c; text-align:center;">(Info aqui)</h3>

  <p style="font-size:13px; line-height:1.6;">
    A(Info aqui)
    <br/><br/>
  </p>

  <div style="&#10;    display:grid;&#10;    grid-template-columns: repeat(1, 1fr);&#10;    gap:10px;&#10;    justify-items:center;&#10;  ">
    <img src=(Imagenes aqui) style="width:200px; height:200px; object-fit:cover; border-radius:8px;"/>
    <img src=(Imagenes aqui) style="width:180px; height:300px; object-fit:cover; border-radius:8px;"/>
  </div>

  <p style="margin-top:10px;">
    (Info aqui)
    <a href=(Link aqui) target="_blank">
      Drive
    </a>
  </p>

</div>


<!--  -->
<div style="border:2px solid #74c69d; padding:10px; margin-bottom:20px; background:#ffffff;">

  <h3 style="color:#40916c; text-align:center;">(Info aqui)</h3>

  <p style="font-size:13px; line-height:1.6;">
    (Info aqui)
    <br/><br/>
  </p>

  <div style="&#10;    display:grid;&#10;    grid-template-columns: repeat(1, 1fr);&#10;    gap:10px;&#10;    justify-items:center;&#10;  ">
    <img src=(Imagenes aqui) style="width:400px; height:180px; object-fit:cover; border-radius:8px;"/>
    <img src=*Imagenes aqui) style="width:135px; height:270px; object-fit:cover; border-radius:8px;"/>
  </div>

  <p style="margin-top:10px;">
    (Info aqui)
    <a href=(Link aqui) target="_blank">
      Drive
    </a>
  </p>

</div></div>







<div style="&#10;  background:#eef7ea;&#10;  background-image:radial-gradient(#b9ddb8 1px, transparent 1px);&#10;  background-size:18px 18px;&#10;  border-radius:18px;&#10;  padding:20px;&#10;  font-family:Verdana, Arial, sans-serif;&#10;  color:#2f4f3b;&#10;">

<h2 style="&#10;  color:#4f7f5f;&#10;  border-bottom:2px dashed #b9ddb8;&#10;  padding-bottom:6px;&#10;  margin-bottom:12px;&#10;  font-size:16px;&#10;">
✦ (Info aqui) ✦
</h2>

<p style="font-size:13px; line-height:1.6;">
(Info aqui)
</p>

</div>

<style>* {cursor: url(https://pixels.crd.co/assets/images/gallery106/6a88de1c.gif?v=29416114), auto !important;}<style/></style>




<div style="&#10;  background:#eef7ea;&#10;  background-image:radial-gradient(#b9ddb8 1px, transparent 1px);&#10;  background-size:18px 18px;&#10;  border-radius:18px;&#10;  padding:20px;&#10;  font-family:Verdana, Arial, sans-serif;&#10;  color:#2f4f3b;&#10;">

  <!-- General -->
  <h2 style="&#10;    color:#4f7f5f;&#10;    border-bottom:2px dashed #b9ddb8;&#10;    padding-bottom:6px;&#10;    margin-bottom:12px;&#10;    font-size:16px;&#10;  ">
    ✦ (Info aqui) ✦
  </h2>

  <p style="font-size:13px; line-height:1.6;">
    (Info aqui)
  </p>
<br/>
  <li style="margin-bottom:8px;">
    ✦ <strong>(Info aqui)</strong> (Info aqui) <br/>
    ↳ <a href=(Link aqui)" style="color:#74b89c; font-weight:bold;">View Git →</a>

  </li>
</div>




<div style="&#10;  background:#eef7ea;&#10;  background-image:radial-gradient(#b9ddb8 1px, transparent 1px);&#10;  background-size:18px 18px;&#10;  border-radius:18px;&#10;  padding:20px;&#10;  font-family:Verdana, Arial, sans-serif;&#10;  color:#2f4f3b;&#10;">

<h2 style="&#10;  color:#4f7f5f;&#10;  border-bottom:2px dashed #b9ddb8;&#10;  padding-bottom:6px;&#10;  margin-bottom:12px;&#10;  font-size:16px;&#10;">

  <!-- General -->
  <h2 style="&#10;    color:#4f7f5f;&#10;    border-bottom:2px dashed #b9ddb8;&#10;    padding-bottom:6px;&#10;    margin-bottom:12px;&#10;    font-size:16px;&#10;  ">
    ✦ (Info aqui) ✦
  </h2>

  </h2><p style="font-size:11px; line-height:1.6;">
    (Info aqui)
    <br/><br/>
  </p>

</div>

