# Plano de Profissionalização - ROMA

Apresentação HTML profissional do Plano de Profissionalização da ROMA Representação Comercial.

## 📁 Estrutura do Projeto

```
.
├── index.html       # Estrutura HTML semântica
├── styles.css       # Estilos CSS separados (mobile-first)
├── metadata.yml     # Dados estruturados do conteúdo
└── README.md        # Documentação do projeto
```

## 🎨 Características

### Design
- ✅ **Mobile-First**: Otimizado para smartphones, tablets e desktops
- ✅ **Responsivo**: Layout adaptativo com breakpoints em 576px, 768px, 992px e 1200px
- ✅ **Cores da marca**: Paleta ROMA (Azul escuro #1E3A5F, Azul turquesa #1A9BAD)
- ✅ **Animações sutis**: Efeitos hover e transições suaves
- ✅ **Acessibilidade**: Suporte a leitores de tela, contraste alto e redução de movimento

### Tecnologias
- HTML5 semântico
- CSS3 com variáveis customizadas
- Flexbox e CSS Grid
- Media queries para responsividade
- Fontes do sistema (sem dependências externas)

### Seções do Plano

1. **Ambiente de Trabalho Digital** - Comparação de workspaces (Zoho, Google, Microsoft)
2. **Infraestrutura em Nuvem** - Opções de hosting (Render, DigitalOcean, AWS/GCP)
3. **Gestão Comercial (CRM)** - Sistema central de crescimento
4. **Organização Interna** - Notion, Trello e RD Station
5. **Atendimento ao Cliente** - WhatsApp Business e Zoho Desk
6. **Controle Financeiro (ERP)** - Gestão de fluxo de caixa e margens
7. **Domínio e Identidade** - Padronização profissional
8. **Segurança e Continuidade** - Backup e controle de acesso
9. **Inteligência Operacional (IA)** - Claude Pro como assistente
10. **Combinações Sugeridas** - 3 pacotes (Econômica, Recomendada, Corporativa)
11. **Indicadores de Profissionalização** - KPIs para acompanhamento

## 📱 Responsividade

### Mobile (até 575px)
- Layout em coluna única
- Cards empilhados verticalmente
- Fontes redimensionadas proporcionalmente
- Padding reduzido para otimizar espaço

### Tablet (576px - 991px)
- Grid de 2 colunas para cards
- KPIs em 2-3 colunas
- Tabelas com scroll horizontal se necessário

### Desktop (992px+)
- Grid de 3 colunas para cards e pacotes
- Layout completo otimizado
- Efeitos hover mais pronunciados

## 🎯 Como Usar

### Abrir localmente
1. Faça download dos arquivos `index.html` e `styles.css`
2. Mantenha ambos na mesma pasta
3. Abra `index.html` no navegador

### Hospedar online
- **GitHub Pages**: Faça push dos arquivos para um repositório
- **Netlify/Vercel**: Arraste a pasta para deploy instantâneo
- **Servidor próprio**: Faça upload via FTP

## 📊 Dados Estruturados (metadata.yml)

O arquivo `metadata.yml` contém todo o conteúdo estruturado em formato YAML:
- Facilita manutenção e atualização do conteúdo
- Permite internacionalização futura
- Pode ser usado para gerar outras versões (PDF, DOCX, etc.)

## 🎨 Customização

### Alterar Cores
Edite as variáveis CSS no arquivo `styles.css`:

```css
:root {
  --primary-dark: #1E3A5F;    /* Azul escuro */
  --primary-light: #1A9BAD;   /* Azul turquesa */
  --accent: #2BB4C7;          /* Azul claro */
}
```

### Alterar Conteúdo
1. Edite o arquivo `metadata.yml` para alterar textos e dados
2. Ou edite diretamente o `index.html` para mudanças rápidas

### Adicionar Seções
Copie a estrutura de uma seção existente no HTML e ajuste o conteúdo.

## 🔧 Compatibilidade

### Navegadores Suportados
- ✅ Chrome/Edge (últimas 2 versões)
- ✅ Firefox (últimas 2 versões)
- ✅ Safari (últimas 2 versões)
- ✅ Mobile Safari (iOS 12+)
- ✅ Chrome Mobile (Android 8+)

### Recursos de Acessibilidade
- Semântica HTML5 (header, section, article, footer)
- Contraste WCAG AA compliant
- Suporte a `prefers-reduced-motion`
- Suporte a `prefers-contrast: high`
- Outline customizado para navegação por teclado

## 📄 Licença

Desenvolvido para ROMA - Representação Comercial.

## 🚀 Próximos Passos

### Melhorias Futuras
- [ ] Adicionar modo escuro (dark mode)
- [ ] Implementar versão para impressão otimizada
- [ ] Criar versão PDF automatizada
- [ ] Adicionar calculadora de investimento interativa
- [ ] Implementar gráficos de comparação de custos

---

**ROMA - Representação Comercial**  
*Profissionalização para Crescimento Sustentável*