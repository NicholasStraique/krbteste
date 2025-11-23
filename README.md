# Grupo KRB - Site Institucional e White Label

Site completo do Grupo KRB para venda de serviços de white label de café, torrefação e café personalizado para eventos.

## 🚀 Deploy no Vercel

### Opção 1: Deploy Direto (Mais Rápido)

1. Acesse [vercel.com](https://vercel.com) e faça login/cadastro
2. Clique em "Add New Project"
3. Clique em "Import Third-Party Git Repository" ou faça upload dos arquivos
4. Se fizer upload, compacte todo o projeto em um .zip
5. Vercel detecta automaticamente e faz o build
6. Aguarde ~2 minutos e seu site estará no ar!

### Opção 2: Deploy via GitHub (Recomendado)

1. Crie um repositório no GitHub
2. Faça upload de todos os arquivos do projeto
3. No Vercel, clique em "Import Project"
4. Conecte com seu GitHub e selecione o repositório
5. Deploy automático!

## 🛠️ Tecnologias Utilizadas

- **React** - Framework JavaScript
- **TypeScript** - Tipagem estática
- **Tailwind CSS** - Estilização
- **shadcn/ui** - Componentes
- **React Router** - Navegação
- **Lucide React** - Ícones
- **Sonner** - Notificações
- **React Hook Form** - Formulários

## 📦 Estrutura do Projeto

```
/
├── App.tsx                 # Componente principal e rotas
├── components/
│   ├── Header.tsx          # Navegação principal
│   ├── Footer.tsx          # Rodapé
│   ├── BenefitsSection.tsx # Seção de benefícios
│   ├── ProductMockup.tsx   # Preview de produtos
│   ├── pages/              # Páginas do site
│   │   ├── HomePage.tsx
│   │   ├── WhiteLabelPage.tsx
│   │   ├── TorrefacaoPage.tsx
│   │   ├── EventosPage.tsx
│   │   ├── CaseKurubiPage.tsx
│   │   ├── SobrePage.tsx
│   │   └── ContatoPage.tsx
│   └── ui/                 # Componentes shadcn/ui
├── styles/
│   └── globals.css         # Estilos globais e Tailwind
└── README.md
```

## 🎯 Funcionalidades

### 1. White Label - Criar Marca de Café
- Formulário multi-step
- Seleção de produtos (drip coffee, pacotes, cápsulas)
- Upload de logo
- Escolha de templates ou arte customizada
- Preview em tempo real
- Validação de CPF/CNPJ

### 2. Torrefação
- Formulário para serviço de torrefação
- Opção de fornecer café verde ou usar o do grupo
- Especificações de torra

### 3. Café para Eventos
- Personalização de rótulos
- Usa a marca Café Kurubi
- Ideal para casamentos e eventos corporativos

### 4. Páginas Institucionais
- Sobre o Grupo KRB
- Case de Sucesso: Café Kurubi
- Contato

## 📝 Notas Importantes

- As imagens usam Unsplash através do componente ImageWithFallback
- Formulários possuem validação completa
- Site totalmente responsivo (mobile-first)
- Não coleta dados reais (versão demonstração)

## 🔧 Configuração Local (Opcional)

Se quiser rodar localmente antes de fazer deploy:

```bash
# Instalar dependências
npm install

# Rodar em desenvolvimento
npm run dev

# Build para produção
npm run build
```

## 📞 Contato

Site desenvolvido para o Grupo KRB - Cafés Especiais da Alta Mogiana

---

**Pronto para fazer deploy no Vercel!** 🚀
