<!DOCTYPE html>
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>You're Invited! - Lovemae Dec 29</title>
<style>
body { font-family: 'Segoe UI'; background: linear-gradient(135deg,#ff9a9e,#fecfef); display:flex; justify-content:center; align-items:center; min-height:100vh; margin:0; }
.card { background:white; padding:30px; border-radius:20px; box-shadow:0 10px 30px rgba(0,0,0,0.2); text-align:center; max-width:350px; width:90%; }
h1 { color:#ff6b81; }
.name { color:#ff4757; font-size:32px; font-weight:bold; margin:15px 0; }
.date { background:#ff6b81; color:white; padding:10px 20px; border-radius:30px; display:inline-block; margin:15px 0; }
</style>
</head>
<body>
<div class="card">
<h1>🎉 You're Invited! 🎉</h1>
<div class="name" id="guestName">Hi Friend!</div>
<p>Join us to celebrate</p>
<h2>Lovemae's Birthday</h2>
<div class="date">December 29</div>
<p>We can't wait to see you!</p>
<p style="margin-top:20px">📍 Venue: TBA</p>
<p>🕕 Time: 6PM</p>
</div>

<script>
// ?name= magic!
const params = new URLSearchParams(window.location.search);
const name = params.get('name');
if(name){
  document.getElementById('guestName').innerHTML = `Hi, ${name}! ❤️`;
}
</script>
</body>
</html>
