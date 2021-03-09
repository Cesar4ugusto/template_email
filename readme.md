# Disparo de Email com Template.

[![Github Badge](https://img.shields.io/badge/-Github-000?style=flat-square&logo=Github&logoColor=white&link=https://github.com/Cesar4ugusto)](https://github.com/Cesar4ugusto)
[![Linkedin Badge](https://img.shields.io/badge/-LinkedIn-blue?style=flat-square&logo=Linkedin&logoColor=white&linkhttps://www.linkedin.com/in/c%C3%A9sar-augusto-aa8143160//)](https://www.linkedin.com/in/c%C3%A9sar-augusto-aa8143160//)

## Sobre mim
Sou estudante de Análise e Desenvolvimento de Sistemas focado no desenvolvimentode soluções web Front-End e Back-End.

## Este projeto
Tem como propósito ajudar desenvolvedores no envio de email atravez da funcionalidade do PHP, o `PHPMailer`. Conta também com um template de email configurado para ser enviado como corpo do projeto.

Neste projeto a instalação do `PHPMailer` foi feita via [Composer](https://getcomposer.org).

Para usar o `PHPMailer` siga as instruções de intalação disponibilizadas em [PHPMailer](https://github.com/PHPMailer/PHPMailer).

## Observação

Veja no arquivo `index.php` que a importação do template é feita no seguinte código:

```php
$template = file_get_contents('../template_email.html');
```

- Primeiro crie uma variável para a importação.
- Após, importe o arquivo no diretório que ele está.

```php
$mail->Body = $template; 
```

- Depois de importado configure o template como corpo do email e está pronto.

## Características

- Suporte SMTP integrado - Envio de um servidor de email local.
- Compatível com PHP 5.5 e posterior, incluindo PHP 8.0.