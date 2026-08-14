# Escolinha Cyber

Repositório dedicado ao registro de estudos, aprendizados e resoluções de desafios de segurança da informação realizados na plataforma **Escolinha CTF**.

Os relatórios apresentam o processo de análise de cada desafio, as hipóteses levantadas, as ferramentas utilizadas e os conceitos de segurança aplicados durante a resolução.

## Objetivo

Este repositório tem como objetivo documentar minha evolução prática em Cybersecurity por meio de desafios CTF (*Capture The Flag*).

Além de registrar as flags encontradas, os write-ups buscam explicar o raciocínio utilizado em cada etapa, permitindo revisar técnicas, identificar vulnerabilidades e consolidar conhecimentos de segurança ofensiva e defensiva.

## Aprendizados

Os desafios documentados abordam conceitos como:

- análise e manipulação de cookies HTTP;
- falhas de controle de acesso;
- confiança indevida em dados controlados pelo cliente;
- propriedades matemáticas da operação XOR;
- ataques de texto claro conhecido;
- identificação de chaves curtas e repetidas;
- reconhecimento de codificações;
- conversão entre binário, hexadecimal e Base64;
- análise de dados organizados em múltiplas camadas;
- utilização do CyberChef em análises criptográficas.

## Write-ups

| Desafio | Categoria | Conceitos principais |
| --- | --- | --- |
| [Cookie Monster](Cookie-Monster/README.md) | Web | Cookies HTTP e Broken Access Control |
| [Acesso Exclusivo](Acesso-Exclusivo/README.md) | Crypto | XOR e Known Plaintext Attack |
| [Cebola Criptográfica](Cebola-Criptografica/README.md) | Crypto | Binário, hexadecimal, Base64 e Onion Encoding |

## Estrutura

Cada desafio possui um diretório próprio com a seguinte organização:

```text
Nome-do-Desafio/
├── README.md
└── images/
```

O arquivo `README.md` contém a análise e a resolução completa. O diretório `images` armazena as capturas de tela utilizadas para demonstrar as etapas do desafio.

## Ferramentas utilizadas

Entre as ferramentas utilizadas nas resoluções estão:

- navegador e Developer Tools;
- CyberChef;
- editores de texto;
- operações de conversão e análise de dados.

## Aviso

Todo o conteúdo deste repositório possui finalidade exclusivamente educacional. As técnicas apresentadas foram aplicadas em ambientes controlados e desafios CTF autorizados.

## Autor

**Felipe Morais**
