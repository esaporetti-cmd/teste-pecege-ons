# Projeto Integrador – Curva do pato na carga líquida do SIN (2023–2025)

**Curso:** Treinamento em análise de dados – Analytics · **Turma:** Outubro de 2026
**Participante:** Eduardo Lutterbach Saporetti Azevedo · **Entrega:** 24/11/2026

## Pergunta
A expansão da geração solar está criando um "pato" na curva de carga líquida (carga − eólica − solar) do SIN, aprofundando o vale do meio-dia e aumentando a rampa do fim de tarde?

## Estrutura
```
projeto/
├── projeto_curva_do_pato.ipynb   # notebook principal (executar do início ao fim)
├── requirements.txt
├── README.md
├── dados/                        # colocar aqui os 3 CSVs do ONS
│   ├── BALANCO_ENERGIA_SUBSISTEMA_2023.csv
│   ├── BALANCO_ENERGIA_SUBSISTEMA_2024.csv
│   └── BALANCO_ENERGIA_SUBSISTEMA_2025.csv
└── figuras/                      # criada automaticamente pelo notebook
```

## Ambiente
- VS Code conectado ao workspace Coder `curso-pecege/dev`
- Python 3.14.4 em ambiente virtual `.venv`

## Como executar
```bash
source /home/devkit/.venv/bin/activate
pip install -r requirements.txt
```
Abrir `projeto_curva_do_pato.ipynb` no VS Code, selecionar o kernel do `.venv` e usar **Run All**.

## Fonte dos dados
ONS – Dados Abertos: Balanço de Energia nos Subsistemas (dados horários, MWmed), 2023 a 2025.
