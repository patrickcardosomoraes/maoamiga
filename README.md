# 🤝 Mão Amiga

> Plataforma moderna de crowdfunding social com taxa zero. Receba doações sem intermediários.

## ✨ Características

- 💰 **Taxa Zero**: Receba 100% das doações via PIX instantaneamente
- 🔗 **Compartilhamento Fácil**: Links curtos e QR Codes dinâmicos para suas campanhas
- 🎨 **Design Responsivo**: Interface moderna e intuitiva, funcionando perfeitamente em mobile
- 🌙 **Dark Mode**: Suporte completo para tema escuro
- ⚡ **Performance Otimizada**: Aplicação rápida e fluida
- 🔒 **Seguro**: Dados criptografados e em conformidade com regulamentações

## 🚀 Stack Tecnológico

- **Frontend**: [Next.js 16](https://nextjs.org/) - React Framework moderno
- **Backend**: [Supabase](https://supabase.com/) - PostgreSQL + APIs REST
- **Styling**: [TailwindCSS 4](https://tailwindcss.com/) - Utility-first CSS
- **Design**: Responsivo e otimizado para conversão

## 📋 Pré-requisitos

- Node.js 18+
- npm ou yarn
- Conta Supabase (gratuita)

## 🔧 Instalação

1. Clone o repositório
```bash
git clone https://github.com/patrickcardosomoraes/maoamiga.git
cd maoamiga
```

2. Instale as dependências
```bash
npm install
```

3. Configure as variáveis de ambiente
```bash
cp .env.local.example .env.local
```

4. Preencha seu `.env.local` com:
```
NEXT_PUBLIC_SUPABASE_URL=sua_url_supabase
NEXT_PUBLIC_SUPABASE_ANON_KEY=sua_chave_anonima
```

5. Execute o servidor de desenvolvimento
```bash
npm run dev
```

6. Abra [http://localhost:3000](http://localhost:3000) no seu navegador

## 📖 Como Usar

### Criar uma Campanha
1. Acesse a plataforma
2. Clique em "Nova Campanha"
3. Preencha os detalhes da vaquinha
4. Compartilhe o link ou QR Code
5. Receba doações via PIX

### Compartilhar
- Copie o link da campanha
- Escaneie o QR Code
- Compartilhe em redes sociais

## 🎯 Roadmap

- [ ] Autenticação com redes sociais
- [ ] Dashboard com analytics
- [ ] Suporte a múltiplas moedas
- [ ] Integração com WhatsApp
- [ ] App mobile (React Native)
- [ ] Certificado para doadores
- [ ] Campanha recorrente

## 🤝 Contribuindo

Contribuições são bem-vindas! Por favor:

1. Fork o projeto
2. Crie uma branch para sua feature (`git checkout -b feature/AmazingFeature`)
3. Commit suas mudanças (`git commit -m 'Add some AmazingFeature'`)
4. Push para a branch (`git push origin feature/AmazingFeature`)
5. Abra um Pull Request

## 📄 Licença

Este projeto está licenciado sob a Licença MIT - veja o arquivo [LICENSE](LICENSE) para mais detalhes.

## 📞 Suporte

Para dúvidas ou sugestões, abra uma [issue](https://github.com/patrickcardosomoraes/maoamiga/issues) no repositório.

## 👨‍💻 Autor

**Patrick Cardoso**
- GitHub: [@patrickcardosomoraes](https://github.com/patrickcardosomoraes)
- Website: [maoamiga-five.vercel.app](https://maoamiga-five.vercel.app)

---

<div align="center">
  <strong>Feito com ❤️ para facilitar o crowdfunding solidário</strong>
</div>
