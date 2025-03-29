
                return;
            }

            var mensagem = `Olá, tenho interesse em Crédito para Investimento!
            \nNome: ${nome}
            \nE-mail: ${email}
            \nTelefone: ${telefone}
            \nCidade: ${cidade}
            \nÁrea de Investimento: ${investimento}
            \nValor do Investimento: R$ ${parseInt(valor).toLocaleString()}
            \nValor da Parcela: R$ ${parseInt(parcela).toLocaleString()}`;

            var url = `https://api.whatsapp.com/send?phone=5598986261538&text=${encodeURIComponent(mensagem)}`;
            window.open(url, "_blank");
        }
    </script>
</body>
</html>
