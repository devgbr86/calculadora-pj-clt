# calculadora-pj-clt
Calculadora PJxCLT
# 🧮 Calculadora PJ vs CLT

Projeto simples para comparar a remuneração líquida entre os regimes de trabalho **CLT** e **PJ**.  
O objetivo é mostrar, de forma clara, as diferenças entre salário, benefícios e custos de cada modelo.

---

## 🚀 Como funciona
- O usuário insere:
  - **Salário bruto**
  - **Benefícios CLT** (vale-alimentação, vale-transporte, plano de saúde etc.)
  - **Custos PJ** (impostos, contador, previdência etc.)
- A aplicação realiza os cálculos (CLT e PJ).
- Mostra os resultados em uma **tabela comparativa**.

---

## 📂 Estrutura do Projeto

```

calculadora-pj-clt/
│
├── index.html       # Estrutura principal da aplicação
├── clt.js           # Funções de cálculo CLT (INSS, IRRF, FGTS etc.)
├── pj.js            # Funções de cálculo PJ (Simples, INSS autônomo etc.)
├── comparador.js    # Junta os cálculos e gera a tabela final
├── style.css        # Estilos visuais
└── README.md        # Este arquivo

```

---

## 📌 Regras de Cálculo
As regras de cálculo devem ser baseadas em fontes oficiais e atualizadas:

- **CLT**
  - INSS
  - IRRF
  - FGTS
  - Benefícios (VA/VT/Plano de saúde etc.)

- **PJ**
  - Impostos (Simples Nacional, ISS, INSS autônomo, quando aplicável)
  - Custos operacionais (contador, previdência, plano de saúde etc.)

---

## 🛠 Tecnologias
- HTML5
- CSS3
- JavaScript (puro)

---

## 📖 Próximos Passos
- Implementar regras de cálculo corretas (com base nas tabelas oficiais).
- Melhorar visualização da comparação (gráficos ou destaques).
- Adicionar testes básicos de validação.

---

## 📄 Licença
Este projeto é de uso livre para estudo e aprendizado.
```

---
