# 🇲🇿 MZN POS SaaS Inteligente - Moçambique

Software comercial completo de Ponto de Venda (POS) e ERP Multi-Loja operando nativamente em **Meticais (MZN)**, desenhado sob a arquitetura de subscrições SaaS.

## 🚀 Recursos Principais
*   **Frente de Caixa Tátil (Kivy Android):** Otimizado para tablets e terminais com carteiras móveis integradas (**M-Pesa, e-Mola, mKesh**).
*   **Controlo de Mensalidades Progressivo:** Bloqueio automático de caixas ao balcão caso a filial falte ao pagamento do plano.
*   **Preços de Escala SaaS:** Lógica dinâmica de faturação integrada (1.000 MT a 10.000 MT/mês).
*   **Inteligência Artificial Distribuída:** Algoritmos preditivos de Cross-selling para o Caixa, Runway de Stock para o Gerente e Monitor de Churn e Forecast de Faturação de 90 dias para o Proprietário.
*   **Impressão Comercial:** Emissão automática de talões térmicos de 80mm e etiquetas de stock (50x30mm) com códigos de barras legíveis.

## 🛠️ Como Executar o Projeto Localmente
1. Instale os requisitos obrigatórios no seu computador:
   ```bash
   pip install -r requirements.txt
   ```
2. Execute o ecossistema integrado:
   ```bash
   python pos_system_android_full.py
   ```

## 📦 Credenciais de Teste Padrão
*   **Dono do Software (Admin Master):** `admin` / `admin`
*   **Gerente Regional:** `gerente` / `gerente123`
*   **Operador de Caixa (Maputo):** `caixa1` / `1234`
