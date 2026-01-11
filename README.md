# MEGARABATY 🔥

MEGARABATY to strona z najnowszymi **kodami rabatowymi** i promocjami online.  
Znajdziesz tu kody do popularnych sklepów internetowych, które pozwolą Ci **oszczędzać przy zakupach** każdego dnia!

## Jak korzystać
1. Przeglądaj listę aktualnych kodów rabatowych.  
2. Kliknij przycisk **„Kopiuj kod”** przy wybranym kodzie.  
3. Wklej kod podczas zakupów w sklepie internetowym.  

## Funkcje strony
- Lista aktualnych kodów rabatowych.  
- Przyciski „Kopiuj kod” dla wygody użytkownika.  
- Nowoczesny, responsywny wygląd, działa na komputerze i telefonie.  

## Autor
Twoje Imię / Twój Nick  

---

Dzięki za odwiedziny! 💻🎉

<!DOCTYPE html>
<html lang="pl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MEGARABATY 🔥</title>
    <meta name="description" content="MEGARABATY – złap najlepsze kody rabatowe online i oszczędzaj na zakupach w sklepach internetowych!">
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f9f9f9;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #ff6f00;
            color: white;
            text-align: center;
            padding: 20px;
        }
        h1 {
            margin: 0;
            font-size: 2em;
        }
        #codes {
            max-width: 800px;
            margin: 20px auto;
            padding: 0 10px;
        }
        .code-box {
            background-color: #fff;
            border: 2px solid #ff6f00;
            border-radius: 8px;
            padding: 15px;
            margin-bottom: 10px;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        .code-box span {
            font-weight: bold;
        }
        .code-box button {
            background-color: #ff6f00;
            color: white;
            border: none;
            padding: 8px 12px;
            border-radius: 5px;
            cursor: pointer;
        }
        .code-box button:hover {
            background-color: #e65c00;
        }
        footer {
            text-align: center;
            padding: 15px;
            background-color: #333;
            color: white;
            margin-top: 30px;
        }
        @media (max-width: 600px) {
            .code-box {
                flex-direction: column;
                align-items: flex-start;
            }
            .code-box button {
                margin-top: 10px;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>MEGARABATY 🔥</h1>
        <p>Najlepsze kody rabatowe i promocje online!</p>
    </header>

    <div id="codes"></div>

    <footer>
        &copy; 2026 MEGARABATY. Oszczędzaj z nami! 💻🎉
    </footer>

    <script>
        // Lista kodów rabatowych
        const codes = [
            {shop: "Sklep Modowy", code: "MODA10"},
            {shop: "ElektronikaPlus", code: "ELEC20"},
            {shop: "SportowyRaj", code: "SPORT15"},
            {shop: "KsiążkiOnline", code: "BOOK5"}
        ];

        const container = document.getElementById("codes");

        // Generowanie kodów na stronie
        codes.forEach(item => {
            const div = document.createElement("div");
            div.className = "code-box";
            div.innerHTML = `
                <span>${item.shop} - ${item.code}</span>
                <button onclick="copyCode('${item.code}')">Kopiuj kod</button>
            `;
            container.appendChild(div);
        });

        // Funkcja kopiowania kodu
        function copyCode(code) {

        <!DOCTYPE html>
<html lang="pl">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>MEGARABATY 🔥</title>
<meta name="description" content="MEGARABATY – kody dnia, kody miesiąca i najlepsze promocje online. Oszczędzaj na zakupach!">

<style>
body { font-family: Arial; margin:0; background:#f5f5f5; }
header { background:#ff6f00; color:white; text-align:center; padding:20px; }

.tabs {
    display:flex;
    justify-content:center;
    background:#fff;
    border-bottom:2px solid #ff6f00;
}
.tabs button {
    padding:15px 20px;
    border:none;
    background:none;
    cursor:pointer;
    font-weight:bold;
}
.tabs button.active {
    color:#ff6f00;
    border-bottom:3px solid #ff6f00;
}

#codes, #cart {
    max-width:900px;
    margin:20px auto;
    padding:0 10px;
}

.code-box, .cart-item {
    background:#fff;
    border:2px solid #ff6f00;
    border-radius:8px;
    padding:15px;
    margin-bottom:10px;
    display:flex;
    justify-content:space-between;
    align-items:center;
}

button.action {
    background:#ff6f00;
    color:white;
    border:none;
    padding:8px 12px;
    border-radius:5px;
    cursor:pointer;
    margin-left:5px;
}

button.action:hover { background:#e65c00; }

footer {
    background:#333;
    color:white;
    text-align:center;
    padding:15px;
    margin-top:30px;
}

@media(max-width:600px){
    .code-box,.cart-item { flex-direction:column; align-items:flex-start; }
}
</style>
</head>

<body>

<header>
    <h1>MEGARABATY 🔥</h1>
    <p>Kody dnia i kody miesiąca – oszczędzaj mądrze</p>
</header>

<!-- ZAKŁADKI -->
<div class="tabs">
    <button class="active" onclick="showTab('all', this)">Wszystkie</button>
    <button onclick="showTab('day', this)">Kody dnia</button>
    <button onclick="showTab('month', this)">Kody miesiąca</button>
</div>

<div id="codes"></div>

<h2 style="max-width:900px;margin:30px auto 10px;">🛒 Koszyk</h2>
<div id="cart"></div>
<button class="action" style="display:block;margin:10px auto;" onclick="copyCart()">
    Kopiuj wszystkie kody z koszyka
</button>

<footer>
    © 2026 MEGARABATY
</footer>

<script>
// ====== KODY ======
const codes = [
    { shop:"Sklep Modowy", code:"MODA10", type:"day" },
    { shop:"ElektronikaPlus", code:"ELEC20", type:"month" },
    { shop:"SportowyRaj", code:"SPORT15", type:"day" },
    { shop:"KsiążkiOnline", code:"BOOK5", type:"month" }
];

let currentTab = "all";
let cart = [];

const codesDiv = document.getElementById("codes");
const cartDiv = document.getElementById("cart");

// ====== RENDER KODÓW ======
function renderCodes() {
    codesDiv.innerHTML = "";
    codes
        .filter(c => currentTab === "all" || c.type === currentTab)
        .forEach(item => {
            const div = document.createElement("div");
            div.className = "code-box";
            div.innerHTML = `
                <strong>${item.shop} – ${item.code}</strong>
                <div>
                    <button class="action" onclick="copyCode('${item.code}')">Kopiuj</button>
                    <button class="action" onclick="addToCart('${item.shop}','${item.code}')">Do koszyka</button>
                </div>
            `;
            codesDiv.appendChild(div);
        });
}

// ====== ZAKŁADKI ======
function showTab(tab, btn){
    currentTab = tab;
    document.querySelectorAll(".tabs button").forEach(b => b.classList.remove("active"));
    btn.classList.add("active");
    renderCodes();
}

// ====== KOSZYK ======
function addToCart(shop, code){
    if(!cart.find(i => i.code === code)){
        cart.push({shop, code});
        renderCart();
    }
}

function removeFromCart(code){
    cart = cart.filter(i => i.code !== code);
    renderCart();
}

function renderCart(){
    cartDiv.innerHTML = "";
    cart.forEach(item => {
        const div = document.createElement("div");
        div.className = "cart-item";
        div.innerHTML = `
            <strong>${item.shop} – ${item.code}</strong>
            <button class="action" onclick="removeFromCart('${item.code}')">Usuń</button>
        `;
        cartDiv.appendChild(div);
    });
}

// ====== KOPIOWANIE ======
function copyCode(code){
    navigator.clipboard.writeText(code);
    alert("Skopiowano: " + code);
}

function copyCart(){
    if(cart.length === 0){
        alert("Koszyk pusty");
        return;
    }
    const text = cart.map(i => i.code).join(", ");
    navigator.clipboard.writeText(text);
    alert("Skopiowano kody: " + text);
}

// START
renderCodes();
</script>

</body>
</html>

            navigator.clipboard.writeText(code);
            alert("Kod skopiowany: " + code);
        }
    </script>
</body>
</html>
