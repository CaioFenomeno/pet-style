# 🐶 Pet&Style — Documentação do Projeto

## 📌 Sobre o Projeto

Pet&Style é uma landing page simples criada para apresentar produtos pet com foco em design, usabilidade e estética. O objetivo principal é oferecer uma experiência leve e agradável para o usuário, apresentando produtos, depoimentos e informações de contato de forma organizada.

Este projeto também serviu como base para aplicar técnicas de otimização de performance, melhorando tempo de carregamento, renderização e experiência geral.

---

## 🎨 Estrutura do Projeto

O site é composto por seções principais:

### **1️⃣ Cabeçalho (Header)**

* Exibe o nome da loja (Pet&Style)
* Menu de navegação com links para Produtos, Contato e Depoimentos
* Layout responsivo

### **2️⃣ Seção Hero**

* Imagem principal destacando a marca
* Título e subtítulo curtos para impacto imediato
* Imagem otimizada para carregamento rápido

### **3️⃣ Produtos**

* Exibição de uma grade com quatro produtos
* Cada produto contém:

  * Imagem
  * Título
  * Descrição curta
  * Preço
* Layout responsivo para diferentes tamanhos de tela

### **4️⃣ Depoimentos**

* Três depoimentos simples de clientes
* Apresentados em cards leves
* Foco em credibilidade da marca

### **5️⃣ Contato**

* Informações de contato direto (e-mail e telefone)
* Formulário simples com nome, e-mail e mensagem

### **6️⃣ Rodapé**

* Direitos reservados

---

## ⚙️ Tecnologias Utilizadas

* **HTML5** → estrutura semântica do conteúdo
* **CSS puro** → estilização manual otimizada
* **Imagens WebP** → formato mais leve e eficiente
* **Lazy Loading** → carregamento sob demanda de imagens secundárias
* **Responsividade** → grid adaptável e layout fluido

Não há uso de JS adicional, frameworks ou bibliotecas externas.

---

## 🚀 Otimizações Implementadas

Mesmo sem prints, segue a explicação das melhorias aplicadas ao projeto para torná-lo mais eficiente:

### ✔ CSS crítico escrito manualmente

* Remoção total do Tailwind CDN
* CSS reduzido e carregado imediatamente
* Evita carregamento de centenas de KB desnecessários

### ✔ Imagens otimizadas

* Uso do formato **WebP** para reduzir tamanho
* Definição de `width` e `height` para evitar layout shift
* Resoluções limitadas (`w=...` na URL do Unsplash)
* `loading="lazy"` para imagens abaixo da dobra

### ✔ HTML minimalista

* Estrutura enxuta
* Sem código redundante
* Sem scripts bloqueando renderização

### ✔ Melhorias em acessibilidade

* Labels para inputs
* Marcação semântica
* Contraste visual mais estável

---

## 📈 Impacto das Otimizações

Após aplicar as melhorias, o projeto ficou:

* **Muito mais rápido para carregar**, especialmente em conexões móveis
* **Com melhor LCP**, graças à imagem principal otimizada
* **Com menor consumo de rede**, devido ao CSS leve e imagens menores
* **Com navegação mais suave**, sem travamentos ou reflows
* **Com layout mais estável**, evitando mudanças bruscas ao carregar imagens

Essas otimizações tornam o site mais profissional e adequado a boas práticas de performance web.

---

## 📚 Conclusão

O projeto Pet&Style demonstra como uma página simples pode atingir alto desempenho ao aplicar técnicas fundamentais de otimização, como uso de imagens modernas, CSS crítico, lazy-loading e melhorias estruturais.

A página final é leve, rápida, responsiva e alinhada com boas práticas atuais do desenvolvimento front-end.

Se quiser adicionar mais seções, animações ou funcionalidades, o projeto está bem estruturado para continuar crescendo.
