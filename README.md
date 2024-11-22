# Logtech MicroSaaS 🚛📦

Bem-vindo ao repositório do projeto **Logtech MicroSaaS**! Este é um sistema inovador para otimizar a experiência de entregas, trazendo previsões precisas e interatividade para clientes, entregadores e administradores.

---

## 💡 Propósito

O **Logtech MicroSaaS** focada para o pequeno empresario e na peerspesctiva do Last Mile, tem como objetivo principal realizar previsões de entrega em tempo real, 
com interações dinâmicas entre cliente final, entregador e administração. Isso reduz falhas de entrega, melhora a eficiência operacional e eleva a satisfação do cliente.

---

## 🎯 Personas

### 1️⃣ **Cliente Final**
- Recebe notificações por e-mail e whatsapp com previsão de entrega.  
- Pode confirmar ou reagendar a entrega.  
- Garante flexibilidade e conveniência no recebimento.


### 2️⃣ **Entregador**
- Recebe atualizações em tempo real sobre a entrega.  
- É notificado em caso de alterações para evitar deslocamentos desnecessários.  
- Conta com rotas otimizadas com base na interação dos clientes.

### 3️⃣ **Administração**
- Uma base do LAST MILE recebe ordem de pedido no qual sera convertido em um codigo interno para monitoramento ao longo da entrega .
- Acompanha e gerencia o status das entregas.  
- Visualiza métricas e relatórios para tomada de decisão.  
- Centraliza informações para melhorar a eficiência operacional.

---

## 🏗️ Arquitetura

- **Modelo de Negócio:** MicroSaaS com planos de assinatura mensal escaláveis.  
- **Wireframes/Userflow:** Desenvolvidos no [Figma](https://figma.com).  
- **Backend:** Monolítico utilizando **C#**.  
- **Banco de Dados:** **SQLite** para simplicidade e rapidez.  
- **API:** Criada em **Python**, integrada ao Google Maps para gerar previsões de entrega em tempo real.  
- **Tecnologia de Notificação:** E-mails automatizados utilizando a API Google mails.

---

## 🔑 Funcionalidades

1. **Previsão de entrega dinâmica:** Atualizada em tempo real após cada entrega.  
2. **Interação com o cliente final:** Permite confirmar ou reagendar a entrega.  
3. **Rotas otimizadas para entregadores:** Baseadas na resposta do cliente.  
4. **Painel administrativo:** Controle centralizado das operações e métricas.  

---

## 🚀 Como usar este projeto

### Pré-requisitos
1. **Ferramentas de desenvolvimento:**  
   - Visual Studio code para o backend em C#.  
   - Python 3.10+ para a API ou C# mesmo.  
   - SQLite como banco de dados.

2. **APIs externas:**  
   - Configuração da API Google Maps para integração para calculos de distancia.

### Passos para rodar o projeto
1. Clone este repositório:
   ```bash
   git clone https://github.com/SEU_USUARIO/SEU_REPOSITORIO.git
   cd SEU_REPOSITORIO
