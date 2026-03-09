<div align="center">
  <img src="https://cdn-icons-png.flaticon.com/512/2092/2092663.png" alt="Security Shield" width="120" />

  <h1>🛡️ Security Management: IAM & Vulnerability</h1>
  <p><em>Gestão de Vulnerabilidades e Resposta a Incidentes</em></p>

  <p>
    <img src="https://img.shields.io/badge/Disciplina-Security_Management-blue?style=for-the-badge&logo=shield" alt="Disciplina" />
    <img src="https://img.shields.io/badge/Professor-Jos%C3%A9_Ricardo_Machado-darkred?style=for-the-badge&logo=google-scholar" alt="Professor" />
  </p>
</div>

---

## 📖 Sobre a Disciplina

A disciplina de **Security Management (Vulnerability and Response)** tem como premissa capacitar no entendimento profundo do que é a informação e sua importância para os negócios. Com base em frameworks como **ITIL v4** e melhores práticas de segurança, o conteúdo aborda desde a estruturação de Segurança da Informação (SI) até metodologias práticas de Resposta a Incidentes e Gestão de Vulnerabilidades.

> **Observação:** O conteúdo desta página baseia-se no PDF "Management Aula 001" (único material disponível na pasta do projeto).

## 🎯 Principais Objetivos

- **Definição e Valor:** Identificar o que é e qual a importância da informação para o negócio.
- **Gestão de Riscos (GRC):** Mapear, identificar e gerenciar os riscos de SI.
- **Resposta a Incidentes:** Traçar estratégias eficazes frente a violações.
- **Gestão de Vulnerabilidades:** Teoria e prática na proteção de ativos e gestão de identidades e senhas (**IAM**).
- **Conscientização:** Defesa contra Engenharia Social através de programas e campanhas (ex: *Ethical Phishing*).

---

## 🛡️ Pilares da Segurança da Informação (Tríade CID)

Garantir que a empresa opere sem interrupções críticas minimizando riscos. Os três pilares fundamentais são:

```mermaid
mindmap
  root((Tríade CID))
    Confidencialidade
      ::icon(fa fa-user-secret)
      Impedir acessos não autorizados
      Conformidade Legal (LGPD, GDPR)
      Proteger segredos comerciais
    Integridade
      ::icon(fa fa-lock)
      Impedir modificações não autorizadas
      Evitar fraudes ou manipulação de dados
    Disponibilidade
      ::icon(fa fa-server)
      Prevenir downtime (Ransomware, DDoS)
      Garantir acesso e continuidade
```

---

## 🔄 Ciclo de Vida da Informação

A informação não é estática, ela deve ser protegida continuamente de acordo com seu **valor intrínseco**:

```mermaid
flowchart LR
    A[Criada] --> B[Armazenada]
    B --> C[Processada]
    C --> D[Transmitida]
    D --> E[Utilizada]
    E --> F[Mantida]
    F --> G[Descartada]

    style A fill:#e1f5fe,stroke:#01579b
    style B fill:#e3f2fd,stroke:#1565c0
    style C fill:#bbdefb,stroke:#0d47a1
    style D fill:#90caf9,stroke:#0b3c5d
    style E fill:#64b5f6,stroke:#0b3c5d
    style F fill:#42a5f5,stroke:#0b3c5d
    style G fill:#ffebee,stroke:#b71c1c
```

---

## 🧠 Estrutura do Conhecimento

A evolução até a tomada de decisão estruturada segue uma cadeia lógica:

1. **Dado:** Elemento bruto sem contexto (ex: "1.200 acessos").
2. **Informação:** Dados com contexto (ex: "1.200 acessos ocorreram em julho").
3. **Conhecimento:** Interpretação da informação (ex: "acessos estão 20% acima da média").
4. **Sabedoria:** Capacidade de agir com base ética e estratégia de longo prazo.

---

## 👩‍🏫 Docência e Contato

**Professor: José Ricardo Machado**
- 🎓 _Coordenador de Infraestrutura, Arquitetura e GRC no SOC da Embratel_
- 💼 Experiência: 16+ anos em TI, Segurança, IAM, Gestão de Riscos e Compliance.
- 📧 Contato: `profjose.machado@fiap.com.br`

---
<div align="center">
  <p>Feito com 💻 e 🛡️ para documentação de aulas.</p>
</div>