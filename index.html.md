<!DOCTYPE html>  
<html lang="id">  
<head>  
  <meta charset="UTF-8" />  
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />  
  <title>SIA-P Toko Hambali | Kelompok 3</title>  
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&display=swap" rel="stylesheet" />  
  <style>  
    :root {  
      --bg: #f1f5f9;  
      --surface: #ffffff;  
      --primary: #0d9488;  
      --primary-dark: #0f766e;  
      --success: #16a34a;  
      --danger: #dc2626;  
      --warning: #d97706;  
      --text: #0f172a;  
      --muted: #64748b;  
      --border: #e2e8f0;  
      --radius: 12px;  
      --sidebar: 250px;  
    }  
    * { box-sizing: border-box; margin: 0; padding: 0; }  
    body { font-family: 'Inter', system-ui, sans-serif; background: var(--bg); color: var(--text); line-height: 1.5; }  
    .app { display: flex; min-height: 100vh; }  
    .sidebar { width: var(--sidebar); background: #0f172a; color: #e2e8f0; position: fixed; top: 0; left: 0; bottom: 0; z-index: 100; display: flex; flex-direction: column; transition: transform .25s; }  
    .brand { padding: 18px 16px; border-bottom: 1px solid #1e293b; display: flex; gap: 12px; align-items: center; }  
    .brand-icon { width: 42px; height: 42px; background: var(--primary); border-radius: 10px; display: flex; align-items: center; justify-content: center; font-size: 22px; }  
    .brand h1 { font-size: 15px; color: #fff; }  
    .brand p { font-size: 11px; color: #94a3b8; }  
    .nav { flex: 1; padding: 10px 8px; overflow-y: auto; }  
    .nav  
