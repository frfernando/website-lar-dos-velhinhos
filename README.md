<div align="center">
  <h1>🤝 Portal Institucional · Lar dos Velhinhos de Regente Feijó - SP</h1>
  <p><strong>Plataforma Social de Acolhimento à Terceira Idade · Módulo de Doações PIX & Portal da Transparência</strong></p>
  <p>
    <a href="https://github.com/frfernando/website-lar-dos-velhinhos"><img src="https://img.shields.io/badge/Status-Produção-22c55e?style=for-the-badge&logo=statuspage&logoColor=white" alt="Status" /></a>
    <a href="https://github.com/frfernando/website-lar-dos-velhinhos"><img src="https://img.shields.io/badge/Impacto-Filantropia_&_Doações-FF5F00?style=for-the-badge&logo=heart&logoColor=white" alt="Impacto" /></a>
    <a href="https://github.com/frfernando/website-lar-dos-velhinhos"><img src="https://img.shields.io/badge/Conformidade-MROSC_&_LAI-3b82f6?style=for-the-badge&logo=civicrm&logoColor=white" alt="Transparência" /></a>
  </p>
</div>

---

## 📌 Visão Geral do Estudo de Caso

O **Lar dos Velhinhos de Regente Feijó - SP** é uma Instituição de Longa Permanência para Idosos (ILPI) sem fins lucrativos que oferece assistência integral, saúde, nutrição e carinho a idosos em situação de vulnerabilidade social.

O projeto consistiu em construir o portal oficial da entidade, unindo duas necessidades vitais: **facilidade extrema para pessoas da comunidade realizarem doações via PIX** e **transparência pública irrestrita**, garantindo a conformidade fiscal e jurídica com o Marco Regulatório das Organizações da Sociedade Civil (MROSC).

---

## 🔍 O Antes (O Desafio)

* **Dificuldade na Arrecadação Contínua:** A instituição dependia quase exclusivamente de eventos físicos esporádicos (bazares, rifas e jantares beneficentes).
* **Falta de um Canal Digital Seguro para Doar:** Doadores queriam contribuir mensalmente ou pontualmente pelo celular, mas não encontravam a chave PIX e os dados bancários oficiais com clareza.
* **Exigência Legal de Transparência Não Atendida Online:** Órgãos fiscalizadores e parceiros institucionais exigiam a publicação pública de atas, balanços contábeis e termos de fomento, que antes ficavam arquivados apenas em papel na secretaria.

---

## 💡 O Porquê (A Estratégia de Engenharia)

* **Por que Módulo Dedicado de Doações com PIX Copia-e-Cola?**  
  Implementação de botão inteligente com cópia com 1 clique da chave PIX e QR Code escaneável, eliminando erros de digitação e permitindo doações imediatas pelo app bancário do celular em menos de 10 segundos.
* **Por que Portal Público de Transparência (`transparencia.html`)?**  
  Criação de uma área estruturada para disponibilização de demonstrativos financeiros, certidões negativas de débito e relatórios anuais de atividades, gerando credibilidade inabalável perante o Ministério Público e o Conselho Municipal do Idoso.
* **Por que Acessibilidade Especial para Famílias e Doadores Idosos?**  
  Tipografia de alta legibilidade, botões com dimensões confortáveis, contraste visual calibrado e ausência de elementos visuais distorcidos ou confusos.

---

## 🚀 O Depois (Resultados & Impacto)

| Métrica / Critério | Cenário Anterior | Novo Portal Lar dos Velhinhos |
|---|---|---|
| **Tempo para Realizar uma Doação** | Visita presencial ou depósito em agência | **⚡ &lt; 15 segundos (PIX Instantâneo)** |
| **Transparência Contábil & Governança** | Documentos restritos a arquivos físicos | **Acesso público e irrestrito 24/7 online** |
| **Acessibilidade para Terceira Idade** | Inexistente | **Contraste calibrado e textos claros sem jargões** |
| **Canal de Voluntariado e Contato** | Telefonia fixa oscilante | **Integração direta com o WhatsApp da secretaria** |

---

## 🧰 Estrutura de Páginas & Stack Tecnológica

* **Páginas Modulares:**
  * `index.html`: Página principal com apresentação, missão, depoimentos e chamadas de solidariedade.
  * `doar.html`: Módulo interativo de captação de doações com chave PIX e dados bancários protegidos.
  * `transparencia.html`: Portal oficial de prestação de contas, balanços patrimoniais e termos de colaboração.
  * `como-ajudar.html`: Diretrizes para doação de fraldas, alimentos e trabalho voluntário.
  * `quem-somos.html` & `contato.html`: História institucional, diretoria e mapa de localização.
* **Tecnologias:** `HTML5 Semântico`, `CSS3 Moderno`, `Design Responsivo Mobile-First` e `Micro-interações de Clipboard`.

---

## 🛠️ Como Executar o Projeto Localmente

```bash
# 1. Clonar o repositório
git clone https://github.com/frfernando/website-lar-dos-velhinhos.git
cd website-lar-dos-velhinhos

# 2. Servir os arquivos
python3 -m http.server 8080
# Acesse no navegador: http://localhost:8080
```

---

<div align="center">
  <p>Engenharia e Arquitetura desenvolvidas por <b><a href="https://github.com/frfernando">Fernando Reis</a></b> · <b><a href="https://sanbernarda.com">SanBernarda Studio</a></b></p>
</div>
