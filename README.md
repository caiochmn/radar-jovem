# 🎯 Radar Jovem

> **Descubra todas as oportunidades que você ainda pode alcançar pela sua idade.**

Radar Jovem é uma ferramenta que ajuda jovens a descobrir concursos militares, olimpíadas, intercâmbios, bolsas e outras oportunidades com **janela de idade** — aquelas que fecham em determinados períodos da vida.

📱 **Progressive Web App** • 🎨 **Design moderno** • 📊 **Base de dados verificada** • 🚀 **Zero dependências externas**

---

## ✨ Features

- **Busca por idade**: Digite sua idade e veja *todas* as oportunidades ainda ao seu alcance
- **Categorias variadas**: Militares, olimpíadas, intercâmbios, bolsas, concursos
- **Offline**: Funciona perfeitamente sem internet (PWA)
- **Design responsivo**: Mobile-first, funciona em qualquer dispositivo
- **Dados atualizados**: Base verificada em julho de 2026

---

## 🚀 Como usar

### Online
Acesse diretamente: **[radar-jovem.github.io](https://caiochmn.github.io/radar-jovem)**

### Localmente
```bash
# Clone o repositório
git clone https://github.com/caiochmn/radar-jovem.git
cd radar-jovem

# Abra no navegador
# Opção 1: Clique duplo em index.html
# Opção 2: Use um servidor local (Node.js)
node serve.js
# Acesse http://localhost:3000
```

---

## 📁 Estrutura

```
radar-jovem/
├── index.html          # Página principal
├── data.js             # Base de dados de oportunidades
├── serve.js            # Servidor local (Node.js)
├── sw.js               # Service Worker (offline)
├── manifest.json       # Configuração PWA
├── oportunidades.json  # Dados em JSON (backup)
└── icon.svg            # Ícone da aplicação
```

---

## 🛠 Desenvolvimento

### Adicionar novas oportunidades

Edite `data.js` e adicione um novo objeto à array `DB`:

```javascript
{
  id: "meu-concurso",
  nome: "Meu Concurso",
  categoria: "categoria",
  orgao: "Órgão responsável",
  resumo: "Descrição breve",
  idade_min: 16,
  idade_max: 25,
  regra_idade: "Regra específica",
  fases: ["em", "emc"],  // Fases educacionais
  escolaridade: "Requisito",
  gratuito: true,
  custo: "Descrição de custo",
  epoca: "Quando acontece",
  vagas: "~Número",
  link: "https://...",
  status: "verificado"
}
```

### Compilar/Build

Não há build necessário. O projeto é 100% estático e funciona direto.

---

## 📊 Base de dados

A base contém **+80 oportunidades** em categorias:

- 🪖 **Militares**: EPCAR, AFA, Intendência, AMAN, ESPCEX...
- 🏅 **Olimpíadas**: Matemática, Física, Programação, Astronomia...
- 🌍 **Intercâmbios**: Youth For Understanding, Rotary, AFS...
- 💰 **Bolsas**: Bolsa Família, FIES, universidades privadas...
- 🎓 **Concursos**: ENEM, Vestibulares, Programas especiais...

---

## 🔒 PWA (Progressive Web App)

Instale como app nativo:

**Desktop (Chrome/Edge):**
- Clique no ícone de instalação na barra de endereço
- Ou: Menu → Mais ferramentas → Criar atalho

**Mobile (Android):**
- Chrome → Menu → Instalar app

**iOS:**
- Safari → Compartilhar → Adicionar à tela inicial

---

## 🎨 Cores & Design

- **Background**: `#131a10` (verde muito escuro)
- **Acento**: `#b8e986` (verde brilhante)
- **Alerta**: `#ffa38f` (coral suave)
- **Font**: Segoe UI / System fonts

---

## 📄 Licença

Projeto pessoal • Livre para usar e modificar

---

## 👤 Autor

**Caio Novais**  
[GitHub](https://github.com/caiochmn) • [Email](mailto:caio.novais@voeazul.com.br)

---

## 🤝 Contribuindo

Encontrou uma oportunidade faltando ou dados desatualizados?  
Abra uma [Issue](https://github.com/caiochmn/radar-jovem/issues) ou envie um PR! 

---

**Última atualização:** Julho 2026
