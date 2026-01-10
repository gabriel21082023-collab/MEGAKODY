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
            navigator.clipboard.writeText(code);
            alert("Kod skopiowany: " + code);
        }
    </script>
</body>
</html>
