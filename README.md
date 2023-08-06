# Atividade_19.
<!DOCTYPE html>
<html>
<head>
    <title>Soma dos números inteiros positivos</title>
</head>
<body>
    <h1>Soma dos números inteiros positivos de 1 a 100</h1>
    <p id="resultado"></p>

    <script>
        // Função para calcular a soma dos números inteiros positivos de 1 a 100
        function calcularSoma() {
            let soma = 0;
            for (let i = 1; i <= 100; i++) {
                soma += i;
            }
            return soma;
        }

        // Exibindo o resultado no parágrafo com o id "resultado"
        document.getElementById("resultado").innerText = "A soma dos números inteiros positivos de 1 a 100 é: " + calcularSoma();
    </script>
</body>
</html>
