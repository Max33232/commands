/* style.css */
:root{
  --bg:#000;
  --panel:#0b0b0b;
  --muted:#9aa0a6;
  --accent:#1e90ff;
  --white:#ffffff;
  --code-bg:#071018;
}
*{box-sizing:border-box;font-family:Inter, system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial;}
html,body{height:100%;margin:0;background:var(--bg);color:var(--white);}
.container{
  max-width:980px;
  margin:32px auto;
  padding:28px;
  position:relative;
  border-radius:8px;
}
.header{
  display:flex;
  align-items:center;
  gap:16px;
  justify-content:center;
  margin-bottom:8px;
}
.icon{
  width:48px;
  height:48px;
  object-fit:contain;
  border-radius:6px;
  background:linear-gradient(180deg,#0f7a1a,#0b5a12);
  padding:6px;
}
.title{
  font-size:20px;
  letter-spacing:0.6px;
}
.emojis{
  position:absolute;
  right:18px;
  top:18px;
  font-size:20px;
  user-select:none;
}
.editor{
  display:flex;
  gap:16px;
  align-items:flex-start;
  margin-top:12px;
  flex-wrap:wrap;
}
.controls{
  flex:1 1 620px;
  min-width:280px;
}
textarea#commandInput{
  width:100%;
  min-height:160px;
  max-height:360px;
  background:var(--panel);
  color:var(--white);
  border:1px solid #1c1c1c;
  padding:12px;
  border-radius:6px;
  resize:vertical;
  font-size:14px;
  line-height:1.4;
}
.meta{
  display:flex;
  justify-content:space-between;
  align-items:center;
  margin-top:8px;
  gap:12px;
}
.counter{color:var(--muted);font-size:13px;}
.generate{
  background:var(--accent);
  color:var(--white);
  border:none;
  padding:10px 16px;
  border-radius:6px;
  cursor:pointer;
  font-weight:600;
  box-shadow:0 4px 10px rgba(30,144,255,0.16);
}
.generate:active{transform:translateY(1px);}
.preview{
  flex:1 1 300px;
  min-width:240px;
  background:var(--code-bg);
  border-radius:8px;
  padding:12px;
  font-family:ui-monospace,SFMono-Regular,Menlo,Monaco,"Roboto Mono","Courier New",monospace;
  font-size:13px;
  color:#cfeefc;
  max-height:360px;
  overflow:auto;
  position:relative;
  border:1px solid rgba(255,255,255,0.04);
}
.copy-btn{
  position:absolute;
  right:12px;
  top:12px;
  background:rgba(255,255,255,0.06);
  color:var(--white);
  border:none;
  padding:6px 8px;
  border-radius:6px;
  cursor:pointer;
  font-size:12px;
}
.hint{color:var(--muted);font-size:13px;margin-top:10px;}
.small{font-size:12px;color:var(--muted);margin-top:6px;}
