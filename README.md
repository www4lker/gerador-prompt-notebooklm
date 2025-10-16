# 📚 Gerador de Prompts para NotebookLM

> Ferramenta web para criar prompts customizados e otimizados para a funcionalidade **"Create from zero"** (Reports customizados) do Google NotebookLM

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

## 🎯 O que é isso?

Esta ferramenta gera **system prompts otimizados** para usar na funcionalidade **"Create your own report"** do NotebookLM - o recurso que permite criar relatórios customizados do zero, com controle total sobre estrutura, tom e formato.

### 📋 Como funciona o "Create from zero" no NotebookLM

O NotebookLM possui um recurso avançado chamado **Reports** que vai além dos templates predefinidos:

1. **Acesse o painel "Studio"** após adicionar suas fontes
2. **Selecione "Report"** → **"Create your own report"**
3. **Cole o prompt gerado** por esta ferramenta no campo de instruções
4. **Configure parâmetros** (fontes incluídas, idioma, etc.)
5. **Gere seu relatório customizado** com estrutura acadêmica rigorosa

Esta ferramenta foi desenvolvida especificamente para **potencializar essa funcionalidade**, gerando prompts metodologicamente rigorosos que transformam o NotebookLM em um assistente de pesquisa acadêmica de alto nível.

## 🎓 Descrição

Uma ferramenta standalone (sem dependências) desenvolvida para pesquisadores, estudantes de pós-graduação e profissionais que trabalham com análise qualitativa, revisão bibliográfica e produção de conteúdo acadêmico usando NotebookLM.

## ✨ Características

- 🚀 **100% Offline** - Funciona sem internet após download
- 🎨 **Design Moderno** - Interface inspirada no Material Design do Google
- 📱 **Responsivo** - Funciona em desktop, tablet e mobile
- ⚡ **Zero Dependências** - HTML, CSS e JavaScript puro
- 🔒 **Privacidade Total** - Nenhum dado enviado para servidores
- 🎯 **8 Templates Especializados** - Cobrem diversos casos de uso acadêmico

## 🛠️ Templates Disponíveis

### 📋 **Arquivo de Referência**
Gera arquivo consultivo com citações ABNT e mapeamento epistemológico para uso como fonte de consulta rápida.

### 🎯 **Síntese para Projeto**
Produz síntese temática focada em aplicabilidade e transferibilidade conceitual para desenvolvimento de pesquisa original.

### ✍️ **Questões Ensaísticas**
Extrai questões complexas e problematizações críticas que demandam posicionamento teórico fundamentado.

### 🗺️ **Mapeador de Temas**
Identifica macrotemas com questões fundamentais e conexões interdisciplinares para discussão aprofundada.

### 🔍 **Análise de Lacunas**
Identifica sistematicamente lacunas metodológicas, teóricas e empíricas na literatura com questões de pesquisa derivadas.

### 🧬 **Codificação Temática**
Implementa análise qualitativa rigorosa com codificação, identificação de padrões e triangulação de achados.

### 🔬 **Arqueologia Conceitual**
Realiza escavação de pressupostos ocultos e mapeia interpretações alternativas plausíveis com neutralidade analítica.

### 🎙️ **Roteiro Podcast**
Transforma conteúdo acadêmico em roteiro modular para podcast com arquitetura narrativa (3 atos + epílogo) e scripts implementáveis.

## 🚀 Como Usar

### Instalação

1. **Download do arquivo**
   ```bash
   # Clone o repositório
   git clone https://github.com/seu-usuario/notebooklm-prompt-generator.git
   
   # Ou baixe diretamente o index.html
   ```

2. **Abra o arquivo**
   - Duplo clique no `index.html` 
   - Ou arraste para seu navegador preferido
   - Funciona em Chrome, Firefox, Safari, Edge

### Uso Básico

1. **Selecione um template** pré-definido ou digite seu próprio tipo de relatório
2. **Adicione foco específico** (opcional) para customizar ainda mais
3. **Clique em "Gerar Prompt"** para criar o prompt otimizado
4. **Copie o resultado** e cole no NotebookLM
5. **Adicione suas fontes** no NotebookLM e use o prompt gerado

### Exemplo de Fluxo

```
1. Abrir index.html no navegador
2. Selecionar template "🔍 Análise de Lacunas"
3. Adicionar foco: "Literatura sobre IA e educação publicada após 2020"
4. Gerar prompt
5. Copiar resultado (respeitando limite de 5000 caracteres)
6. Colar no NotebookLM com suas fontes carregadas
7. Obter análise estruturada de lacunas metodológicas, teóricas e empíricas
```

## 📐 Especificações Técnicas

- **Limite de caracteres**: Alerta visual quando prompt excede 5.000 caracteres (limite do NotebookLM)
- **Formato de saída**: Plain text otimizado para copiar/colar
- **Navegadores compatíveis**: Todos os navegadores modernos (Chrome 90+, Firefox 88+, Safari 14+, Edge 90+)
- **Tamanho do arquivo**: ~15KB (extremamente leve)

## 🎓 Casos de Uso

### Pesquisa Acadêmica
- Revisão sistemática de literatura
- Análise temática de dados qualitativos
- Identificação de gaps de pesquisa
- Mapeamento de frameworks teóricos

### Produção de Conteúdo
- Desenvolvimento de roteiros educacionais
- Criação de material didático
- Podcasts acadêmicos
- Ensaios e artigos científicos

### Análise Crítica
- Desconstrução de pressupostos teóricos
- Comparação de abordagens metodológicas
- Triangulação de perspectivas
- Validação de interpretações

## 🔧 Personalização

Os prompts base podem ser facilmente customizados editando o objeto `templates` no JavaScript:

```javascript
const templates = {
    'seu-template': 'descrição do tipo de análise desejada',
    // Adicione quantos templates personalizados desejar
};
```

## 🤝 Contribuindo

Contribuições são bem-vindas! Sinta-se livre para:

- 🐛 Reportar bugs via Issues
- 💡 Sugerir novos templates
- 🔧 Enviar Pull Requests com melhorias
- 📖 Melhorar a documentação
- ⭐ Dar uma estrela no repositório se achou útil

## 📄 Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

## 🙏 Agradecimentos

- Inspirado pela comunidade de pesquisadores usando NotebookLM
- Design baseado no Google Material Design
- Desenvolvido com foco em metodologia acadêmica rigorosa
- Gerado com ajuda do claude sonnet 4.5


---

**Nota**: Esta ferramenta é independente e não é oficialmente associada ao Google ou ao NotebookLM. É um projeto open-source criado para auxiliar a comunidade acadêmica.

**Desenvolvido com ❤️ para pesquisadores e estudantes**
