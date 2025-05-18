# Projeto de Criação de Conteúdo Inteligente para Conexão Saúde-IA
## Unindo Conhecimento e Acessibilidade na Área da Saúde

[![Licença](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
![Python](https://img.shields.io/badge/Python-3.x-blue.svg)
[![Google Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/SEU_LINK_DO_COLAB_AQUI)

## 🌟 Visão Geral

A comunicação eficaz na saúde é fundamental para o bem-estar. Este projeto propõe um sistema inovador, impulsionado por Inteligência Artificial e arquitetura de agentes, para automatizar e otimizar a criação de conteúdo de saúde. Nosso objetivo é construir uma ponte de conhecimento, transformando informações complexas em conteúdo acessível e relevante tanto para pacientes quanto para profissionais da saúde, promovendo uma conexão mais forte e informada.

Este projeto demonstra como agentes de IA podem colaborar para:

* **Identificar Tendências:** Descobrir os avanços mais recentes e relevantes na área da saúde.
* **Planejar Conteúdo Estratégico:** Organizar informações e definir abordagens que ressoem com diferentes públicos.
* **Criar Conteúdo Engajador:** Redigir materiais claros, precisos e adaptados para plataformas como o Instagram.
* **Garantir a Qualidade e Precisão:** Revisar o conteúdo para assegurar sua confiabilidade e adequação.

## 🛠️ Tecnologias Utilizadas

* **Google GenAI:** Biblioteca para interagir com os modelos Gemini do Google.
* **Google ADK (Agent Development Kit):** Framework para construir e orquestrar arquiteturas de agentes inteligentes.
* **Python:** Linguagem de programação principal.
* **Google Search:** Ferramenta utilizada pelos agentes para buscar informações atualizadas.
* **Google Colab:** Ambiente de desenvolvimento utilizado para prototipagem e execução do código.

## 🚀 Começando

### Pré-requisitos

* Uma conta Google.
* Acesso ao Google AI Studio para obter uma API Key.
* Conhecimento básico de Python.
* Familiaridade com o Google Colab (opcional, mas recomendado para executar o notebook).

### Instalação

1.  Clone este repositório (se aplicável):
    ```bash
    git clone [https://github.com/SEU_USUARIO/SEU_REPOSITORIO.git](https://github.com/SEU_USUARIO/SEU_REPOSITORIO.git)
    cd SEU_REPOSITORIO
    ```

2.  Abra o notebook `ProjetoALURA.ipynb` no Google Colab.

3.  Execute a célula de instalação das bibliotecas necessárias:
    ```python
    %pip install -q google-genai google-adk
    ```

4.  **Configuração da API Key:**
    * Acesse o ícone de chave (`🔑`) na barra lateral esquerda do Google Colab para abrir a seção "Segredos".
    * Adicione um novo segredo com o nome `GOOGLE_API_KEY` e cole sua API Key do Google AI Studio no campo "Valor".
    * Execute a célula de configuração da API Key no notebook para carregá-la como uma variável de ambiente.

## ⚙️ Arquitetura do Sistema

O sistema de criação de conteúdo é estruturado como um pipeline de agentes especializados:

1.  **Agente Buscador de Tendências em Saúde (`agente_buscador_saude`):**
    * Responsável por buscar informações relevantes e atuais sobre um tópico de saúde específico utilizando a ferramenta de busca do Google.
    * Prioriza fontes confiáveis e informações recentes (último mês).
    * Retorna um resumo das principais tendências e lançamentos encontrados.

2.  **Agente Planejador de Conteúdo para Conexão Saúde (`agente_planejador_saude`):**
    * Analisa as informações buscadas e estrutura um plano detalhado para um post de Instagram.
    * Identifica pontos relevantes para pacientes e profissionais de saúde, explicando a importância para cada público.
    * Define os tópicos a serem abordados e sugere formatos/abordagens para o post no Instagram.

3.  **Agente Redator de Posts Engajadores de Saúde (`agente_redator_saude`):**
    * Utiliza o plano de conteúdo para redigir um rascunho de post para o Instagram.
    * Emprega linguagem clara, acessível e engajadora, evitando jargões técnicos.
    * Inclui uma introdução cativante, chamada para ação e hashtags relevantes.

4.  **Agente Revisor de Qualidade em Saúde (`agente_revisor_saude`):**
    * Avalia o rascunho do post quanto à precisão da informação, clareza, relevância para o público, tom e concisão.
    * Retorna um feedback com aprovação ou sugestões de melhorias específicas.

## 🕹️ Como Usar

1.  Execute as células de configuração e importação no notebook.
2.  Na seção do **Agente 1: Buscador de Tendências em Saúde**, insira o tópico de saúde desejado quando solicitado:
    ```
    ❓ Por favor, digite o TÓPICO de saúde para buscar tendências:
    ```
3.  Execute a célula para ver o agente buscar as informações.
4.  As informações buscadas serão automaticamente passadas para o **Agente 2: Planejador de Conteúdo para Conexão Saúde**. Execute a célula para gerar o plano do post.
5.  O plano gerado será utilizado pelo **Agente 3: Redator de Posts Engajadores de Saúde**. Execute a célula para obter o rascunho do post para o Instagram.
6.  Finalmente, o rascunho será avaliado pelo **Agente 4: Revisor de Qualidade em Saúde**. Execute a célula para obter o feedback sobre o post.

Você pode interagir com o sistema ajustando o tópico de saúde e observando como os diferentes agentes colaboram para gerar o conteúdo final.

## 🤝 Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues para relatar bugs ou sugerir melhorias. Se quiser contribuir com código, por favor, siga estas etapas:

1.  Faça um fork do repositório.
2.  Crie uma branch para sua feature (`git checkout -b feature/sua-feature`).
3.  Faça o commit das suas mudanças (`git commit -am 'Adiciona sua feature'`).
4.  Faça o push para a branch (`git push origin feature/sua-feature`).
5.  Abra um Pull Request.

## 📄 Licença

Este projeto está sob a licença MIT. Consulte o arquivo [LICENSE](LICENSE) para obter mais detalhes.

## ✉️ Contato

Se tiver alguma dúvida ou sugestão, sinta-se à vontade para entrar em contato:

* Seu Nome: Gustavo Marques
* Seu Email: gutosantosx@gmail.com
* Seu GitHub: https://github.com/GustavoMarques22

---

**Esperamos que este projeto seja útil para a criação de conteúdo de saúde impactante e acessível!**
