Para preencher esteS template, faça um `Ctrl+H` (Localizar e Substituir) e troque cada `{{VARIAVEL}}` pelos seus dados:

|Placeholder|Descrição|Exemplo|
|---|---|---|
|`{{USER_NAME}}`|Seu username do GitHub|`joaosilva`|
|`{{NAME}}`|Seu nome completo (se quiser)|`João Silva`|
|`{{BIO_LINE_1/2/3}}`|Frases curtas para o digitando|`Desenvolvedor Full Stack`|
|`{{LOCATION}}`|Sua cidade/país|`São Paulo, Brasil`|
|`{{FOCUS_AREA}}`|Área principal de atuação|`Desenvolvimento Web e Cloud`|
|`{{CURRENT_LEARNING}}`|O que está estudando agora|`Kubernetes e Golang`|
|`{{ASK_ME_ABOUT}}`|Assuntos que você domina|`React, Node.js e AWS`|
|`{{FUN_FACT}}`|Curiosidade pessoal|`Sou músico nas horas vagas`|
|`{{SKILL_ICONS}}`|Ícones separados por vírgula|`react,nextjs,nodejs,python,aws,docker`|
|`{{STATS_URL}}`|URL das suas stats (ex: github-readme-stats)|`https://github-readme-stats.vercel.app/api?username=joaosilva`|
|`{{TOP_LANGS_URL}}`|URL das linguagens|`.../api/top-langs/?username=joaosilva`|
|`{{STREAK_URL}}`|URL da streak (ex: git-readme-streak-stats)|`...?user=joaosilva`|
|`{{PROJECT_1/2/3_NAME/LINK/DESC}}`|Nome, link e descrição dos seus projetos|`Projeto X`, `https://...`, `API de integração`|
|`{{EMAIL}}`, `{{LINKEDIN_URL}}`, etc.|Links das suas redes|`joao@email.com`, `linkedin.com/in/joao`|
|`{{SNAKE_DARK_URL}}`|URL da animação da cobrinha (modo escuro)|`https://raw.githubusercontent.com/joaosilva/joaosilva/output/github-contribution-grid-snake-dark.svg`|
|`{{PERSONAL_MOTTO}}`|Seu lema ou frase favorita|`"Código limpo é melhor que código rápido"`|

---

### Dica Extra: Como Gerar as URLs das Estatísticas

Se você ainda não configurou as imagens das estatísticas, use estes serviços gratuitos:

1. **GitHub Readme Stats** (`STATS_URL` e `TOP_LANGS_URL`):
    
    - `https://github-readme-stats.vercel.app/api?username={{USER_NAME}}&show_icons=true&theme=radical`
        
    - `https://github-readme-stats.vercel.app/api/top-langs/?username={{USER_NAME}}&layout=compact&theme=radical`
        
2. **GitHub Streak Stats** (`STREAK_URL`):
    
    - `https://streak-stats.demolab.com?user={{USER_NAME}}&theme=radical`
        
3. **Contador de Visitantes** (já incluso no final do template):
    
    - `https://komarev.com/ghpvc/?username={{USER_NAME}}`