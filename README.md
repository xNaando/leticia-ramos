# Chef Letícia Ramos - Site Profissional

Um site elegante e moderno para a Chef de Cozinha Letícia Ramos, desenvolvido para gerar contatos e conversões via WhatsApp, transmitindo autoridade, sofisticação e confiança.

## 🌐 Demonstração

O site está pronto para ser publicado no GitHub Pages e apresenta:

- Design elegante e minimalista
- Cores quentes e refinadas (tons de vinho, dourado, preto, branco)
- Layout totalmente responsivo (mobile-first)
- Animações suaves e interatividade
- Otimizado para SEO e performance
- Chamadas para ação focadas em WhatsApp

## 📁 Estrutura do Projeto

```
leticia-ramos/
├── index.html          # Página principal
├── css/
│   └── style.css       # Estilos CSS
├── js/
│   └── script.js       # JavaScript e animações
├── sitemap.xml         # Sitemap para SEO
├── robots.txt          # Diretrizes para motores de busca
└── README.md           # Este arquivo
```

## 🚀 Como Publicar no GitHub Pages

### Método 1: Via Interface do GitHub

1. **Faça upload dos arquivos para seu repositório GitHub**
   - Vá para o repositório `leticia-ramos`
   - Clique em "Add file" → "Upload files"
   - Arraste todos os arquivos e pastas do projeto
   - Faça o commit

2. **Ative o GitHub Pages**
   - Vá para "Settings" do repositório
   - No menu lateral, clique em "Pages"
   - Em "Build and deployment", selecione "Source: Deploy from a branch"
   - Escolha a branch `main` e a pasta `/ (root)`
   - Clique em "Save"

3. **Aguarde o deployment**
   - O site ficará disponível em: `https://seu-usuario.github.io/leticia-ramos/`

### Método 2: Via GitHub Desktop

1. **Clone o repositório**
   ```bash
   git clone https://github.com/seu-usuario/leticia-ramos.git
   cd leticia-ramos
   ```

2. **Copie os arquivos do projeto**
   - Copie todos os arquivos para a pasta do repositório

3. **Faça o commit e push**
   ```bash
   git add .
   git commit -m "Adicionando site profissional da Chef Letícia Ramos"
   git push origin main
   ```

4. **Siga os passos 2 e 3 do Método 1 para ativar o GitHub Pages**

## 🎨 Personalizações

### Cores e Identidade Visual

As cores principais estão definidas no arquivo `css/style.css`:

```css
:root {
    --primary-color: #722f37;    /* Vinho escuro */
    --secondary-color: #d4af37;   /* Dourado */
    --accent-color: #8b0000;      /* Vermelho bordô */
    --text-dark: #2c2c2c;        /* Texto principal */
    --text-light: #666;          /* Texto secundário */
    --bg-light: #f8f8f8;          /* Fundo claro */
    --bg-dark: #1a1a1a;           /* Fundo escuro */
    --white: #ffffff;             /* Branco */
    --cream: #faf6f2;             /* Creme */
}
```

### WhatsApp

O número de WhatsApp está configurado em vários lugares:

1. **Botão flutuante:** `index.html` (linha ~280)
2. **Botões CTA:** `index.html` (várias localizações)
3. **Link direto:** Substitua `553188841213` pelo número correto

### Imagens

Para adicionar imagens reais:

1. **Hero Section:** Substitua o placeholder em `.hero-image-placeholder`
2. **Sobre:** Substitua o placeholder em `.about-image-placeholder`
3. **Galeria:** Substitua os placeholders em `.gallery-placeholder`

Exemplo:
```html
<img src="images/foto-chef.jpg" alt="Chef Letícia Ramos" loading="lazy">
```

## 🔧 SEO e Performance

### Meta Tags

O site já está otimizado com:

- Título e descrição otimizados
- Open Graph para redes sociais
- Meta tags para palavras-chave
- Estrutura semântica HTML5

### Performance

- Lazy loading para imagens
- CSS e JavaScript otimizados
- Fontes Google pré-carregadas
- Animações com hardware acceleration

### Sitemap

O arquivo `sitemap.xml` está configurado para ajudar os motores de busca a indexar o site. **Lembre-se de atualizar a URL** `https://seu-dominio.com/` para o seu domínio real.

## 📱 Responsividade

O site é totalmente responsivo e funciona perfeitamente em:

- Desktop (1200px+)
- Tablet (768px - 1199px)
- Mobile (até 767px)

## 🎯 Recursos Principais

### Navegação
- Menu fixo com efeito de scroll
- Menu hambúrguer para mobile
- Scroll suave entre seções

### Animações
- Fade-in ao scroll
- Hover effects em cards
- Transições suaves
- Loading animation

### Chamadas para Ação
- Botão WhatsApp flutuante (canto inferior direito)
- Múltiplos botões CTA estratégicos
- Destaque visual para conversão

## 🌐 Domínio Personalizado

Para usar um domínio personalizado:

1. **Configure o DNS** para apontar para o GitHub Pages
2. **Adicione o arquivo CNAME** na raiz do projeto:
   ```
   seu-dominio.com
   ```
3. **Atualize as URLs** nos arquivos:
   - `index.html` (meta tags)
   - `sitemap.xml`
   - `robots.txt`

## 📈 Monitoramento

### Google Analytics

Para adicionar o Google Analytics:

1. Crie uma conta no Google Analytics
2. Adicione o script antes de `</head>` no `index.html`:
```html
<!-- Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=GA_MEASUREMENT_ID"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'GA_MEASUREMENT_ID');
</script>
```

### WhatsApp Business

Recomendações para o WhatsApp:

- Configure o WhatsApp Business
- Use uma mensagem de boas-vindas automatizada
- Crie respostas rápidas para perguntas frequentes
- Monitore o tempo de resposta

## 🛠️ Manutenção

### Atualizações Recomendadas

1. **Conteúdo:** Atualize depoimentos e galeria regularmente
2. **SEO:** Monitore o desempenho nos buscadores
3. **Imagens:** Comprima imagens para melhor performance
4. **Links:** Verifique se todos os links estão funcionando

### Backup

Mantenha um backup do projeto:
- Faça commit regularmente no GitHub
- Salve uma cópia local dos arquivos
- Documente todas as personalizações

## 📞 Suporte

Para dúvidas ou suporte técnico:

- Verifique o console do navegador para erros
- Teste em diferentes navegadores e dispositivos
- Valide o HTML e CSS regularmente

---

## 📋 Checklist de Publicação

- [ ] Upload de todos os arquivos para o GitHub
- [ ] Ativação do GitHub Pages
- [ ] Configuração do domínio (se aplicável)
- [ ] Atualização das URLs no sitemap.xml
- [ ] Teste de todos os links e botões
- [ ] Teste de responsividade
- [ ] Validação do HTML/CSS
- [ ] Configuração do Google Analytics (opcional)
- [ ] Teste do WhatsApp Business

---

**Desenvolvido com ❤️ para transformar a presença digital da Chef Letícia Ramos**
