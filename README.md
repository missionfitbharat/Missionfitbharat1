<!DOCTYPE html>
<html lang="mr">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Mission Fit Bharat</title>

<style>
body{
  margin:0;
  font-family: Arial, sans-serif;
  background:#f4f6f8;
  color:#222;
}
.hero{
  background:#1abc9c;
  color:#fff;
  padding:40px 20px;
  text-align:center;
}
.hero h1{margin-bottom:10px}
.btn{
  display:inline-block;
  padding:12px 22px;
  background:#e74c3c;
  color:#fff;
  text-decoration:none;
  border-radius:6px;
  margin:10px;
  font-weight:bold;
}
section{padding:30px 15px}
.box{
  background:#fff;
  padding:20px;
  margin:15px auto;
  max-width:500px;
  border-radius:10px;
  box-shadow:0 0 10px rgba(0,0,0,0.1);
}
h2{text-align:center;color:#1abc9c}

input, button{
  width:100%;
  padding:12px;
  margin-top:10px;
  border-radius:6px;
  border:1px solid #ccc;
  font-size:16px;
}
button{
  background:#1abc9c;
  color:#fff;
  border:none;
  cursor:pointer;
  font-weight:bold;
}
.social{
  text-align:center;
  margin-top:20px;
}
.social a{
  margin:0 10px;
  text-decoration:none;
  font-weight:bold;
  color:#1abc9c;
}
.footer{
  background:#222;
  color:#fff;
  text-align:center;
  padding:15px;
  font-size:14px;
}
.whatsapp-float{
  position:fixed;
  bottom:20px;
  right:20px;
  background:#25d366;
  color:#fff;
  padding:14px 18px;
  border-radius:50%;
  text-decoration:none;
  font-size:20px;
}
</style>
</head>

<body>

<!-- HERO -->
<div class="hero">
  <h1>Mission Fit Bharat</h1>
  <p>वजन कमी करा | वजन वाढवा | आजारांवर नियंत्रण मिळवा</p>
  <p>BP | Sugar | Thyroid | PCOD/PCOS | Back Pain | Knee Pain</p>
  <a class="btn" href="#form">5 Days FREE Trial</a>
  <a class="btn" href="https://wa.me/918605331586">WhatsApp Call</a>
</div>

<!-- PROGRAMS -->
<section>
<h2>आमचे Programs</h2>
<div class="box">✅ वजन कमी करणे / Weight Loss</div>
<div class="box">✅ वजन वाढवणे / Weight Gain</div>
<div class="box">✅ BP | Sugar | Thyroid | PCOD / PCOS</div>
<div class="box">✅ Back Pain | Knee Pain</div>
<div class="box">✅ लहान मुलांचे आरोग्य</div>
</section>

<!-- LEAD FORM -->
<section id="form">
<h2>FREE Trial साठी फॉर्म भरा</h2>

<div class="box">
<form onsubmit="sendWhatsApp(); return false;">
  <input type="text" id="name" placeholder="तुमचे नाव" required>
  <input type="tel" id="mobile" placeholder="मोबाईल नंबर" required>
  <button type="submit">FREE Trial Join करा</button>
</form>
</div>
</section>

<!-- SOCIAL MEDIA -->
<section>
<h2>आमच्याशी कनेक्ट व्हा</h2>
<div class="social">
 <a href="https://www.instagram.com/missionfitbharat1?igsh=cTU1aDBlYWFrN2x6" target="_blank">📸 Instagram</a>
  <a href="https://www.facebook.com/share/16QjWUMzsk/" target="_blank">📘 Facebook</a>
  <a href="https://www.youtube.com/@Missionfitbharat1" target="_blank">▶️ YouTube</a>
</div>
</section>

<!-- FOOTER -->
<div class="footer">
© 2025 Mission Fit Bharat | All Rights Reserved
</div>

<!-- FLOATING WHATSAPP -->
<a class="whatsapp-float" href="https://wa.me/918605331586">💬</a>

<!-- SCRIPT -->
<script>
function sendWhatsApp(){
  var name = document.getElementById("name").value;
  var mobile = document.getElementById("mobile").value;
  var text = "नमस्कार, मला Mission Fit Bharat चा 5 Days FREE Trial हवा आहे.%0Aनाव: "
              + name + "%0Aमोबाईल: " + mobile;
  window.open("https://wa.me/918605331586?text=" + text, "_blank");
}
</script>

</body>
</html>
