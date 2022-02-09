# Desafio de UX & UI

> 📙 Esse teste é mais qualitativo do que quantitativo, vamos levar em consideração a qualidade dos fluxos e não somente o número de etapas concluídas.

## Contexto

Você foi contratado pela empresa Dynamic Automata (DA) para conceber um fluxo de criação de conta, autenticação e recuperação de conta do novo produto, um software de automação de processos industriais e IoT.

Este app é primariamente para uso em computadores desktop dentro de fábricas. Como a Dynamic Automata é uma grande empresa e pretende atingir diversas verticais em diversas indústrias em diversos países, é importante que a interface seja amigável e haja preocupação com acessibilidade.

## O que se espera do fluxo de criação de conta

O usuário terá acesso freemium ao app através do website da DA. Para criar uma conta os dados minimamente necessário são: o nome e sobrenome do usuário que está criando a conta, país de residência, documento principal de identificação individual naquele país, nome da empresa para qual trabalha, email corporativo e senha de acesso. Esses dados são os minimamente necessários para se criar a conta. Contudo, como a DA também quer entender mais de seus clientes, ela pede que você sugira mais campos que o novo usuário deveria preencher, mas sem onerar a experiência de _onboarding_. Além disso, o email da conta deve ser confirmado de alguma forma.

## O que se espera do fluxo de autenticação

Quando o usuário que já possui conta acessar a plataforma, deverá fazer autenticação antes de prosseguir. Neste fluxo tradicional, os dados mínimos de autenticação são email e senha de acesso. Como a DA se preocupa com a segurança do seus usuários e do sistema, ela gostaria que todos os usuários tivessem ativo multiplos fatores de autenticação (MFA). E que no primeiro login pelo menos 2 formas de recuperação de conta fossem configurados. Assim, ela pede que você sugira o fluxo de configuração dessas 2 formas de recuperação da conta

Enfim, caso o usuário esqueça a senha ou perca acesso ao aparelho na qual o MFA foi configurado, deve-se ter um fluxo de recuperação da conta, que considera o que foi configurado durante o primeiro acesso do usuário à plataforma.

## Resumo

Assim, de forma resumida, os fluxos requeridos são:

1. fluxo de cadastro de usuário
2. fluxo de autenticação com MFA
3. fluxo diferenciado de autenticação para primeiro acesso
4. fluxo de recuperação de conta

Os fluxos devem ser apresentados como diagramas ou desenhos de baixa ou média fidelidade. É necessário que apenas 1 tela de qualquer fluxo seja em alta fidelidade

## Ferramentas e dicas

A DA trabalha principalmente com Figma, mas aceita qualquer outro tipo de formato de apresentação.

- Sobre MFA: https://www.hostmidia.com.br/blog/o-que-e-mfa/

## Submissão
Envie um email para andre.ravazzi[at]semantix.com.br com um link público para a solução do desafio. No título do email coloque "{Seu nome} - UI/UX Challenge"