# Análise e Troubleshooting de DNS

Laboratório técnico sobre hierarquia de domínios, registros DNS, resolução de nomes e consultas realizadas com nslookup.

## Objetivo

Compreender como o DNS traduz nomes de domínio em endereços e como diferentes registros orientam serviços web, e-mail e validações de domínio. O projeto relaciona esses conceitos a troubleshooting, administração de infraestrutura e segurança da informação.

## Atividades realizadas

- Estudo da hierarquia formada pelo domínio raiz, TLD, domínio de segundo nível e subdomínios.
- Análise dos registros A, AAAA, CNAME, MX e TXT.
- Acompanhamento do fluxo de resolução entre cache local, servidor recursivo, servidores raiz, TLD e servidor autoritativo.
- Compreensão do papel do TTL no armazenamento temporário das respostas DNS.
- Realização de consultas práticas com nslookup para registros CNAME, MX e A.
- Relação dos resultados com troubleshooting, enumeração de subdomínios, spoofing e sequestro de domínio.

## Resultado e aprendizado

A prática permitiu interpretar a resolução de nomes a partir dos registros e da hierarquia DNS. O uso de nslookup reforçou um procedimento inicial de troubleshooting para confirmar respostas, identificar o tipo de registro consultado e compreender a participação de servidores recursivos e autoritativos.

## Ferramenta e cenário

O laboratório foi realizado na **plataforma TryHackMe**, utilizando o utilitário de linha de comando **nslookup** para observar consultas DNS em um ambiente educacional.

## Competências demonstradas

**DNS**, resolução de nomes, hierarquia de domínios, registros A/AAAA/CNAME/MX/TXT, TTL, servidores recursivos e autoritativos, nslookup, troubleshooting e fundamentos de segurança de infraestrutura.

## Documentação

- [Baixar relatório técnico original em PDF](./relatorio-fundamentos-dns.pdf)
- [Voltar ao catálogo de projetos](../README.md)
