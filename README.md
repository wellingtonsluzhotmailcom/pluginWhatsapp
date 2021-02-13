# pluginWhatsapp
Plugin de CTA whatsapp para sites

Exemplo de uso: 

<!DOCTYPE html>
<html>

<head>
    <script src="assets/js/pluginWhatsapp.js"></script>
</head>

<body>


    <script>
      // colocar no final do body

      pluginWhastapp([{
            "Name": "Usuario 01",
            "Phone": "(62)90000-0000",
            "UnmaskedPhone": "5562900000000",
            "Message": "Olá Usuario 01! Tudo bem?",
            "ButtonText": null,
            "Photo": "https://meusite.com.br/assets/img/User01.PNG" //link para a foto do usuario
        }, {
            "Name": "Usuario 02",
            "Phone": "(62) 98461-9251",
            "UnmaskedPhone": "556284619251",
            "Message": "Olá Usuario 02! Tudo bem?",
            "ButtonText": null,
            "Photo": "https://meusite.com.br/assets/img/User01.PNG" //link para a foto do usuario
        }, {
            "Name": "Exemplo três",
            "Phone": "(62) 99999-0000",
            "UnmaskedPhone": "+5562900000000",
            "Message": "Olá Exemplo! Tudo bem?",
            "ButtonText": "Chamar no whatsapp",
            "Photo": "" //link para a foto do usuario
        }], {
            tipography: "Ubuntu",
            titleBox: 'Conversar pelo WhatsApp',
            CTA: "Olá! Fale com nossas atendentes",
            description: "Solicite o catálogo com uma de nossas vendedoras",
            btnText: "Iniciar conversa",
            footerMesssage: "",
			      posBottom: "40px", 
            posRight: "40px",
        });
    </script>

</body>

</html>
