<!DOCTYPE html>
<html>

<head>
    <meta charset="UTF-8">
    <title>Treinando Javascript.</title>
</head>

<body>
    <script>
        const endereco = {
            rua: "Rua pedestre J",
            numero: 148,
            bairro: "Curió/ Lagoa Redonda",
            cidade: "Fortaleza",
            uf: "CE"
        };
        const {
            rua,
            numero,
            bairro,
            cidade,
            uf
        } = endereco;
        console.log(`O usuário mora na ${rua}, ${numero} - ${bairro} - ${cidade}/ ${uf}`);
    </script>
</body>

</html>
