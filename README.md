trade-license-calculator/
├── README.md
├── .gitignore
├── requirements.txt
├── data/
│   └── dncc_fees_2026.csv      # the rates, with source + date
├── src/
│   ├── calculator.py           # pure logic, no UI
│   └── rules.py                # loads the fee data
├── tests/
│   └── test_calculator.py
└── app.py                      # Streamlit interface
