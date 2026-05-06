# Gastro-Tag

O **Gastro-Tag** é um sistema de software desenvolvido para auxiliar na identificação e rotulagem de alimentos dentro de cozinhas pedagógicas e depósitos. O sistema automatiza o processo de registro de abertura de insumos, calcula datas de descarte baseadas em normas técnicas e gera etiquetas prontas para impressão, substituindo métodos manuais ineficientes.

## 📌 Introdução

O sistema opera em um **terminal eletrônico fixo** dentro do ambiente da cozinha. Funcionários autorizados utilizam a interface para preencher informações sobre as condições do alimento, e o software processa esses dados para emitir etiquetas de identificação precisas, garantindo a segurança alimentar e a rastreabilidade dos processos.

## 🚀 Principais Funcionalidades

* **Cadastro de Produtos:** Inserção detalhada de dados, incluindo nome, marca, prazo de validade original e regras específicas para o pós-abertura.
* **Busca Otimizada:** Localização rápida de produtos cadastrados apenas digitando parte do nome.
* **Cálculo Automático de Validade:** Determinação precisa da nova data de descarte com base na data de abertura e no tipo de armazenamento (**refrigerado ou congelado**).
* **Alerta Visual de Vencimento:** Diferenciação visual na interface (sistema de cores por mês) para identificar produtos que estão próximos da data de descarte.
* **Geração de Etiquetas:** Layout automático contendo nome, lote, data de abertura, nova data de validade, modo de armazenamento, temperatura e campo para assinatura.
* **Identidade Visual:** Módulo para inclusão de logotipos institucionais (como o do **SENAC-AM**) diretamente nas etiquetas impressas.
* **Controle de Responsabilidade:** Registro do funcionário responsável pela manipulação do produto diretamente na etiqueta.

## 🛠️ Requisitos do Sistema

* **Hardware:** Terminal de computador fixo ou computador dedicado (**não suporta dispositivos móveis/tablets**).
* **Impressão:** Impressora térmica ou mini impressora de etiquetas configurada para operação local.
* **Persistência:** Banco de dados relacional para armazenamento de produtos, usuários e histórico de etiquetas geradas.
* **Tempo de Operação:** O sistema deve permitir a conclusão do processo de rotulagem em aproximadamente 5 minutos.

## ⚖️ Conformidade e Regras Técnicas

O desenvolvimento e a lógica de cálculo do sistema seguem rigorosamente as resoluções e regulamentos aplicáveis à rotulagem e validade de alimentos, especificamente a **RDC 216** e normas correlatas da **Anvisa**.

## 🚫 Exclusões do Escopo (MVP)

Para manter o foco na rotulagem e eficiência operacional, as seguintes funcionalidades não estão inclusas nesta versão inicial:
* Controle de estoque ou inventário quantitativo.
* Gestão de desperdício ou pesagem de sobras.
* Integração com leitura de QR Codes ou códigos de barras.

## 👥 Colaboradores (3º Período - ADS)

* Bianka Rocha da Silva
* Carlos Felipe
* Francisco Sinval
* João Pedro Garcia
* Sávio José
