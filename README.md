# AME IDIOMAS 🎓

Aplicativo web para aprendizado de inglês com sistema de memorização espaçada.

## 🚀 Características

- ✅ **1.500 palavras** essenciais do inglês
- ✅ **Sistema de flashcards** com 7 níveis de memorização
- ✅ **Memory Game** - 64 dias de prática estruturada
- ✅ **Autenticação** - Login com email/senha ou Google
- ✅ **Pronúncia** - Áudio para todas as palavras
- ✅ **Progresso** - Acompanhamento detalhado
- ✅ **Banco de dados** - Integração com Supabase

## 📦 Tecnologias

- **Frontend**: HTML5, CSS3, JavaScript (Vanilla)
- **Backend**: Supabase (PostgreSQL, Auth, Storage)
- **Deploy**: Vercel / Netlify
- **Design**: Design System customizado

## 🎯 Como Usar

### 1. Deploy Rápido (Recomendado)

**Vercel:**
```bash
# 1. Clone o repositório
git clone https://github.com/seu-usuario/ame-idiomas.git

# 2. Acesse Vercel
https://vercel.com/new

# 3. Importe o repositório
# 4. Deploy automático!
```

**Netlify:**
```bash
# Arraste a pasta do projeto em:
https://app.netlify.com/drop
```

### 2. Executar Localmente

```bash
# 1. Clone o repositório
git clone https://github.com/seu-usuario/ame-idiomas.git

# 2. Abra o arquivo
open index.html

# Ou use um servidor local:
python -m http.server 3000
# Acesse: http://localhost:3000
```

## ⚙️ Configuração Supabase

1. Crie conta em: https://supabase.com
2. Crie novo projeto
3. Execute os scripts SQL (ver pasta `/database`)
4. Copie credenciais (Project URL e anon key)
5. Cole no arquivo `index.html` (linhas 1135-1136)

## 📊 Estrutura do Banco

- **users** - Dados dos usuários
- **words** - 1.500 palavras
- **flashcards** - Cards criados com progresso
- **dominated_words** - Palavras dominadas
- **user_progress** - Progresso do usuário

## 🎮 Como Jogar

1. **Cadastre-se** ou faça login
2. **Crie flashcards** (10 por dia)
3. **Pratique no Memory Game** (64 dias)
4. **Domine palavras** (7 níveis de revisão)
5. **Acompanhe progresso** (estatísticas)

## 📱 Recursos

### Fonética
- 1.500 palavras com pronúncia
- Áudio de qualidade
- Busca rápida

### Flashcards
- Criação interativa
- Seleção de imagens
- Teclado fonético
- Validação automática

### Memory Game
- 64 dias estruturados
- 7 níveis de revisão
- Memorização espaçada
- Progresso visual

### Palavras Dominadas
- Galeria visual
- Filtros de busca
- Conquistas

## 🔐 Autenticação

- Email/Senha
- Google OAuth
- Session persistence

## 📄 Licença

MIT License - Sinta-se livre para usar e modificar!

## 👨‍💻 Desenvolvedor

Desenvolvido por [Seu Nome]

## 🤝 Contribuindo

Contribuições são bem-vindas! Abra uma issue ou pull request.

## 📞 Suporte

Para dúvidas ou sugestões:
- Email: seuemail@exemplo.com
- Issues: GitHub Issues

---

**Feito com ❤️ para estudantes de inglês**
