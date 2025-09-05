!DOCTYPE html> 
<!-- saved from url=(0031)https://www.runoob.com/runcode# --> 
<html lang="ja"><head><meta http-equiv="Content-Type" content="text/html; charset=UTF-8"> 
 <meta name="viewport" content="width=device-width, initial-scale=1.0"> 
<title>良辰株式会社 - カスタマイズ可能なウェブテンプレート</title> 
<link rel="stylesheet" href="./良辰株式会社 - カスタマイズ可能なウェブテンプレート_files/all.min.css"> 
<style> 
:root { 
--primary-color: #ab0f02; 
--secondary-color: #1a1a1a; 
--background-color: #f8f8f8; 
--text-color: #333333; 
--accent-color: #d4af37; 
--font-family: 'Helvetica Neue', Arial, 'Hiragino Sans', Meiryo, sans-serif; 
} 
 * { 
margin: 0; 
padding: 0; 
box-sizing: border-box; 
transition: all 0.3s ease; 
} 
 body { 
background-color: var(--background-color); 
color: var(--text-color); 
line-height: 1.6; 
font-family: var(--font-family); 
} 
 .container { 
max-width: 1200px; 
margin: 0 auto; 
padding: 0 20px; 
} 
 /* ヘッダー */ 
header { 
background-color: var(--background-color); 
box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1); 
position: sticky; 
top: 0; 
z-index: 100; 
} 
 .header-content { 
display: flex; 
justify-content: space-between; 
align-items: center; 
padding: 20px 0; 
} 
 .logo { 
display: flex; 
align-items: center; 
} 
 .logo-circle { 
width: 40px; 
height: 40px; 
background-color: var(--primary-color); 
border-radius: 50%; 
margin-right: 10px; 
} 
 .logo-text { 
font-size: 24px; 
font-weight: 700; 
color: var(--secondary-color); 
} 
 .logo-highlight { 
color: var(--primary-color); 
} 
 nav ul { 
display: flex; 
list-style: none; 
} 
 nav li { 
margin-left: 30px; 
} 
 nav a { 
text-decoration: none; 
color: var(--text-color); 
font-weight: 500; 
} 
 nav a:hover { 
color: var(--primary-color); 
} 
 /* ヒーローセクション */ 
.hero { 
background: linear-gradient(rgba(0, 0, 0, 0.6), rgba(0, 0, 0, 0.6)), url('https://images.unsplash.com/photo-1493976040374-85c8e12f0c0e?ixlib=rb-4.0.3&auto=format&fit=crop&w=1200&q=80'); 
background-size: cover; 
background-position: center; 
color: white; 
padding: 100px 0; 
text-align: center; 
} 
 .hero-content {
