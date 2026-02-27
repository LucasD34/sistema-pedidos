# 📦 Sistema de Gestão de Pedidos - Elka (Produção & Estoque)

> Solução em tempo real para comunicação e logística interna, integrando a linha de produção ao setor de estoque.

---

## 📝 Sobre o Projeto
Este sistema foi desenvolvido para digitalizar e acelerar o fluxo de pedidos de peças. Ele elimina a necessidade de comunicações manuais lentas, permitindo que a **Produção** solicite itens e o **Estoque** receba alertas instantâneos para separação.

O diferencial técnico é a atualização **bi-direcional em tempo real**: quando o estoque dá baixa em um material, a produção visualiza a confirmação na mesma hora, sem precisar atualizar a página.

## 🚀 Funcionalidades Principais

### 🏭 Painel da Produção (`producao.html`)
* **Solicitação Ágil:** Formulário validado para envio de pedidos (Peça, Referência e Encarregada).
* **Campo de Observação:** Permite adicionar detalhes específicos que aparecem em destaque para o estoquista.
* **Status em Tempo Real:** Visualização imediata de quais pedidos ainda estão pendentes e quais já foram enviados.

### 📦 Painel do Estoque (`estoque.html`)
* **Alertas Sonoros:** Notificação por áudio sempre que um novo pedido entra na fila.
* **Gestão de Envios:** Botão para marcar pedidos como "Enviados" com registro automático de data e hora.
* **Contador Inteligente:** Badge flutuante que exibe o total de pedidos ativos no banco de dados.
* **Modo de Edição:** Permite que o estoque adicione uma observação de retorno antes de finalizar o envio.

## 🛠 Tecnologias Utilizadas
* **Linguagem:** JavaScript (ES6+)
* **Interface:** HTML5 & CSS3 (Design moderno e responsivo)
* **Banco de Dados:** [Firebase Realtime Database](https://firebase.google.com/)
* **Notificações:** Web Audio API

## ⚙️ Como Instalar e Usar

1. **Clonagem do Repositório:**
   ```bash
   git clone [https://github.com/seu-usuario/nome-do-repositorio.git](https://github.com/seu-usuario/nome-do-repositorio.git)
