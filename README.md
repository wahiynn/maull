html_content = """
<!DOCTYPE html>
<html>
<head>
    <title>Global Warming</title>
    <style>
        body {
            background-color: blue;
            font-family: Arial, sans-serif;
            text-align: center;
        }
        .header {
            padding: 10px;
            background-color: #e0f7fa;
        }
        .main {
            margin-top: 20px;
        }
        a {
            color: red;
            text-decoration: underline;
        }
    </style>
</head>
<body>
    <div class="header">
        <a href="#">beranda</a>
        <a href="#">Proses Desain</a>
        produk
    </div>

    <div class="main">
        <h2><strong>global warming</strong></h2>
        <p>dibuat oleh Wahiya</p>
    </div>

    <footer>
        <p><a href="#">Soft Pink Dreamy Cloud Y2K Eco Friendly New Year Presentation</a> by radit aryasatya</p>
    </footer>
</body>
</html>
"""

# Simpan ke file index.html
with open("index.html", "w", encoding="utf-8") as file:
    file.write(html_content)

print("File HTML berhasil dibuat.")
     
