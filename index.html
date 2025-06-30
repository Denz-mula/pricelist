<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Always Hanzz - 2025</title>
  <style>
    body {
      margin: 0;
      padding: 20px;
      font-family: 'Segoe UI', sans-serif;
      background: #f5faff;
      color: #333;
    }

    .header {
      display: flex;
      align-items: center;
      justify-content: center;
      gap: 15px;
      margin-bottom: 25px;
    }

    .logo-box {
      width: 60px;
      height: 60px;
      background-color: #ffffff;
      border: 2px solid #007aff;
      border-radius: 10px;
      display: flex;
      align-items: center;
      justify-content: center;
      padding: 5px;
    }

    .logo-box img {
      width: 100%;
      height: 100%;
      object-fit: contain;
    }

    .header-title {
  color: white;
  background-color: #007aff;
  padding: 10px 15px;
  border-radius: 8px;
}

    .product-list {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 15px;
    }

    .product-card {
      background: #fff;
      padding: 15px;
      border-radius: 12px;
      box-shadow: 0 2px 6px rgba(0,0,0,0.1);
      transition: 0.2s;
    }

    .product-card:hover {
      transform: scale(1.02);
    }

    label {
      display: block;
      margin-bottom: 5px;
      font-weight: bold;
    }

    .product-desc {
      font-size: 0.9rem;
      color: #555;
      margin-bottom: 10px;
    }

    .product-card input[type="checkbox"] {
      transform: scale(1.2);
      margin-right: 10px;
    }

    .product-price {
      color: #0099cc;
      font-weight: bold;
      margin: 5px 0 10px;
    }

    .total-box {
      margin-top: 25px;
      padding: 15px;
      background: #fff;
      border-radius: 12px;
      box-shadow: 0 2px 6px rgba(0,0,0,0.1);
      text-align: center;
    }

    .total-box h2 {
      margin-bottom: 10px;
    }

    .order-btn {
      margin-top: 15px;
      padding: 12px 25px;
      font-size: 1rem;
      background: #28a745;
      color: white;
      border: none;
      border-radius: 10px;
      cursor: pointer;
    }

    .order-btn:hover {
      background: #218838;
    }

    footer {
      text-align: center;
      margin-top: 40px;
      color: #777;
    }
  </style>
</head>
<body>

<div class="header">
  <div class="logo-box">
    <img src="https://i.ibb.co.com/dJtTjRBM/17419789380312652076433473311377.jpg" alt="Logo"> <!-- GANTI DENGAN LINK ATAU FILE LOGO -->
  </div>
  <div class="header-title">Daftar Produk Yang Tersedia - AlwaysHanzz</div>
</div>

<div class="product-list" id="productList">
  <!-- Produk akan di-generate oleh JS -->
</div>

<div class="total-box">
  <h2>Total yang Harus Dibayar:</h2>
  <div id="totalHarga">Rp 0</div>
  <button class="order-btn" onclick="kirimKeWhatsApp()">Kirim Pesanan ke Owner</button>
</div>

<footer>&copy; 2025 - AlwaysHanzz</footer>

<script>
  const ownerNumber = "6281936513894"; // Ganti dengan nomor WhatsApp admin

  const products = [
    { name: "Script Bot Pushkontak", price: 7000, desc: "Script Anti Kenon , Anti Over Limit , Support All Wa" },
    { name: "Script Bot Cpanel x Store V3", price: 15000, desc: "Cocok Buat Yang Open Reseller Panel , Cocok Buat Jualan , Support All Wa" },
    { name: "Script AteusCrasher V2 Via Wa", price: 45000, desc: "Pre-Order Script AteusCrasher V2 Via Wa" },
    { name: "Script AteusCrasher V2 Via Tele", price: 55000, desc: "Free Update Jika Tidak Nego Nego?No Update" },
    { name: "Reseller AteusCrasher", price: 50000, desc: "Free Update Selama Nego?Update 2x , Free Nokos ( Jika Ada Stok ) , Free Panel ( Jika Ada ) , Masuk Di Tqto" },
    { name: "Pt AteusCrasher", price: 85000, desc: "Free Update Selamanya Nego? Update 3x , Free Nokos ( Jika Ada Stok Nya ) , Free Panel ( Jika Ada ) , Masuk Di Tqto" },
    { name: "Murid Create Script Bug Via Tele", price: 50000, desc: "Bisa Po Script Mu Sendiri , Bisa Jual Script Mu sendiri , Bisa Open Reseller/Pt Script Mu Sendiri, Free Base Nya ( Jika Belum Punya )" },
    { name: "Jasa Bikin Projek Script Bot Bug Via Tele", price: 45000, desc: "Tinggal Nunggu jadi , Free Funct , Free Req Nama script mu" },
    { name: "Jasa Bikin Website", price: 15000, desc: "Tersedia Berbagai Macam Yaitu Web Toko online, Web Top up Untuk Web Top up Beda Harga Harga web top up?Rp25.000" },
    { name: "Jasa pasang database", price: 15000, desc: "preview web nya langsung ke owner saja" },
    { name: "Jasa Fix Eror Script", price: 15000, desc: " - " },
    { name: "Script Create Website", price: 20000, desc: " - " },
    { name: "Base Script Bot Wa", price: 15000, desc: "Bisa Buat Script Mu Sendiri ( Jika Ngerti ) , Bisa Jual Script Mu sendiri , Bisa Open Reseller/Pt Sendiri" }
  ];

  const productList = document.getElementById("productList");
  const totalHargaDiv = document.getElementById("totalHarga");

  let selectedProducts = [];

  products.forEach((product, index) => {
    const card = document.createElement("div");
    card.className = "product-card";
    card.innerHTML = `
      <label>
        <input type="checkbox" id="product-${index}" onchange="updateTotal()" data-name="${product.name}" data-price="${product.price}">
        ${product.name}
      </label>
      <div class="product-desc">${product.desc}</div>
      <div class="product-price">Rp ${product.price.toLocaleString("id-ID")}</div>
    `;
    productList.appendChild(card);
  });

  function updateTotal() {
    selectedProducts = [];
    let total = 0;
    products.forEach((product, index) => {
      const checkbox = document.getElementById(`product-${index}`);
      if (checkbox.checked) {
        selectedProducts.push(product);
        total += product.price;
      }
    });
    totalHargaDiv.innerText = "Rp " + total.toLocaleString("id-ID");
  }

  function kirimKeWhatsApp() {
    if (selectedProducts.length === 0) {
      alert("Pilih minimal 1 produk terlebih dahulu.");
      return;
    }

    const tanggal = new Date().toLocaleDateString("id-ID");
    const totalHarga = selectedProducts.reduce((sum, p) => sum + p.price, 0);
    const produkList = selectedProducts.map(p => `- ${p.name} (Rp ${p.price.toLocaleString("id-ID")})`).join("%0A");

    const pesan = 
`Halo Admin 👋, Saya Ingin Memesan Produk Yaitu

Produk :
${produkList}

Tanggal Pemesanan : ${tanggal}
Total Harga : Rp ${totalHarga.toLocaleString("id-ID")}

Mohon Kirimkan Format Pembayarannya. Terima Kasih 🙏`;

    const url = `https://wa.me/${ownerNumber}?text=${encodeURIComponent(pesan)}`;
    window.open(url, "_blank");
  }
</script>

</body>
</html>
