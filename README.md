
# Smart Ticket Router

**Roteador Inteligente de Mensagens em Sistemas Críticos para Chamados**

Este projeto tem como objetivo desenvolver um sistema baseado em mensageria assíncrona (RabbitMQ) para roteamento inteligente de chamados acadêmicos, administrativos e de TI. Ele permite direcionar automaticamente chamados para as filas corretas (Secretaria, TI, Helpdesk), com base em regras de negócio e futuramente com técnicas de Machine Learning.

---

## 🧩 Objetivos

- Organizar chamados por categoria (Secretaria, TI, Helpdesk)
- Reduzir o tempo de resposta com roteamento inteligente
- Escalonar chamados críticos automaticamente
- Prover estrutura para uso de Machine Learning (categorização e priorização)

---

## ⚙️ Tecnologias

- .NET Core (C#)
- RabbitMQ
- Docker
- PostgreSQL
- Python (futuramente para NLP)

---

## 📦 Estrutura Inicial (WIP)

📁 SmartTicketRouter/
├── producer/ # Geração e envio de chamados
├── router/ # Lógica de roteamento inteligente
├── consumers/ # Consumidores por setor (TI, Secretaria, Helpdesk)
├── shared/ # Contratos e modelos
└── README.md


---

## 📅 Roadmap (Início)

- [x] Definição da arquitetura de filas
- [ ] Implementação do produtor de chamados
- [ ] Implementação do roteador inteligente com base em palavras-chave
- [ ] Separação das filas por setor
- [ ] Notificações e escalonamento de SLA
- [ ] Protótipo de painel simples (opcional)

---

## 📜 Licença

Projeto acadêmico em fase inicial. Sem licença aberta definida ainda.

---

## 🤝 Contribuição

Ainda em desenvolvimento. Sugestões são bem-vindas!
