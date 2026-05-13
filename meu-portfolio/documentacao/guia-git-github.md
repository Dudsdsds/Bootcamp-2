# 📋 Guia de Versionamento com Git

Passo a passo completo para versionar e publicar seu portfólio.

---

## 1. Configuração inicial do Git (fazer uma vez só)

```bash
git config --global user.name "Seu Nome"
git config --global user.email "seuemail@email.com"
```

---

## 2. Inicializar o repositório (dentro da pasta meu-portfolio)

```bash
cd meu-portfolio
git init
git add .
git commit -m "feat: versão 1.0 - estrutura inicial do portfólio"
```

---

## 3. Conectar ao GitHub

1. Acesse github.com e crie um repositório chamado `meu-portfolio`
2. Deixe-o **público** e **sem** README (vamos subir o nosso)
3. Copie o link HTTPS e rode:

```bash
git remote add origin https://github.com/seu-usuario/meu-portfolio.git
git branch -M main
git push -u origin main
```

---

## 4. Fluxo para enviar atualizações

```bash
# Ver o que mudou
git status

# Adicionar arquivos modificados
git add .

# Fazer commit com mensagem descritiva
git commit -m "feat: adiciona projeto X na pasta pessoal"

# Enviar para o GitHub
git push
```

---

## 5. Boas práticas para mensagens de commit

| Prefixo | Quando usar |
|---------|-------------|
| `feat:` | adicionou algo novo |
| `fix:` | corrigiu um bug ou erro |
| `docs:` | alterou documentação / README |
| `style:` | mudou aparência, CSS |
| `refactor:` | reorganizou código sem mudar funcionalidade |

Exemplo: `git commit -m "docs: atualiza README com descrição do TCC"`

---

## 6. Ativar GitHub Pages

1. No GitHub, acesse: **Settings → Pages**
2. Source: `Deploy from a branch`
3. Branch: `main` / Folder: `/ (root)` ou `/pagina-web`
4. Clique em **Save**
5. Aguarde ~1 minuto e acesse: `https://seu-usuario.github.io/meu-portfolio`

---

## 7. Integrar ao LinkedIn

1. No LinkedIn, vá em **Perfil → Adicionar seção → Projetos**
2. Nome do projeto: `Portfólio no GitHub`
3. URL: `https://github.com/seu-usuario/meu-portfolio`
4. Descrição: "Repositório com projetos acadêmicos e pessoais, documentado com README e publicado via GitHub Pages."
5. Habilidades: Git, GitHub, HTML, CSS, JavaScript

---

*Arquivo de referência — não precisa subir para o GitHub*
