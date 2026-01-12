# MiniGameHubPro
<!DOCTYPE html>
<html lang="vi">
<head>
<meta charset="UTF-8">
<title>Mini Game Hub Pro</title>
<meta name="viewport" content="width=device-width, initial-scale=1.0, user-scalable=no">
<style>
  body { font-family: 'Segoe UI', sans-serif; background: linear-gradient(to right,#0f2027,#203a43,#2c5364); color:#fff; margin:0; padding:0; display:flex; flex-direction:column; justify-content:center; align-items:center; height:100vh; }
  h1 { font-size:32px; color:#ffd700; text-shadow:2px2px5px #000; margin:20px; }
  button { font-size:20px; margin:10px; padding:15px 30px; border:none; border-radius:10px; cursor:pointer; background: linear-gradient(45deg,#ff5e5e,#ff2e2e); color:white; transition:0.3s; }
  button:hover { background: linear-gradient(45deg,#ff8c00,#ffa500); }
  .game { display:none; margin-top:20px; text-align:center; width:100%; }
  .dice { font-size:60px; margin:20px; }
  .result { font-size:28px; margin:20px; font-weight:bold; text-shadow:1px1px5px #000; }
  .score { font-size:24px; margin:10px; }
  .flash { animation: flash 0
