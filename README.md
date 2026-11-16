# Audius | Landing page

Landing page em HTML, CSS e JavaScript para a Audius Aparelhos Auditivos, baseada na estrutura visual do site [audiusaparelhosauditivos.com.br](https://audiusaparelhosauditivos.com.br/).

## Prévia

[Abrir a prévia para aprovação](https://aprovacoes.3ads.com.br/audius-landing/)

O código principal fica em `atendimento3ads/audius-landing`. A prévia no domínio de aprovações é publicada por um fork em `atende3ads-ux/audius-landing`, sincronizado com este repositório.

## Formulário

- Nome e telefone são obrigatórios.
- E-mail e a resposta sobre uso de aparelho auditivo são opcionais.
- O telefone recebe máscara e validação para números brasileiros com DDD.
- Após a confirmação do POST pelo webhook, o visitante é redirecionado para `obrigado.html`.

O projeto é estático. Para conferir localmente, sirva esta pasta por HTTP, por exemplo com `python3 -m http.server 8765`.
