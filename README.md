# 📂 README-Vault

<p align="center">
  <img src="https://img.shields.io/badge/status-ativo-brightgreen?style=for-the-badge" alt="Status Ativo">
  <img src="https://img.shields.io/badge/licença-MIT-blue?style=for-the-badge" alt="Licença MIT">
  <img src="https://img.shields.io/badge/markdown-100%25-orange?style=for-the-badge" alt="Markdown">
</p>

<p align="center">
  <strong>Um acervo inteligente e organizado de templates em Markdown para perfis, projetos e documentação no GitHub.</strong><br>
  Projetado para ser usado com <strong>Obsidian</strong> (opcional), mas 100% funcional em qualquer editor de texto.
</p>

---

## 📖 Sobre o Projeto

Criar READMEs bonitos e informativos do zero toda vez é cansativo e repetitivo. O **README Vault** nasceu para resolver isso: é um repositório-central onde guardo todos os meus modelos prontos, separados por categorias e otimizados para diferentes cenários.

A grande sacada é que este repositório é **apenas Markdown puro**. Você pode clonar, abrir no Obsidian (usando os plugins que quiser localmente) ou simplesmente copiar e colar os trechos diretamente do GitHub.

> ⚡ **Foco principal**: Agilizar a criação de documentações de alto nível, mantendo a consistência visual e estrutural em todos os seus projetos.

---

## 🗂️ Estrutura de Pastas

A organização foi pensada para ser escalável e intuitiva. As pastas numeradas garantem a ordem correta dentro do Obsidian.

```
readme-vault/
│
├── 📁 _assets/                        # Imagens, ícones e badges de exemplo
│   ├── icons/
│   ├── screenshots/
│   └── badges/
│
├── 📁 templates/                      # ↪ RAIZ DOS MODELOS
│   │
│   ├── 📁 01-profile/                 # Modelos para README de Perfil
│   │   ├── .md
│   │   ├── .md
│   │   └── .md
│   │
│   ├── 📁 02-projects/                # Modelos para README de Projetos
│   │   ├── .md
│   │   ├── .md
│   │   └── .md
│
└── 📁 examples/                       # Exemplos práticos renderizados
    ├── profile-example.md
    └── project-example.md
```

## 🚀 Como Utilizar

Siga o passo a passo abaixo para extrair o máximo proveito deste acervo:

### 1. Escolha o template ideal
Navegue pela pasta [`templates/`](./templates) e encontre o modelo que melhor se adapta ao seu objetivo (perfil, projeto completo).

### 2. Copie o conteúdo
Abra o arquivo `.md` desejado e copie todo o seu conteúdo.

### 3. Substitua os placeholders
Todos os templates utilizam placeholders no formato `{{NOME_DA_VARIAVEL}}`. Utilize o recurso "Localizar e Substituir" (`Ctrl+H`) do seu editor para preencher rapidamente com suas informações:

| Placeholder | Descrição |
| :--- | :--- |
| `{{USERNAME}}` | Seu nome de usuário ou nome real |
| `{{PROJECT_NAME}}` | Nome do projeto |
| `{{SKILLS}}` | Lista de tecnologias dominadas |
| `{{STATS_URL}}` | URL das suas estatísticas do GitHub |
| `{{REPO_LINK}}` | Link para o repositório do projeto |

### 4. (Opcional) Use com o Obsidian
Se você usa o [Obsidian](https://obsidian.md/), clone este repositório e abra-o como um **Vault**. A pasta `.obsidian/` está configurada para ser ignorada pelo Git, então você pode:

- Instalar plugins como **Dataview** para criar índices automáticos locais.
- Usar o plugin **Templates** para inserir datas e metadados com um clique.
- Vincular seus templates usando `[[wikilinks]]` entre as notas.

> 💡 **Dica**: Mesmo usando o Obsidian, o repositório remoto continua totalmente limpo, contendo apenas os arquivos essenciais em Markdown!

---

## 🤝 Como Contribuir

Quer adicionar um novo template ou melhorar um existente? Ficarei muito feliz com a ajuda!

1. Faça um **Fork** deste repositório.
2. Crie uma nova branch com sua feature:  
   `git checkout -b minha-nova-categoria`
3. Adicione seu template na pasta correta (ou crie uma nova, se necessário).
4. Envie um **Pull Request** descrevendo o que você criou.

---

## 📄 Licença

Este projeto está sob a licença **MIT**. Sinta-se à vontade para usar, modificar e distribuir os templates como achar melhor. 😉

---

<p align="center">
  Feito com ☕ e ⌨️ — aproveite e organize seu trabalho!
</p>