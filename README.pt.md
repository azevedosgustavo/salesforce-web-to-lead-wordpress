# Salesforce Web-To-Lead com WordPress (Compatível com Cornerstone)

## Autor
Este script foi desenvolvido por **Gustavo Azevedo**.  
Se precisar de suporte ou quiser trocar ideias, você pode entrar em contato comigo pelos canais abaixo:  

-E-mail: [azevedosgustavo@gmail.com]
-GitHub: [https://github.com/azevedosgustavo]
---
## Objetivo do Script
O objetivo deste código é permitir a integração confiável do **Salesforce Web-To-Lead** dentro do **WordPress**, especialmente quando o site utiliza o **Cornerstone** ou outros page builders que manipulam o DOM.  

O script garante que o campo oculto 'captcha_settings' seja corretamente atualizado com o timestamp ('ts'), evitando falhas comuns na validação do **Google reCAPTCHA** e assegurando que os leads sejam enviados corretamente para o Salesforce.  

---

## Benefícios
- Compatibilidade total com WordPress e Cornerstone.  
- Evita problemas no envio de 'captcha_settings'.  
- Atualização automática do timestamp em tempo real.  
- Código leve, em JavaScript puro, sem dependências.  
- Fácil implementação via plugin WPCode (Shortcode).  

---

## Como usar
1. Instale o plugin [WPCode](https://wordpress.org/plugins/insert-headers-and-footers/) no WordPress.  
2. Crie um novo snippet no modo **Shortcode**.  
3. Cole o código disponível neste repositório.  
4. Substitua os valores de exemplo:  
   - 'xxxxORGIDxxxx' → ID da sua organização Salesforce  
   - 'xxxxRetURLxxxx' → URL de retorno após o envio  
   - 'xxxxDataSiteKeyxxxx' → Chave do Google reCAPTCHA  
   - 'xxxxKeyNamexxxx' → Nome da chave do reCAPTCHA no Salesforce  
5. Use o shortcode na página desejada.  
