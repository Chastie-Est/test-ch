<!DOCTYPE html>
<html lang="ru">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Счастье-есть — кафе-пиццерия</title>
<style>
*{box-sizing:border-box}
html,body{margin:0;padding:0}
body{font-family:Arial,sans-serif;color:#2A1F1B;background:#FFF8F0}

.info-bar{
  position:fixed;top:0;left:0;right:0;
  z-index:110;background:#2A1F1B;
  color:#fff;font-size:13px;font-weight:700;
}
.info-bar-inner{
  max-width:1200px;margin:0 auto;
  padding:8px 18px;display:flex;
  align-items:center;justify-content:center;
  gap:24px;flex-wrap:wrap;
}
.info-link{color:#FFD8A8;text-decoration:none}
.info-link:hover{text-decoration:underline;color:#fff}
.info-item{color:#fff}

.topbar{
  position:fixed;top:36px;left:0;right:0;
  z-index:100;
  background:rgba(255,248,240,0.94);
  backdrop-filter:blur(10px);
  -webkit-backdrop-filter:blur(10px);
  border-bottom:1px solid rgba(198,93,59,.18);
}
.topbar-inner{
  max-width:1200px;margin:0 auto;
