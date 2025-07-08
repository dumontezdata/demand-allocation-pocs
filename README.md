# demand-allocation-pocs

Este repositório apresenta uma prova de conceito (PoC) com diferentes abordagens para alocação e roteirização de pedidos em contextos urbanos, utilizando dados sintéticos e reais para simulação.

## 📁 Estrutura do Projeto

```
demand-allocation-pocs/
├── delivery_center_deliveries.csv
├── delivery_center_drivers.csv
├── delivery_center_orders.csv
├── olist_customers_dataset.csv
├── olist_geolocation_dataset.csv
├── olist_orders_dataset.csv
├── Mestrado - vf.ipynb
├── requirements.txt
└── README.md
```

## 📚 Descrição

O notebook `Mestrado - vf.ipynb` contém o fluxo completo do experimento:
- Geração de pedidos e alocação em hubs.
- Estratégias de adensamento por janelas (fixas e móveis).
- Comparação entre políticas de roteirização: com e sem reuso de rotas abertas.
- Avaliação dos resultados com variáveis simuladas e empíricas (distância, tempo, SLA, custo).

Os arquivos `.csv` representam datasets sintéticos e reais utilizados nas simulações.

## ⚙️ Como rodar

1. Clone o repositório:
```bash
git clone https://github.com/dumontezdata/demand-allocation-pocs.git
cd demand-allocation-pocs
```

2. Crie um ambiente virtual (opcional mas recomendado):
```bash
python -m venv venv
source venv/bin/activate  # Linux/macOS
venv\Scripts\activate     # Windows
```

3. Instale as dependências:
```bash
pip install -r requirements.txt
```

4. Execute o notebook:
Abra o `Mestrado - vf.ipynb` no Jupyter ou VS Code e siga as células para reproduzir o experimento.

## 📊 Resultados

Os resultados incluem:
- Comparações entre políticas com janelas fixas, móveis e dinâmicas.
- Avaliações com diferentes premissas de velocidade e tempo de despacho.
- Métricas como custo total, SLA, agrupamento e tempo médio de entrega.

## 🧠 Objetivo

Explorar abordagens eficientes de roteirização e adensamento urbano de entregas a partir de uma lógica baseada em simulação e otimização operacional.

## 📝 Licença

Este projeto está licenciado sob a licença MIT.
