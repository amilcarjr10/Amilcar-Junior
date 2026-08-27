# Fundamentos de DNS

Laboratório técnico sobre a hierarquia de domínios, os principais registros DNS, o processo de resolução de nomes e consultas realizadas com `nslookup`.

## Objetivo

Compreender como o DNS traduz nomes de domínio em endereços e como diferentes registros orientam serviços web, e-mail e validações de domínio. O projeto também reforça a importância desses conceitos para troubleshooting, administração de infraestrutura e segurança da informação.

## Atividades realizadas

- Estudo da hierarquia formada pelo domínio raiz, TLD, domínio de segundo nível e subdomínios.
- Análise dos registros **A**, **AAAA**, **CNAME**, **MX** e **TXT**.
- Acompanhamento do fluxo de resolução entre o cache local, o servidor recursivo, os servidores raiz, o TLD e o servidor autoritativo.
- Compreensão do papel do **TTL** no armazenamento temporário das respostas DNS.
- Realização de consultas práticas com `nslookup` para registros CNAME, MX e A.
- Registro dos resultados obtidos e relação com enumeração de subdomínios, spoofing e sequestro de domínio.

## Ferramenta e cenário

O laboratório foi realizado na **plataforma TryHackMe**, utilizando o utilitário de linha de comando **`nslookup`** para observar diferentes tipos de consulta DNS em um ambiente educacional.

## Competências demonstradas

**DNS**, resolução de nomes, hierarquia de domínios, registros A/AAAA/CNAME/MX/TXT, TTL, servidores recursivos e autoritativos, `nslookup`, troubleshooting e fundamentos de segurança de infraestrutura.

## Documentação

- [Baixar relatório técnico em PDF](./relatorio-fundamentos-dns.pdf)

[Voltar ao catálogo de projetos](../)
