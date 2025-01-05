# ETL-com-Python
Extração de dados da internet

# 🔄 Projeto ELT com Python

## 📋 Descrição
Este projeto implementa um processo de ELT (Extract, Load, Transform) utilizando Python para manipulação e processamento de dados.

## 🏗️ Estrutura do Projeto
```bash
projeto_elt/
├── src/
│   ├── extract/
│   │   └── extractors.py
│   ├── load/
│   │   └── loaders.py
│   └── transform/
│       └── transformers.py
├── config/
│   └── config.yaml
├── tests/
├── requirements.txt
└── README.md
```

## 🚀 Como começar

### Pré-requisitos
- Python 3.8+
- pip (gerenciador de pacotes Python)

### Instalação
1. Clone o repositório
```bash
git clone https://github.com/seu-usuario/projeto-elt.git
cd projeto-elt
```

2. Crie um ambiente virtual
```bash
python -m venv venv
source venv/bin/activate  # Linux/Mac
# ou
venv\Scripts\activate  # Windows
```

3. Instale as dependências
```bash
pip install -r requirements.txt
```

## 📦 Principais Dependências
- pandas
- sqlalchemy
- pyyaml
- python-dotenv

## 🛠️ Configuração
1. Copie o arquivo `.env.example` para `.env`
2. Configure as variáveis de ambiente necessárias no arquivo `.env`

## 🔨 Uso
```bash
python src/main.py
```

## 📊 Fluxo de Dados
1. **Extração**: Coleta dados das fontes configuradas
2. **Load**: Carrega os dados brutos no data lake/warehouse
3. **Transform**: Realiza as transformações necessárias nos dados já carregados

## 🧪 Testes
```bash
pytest tests/
```

## 📝 Documentação
Para mais detalhes sobre cada módulo, consulte a documentação em `/docs`

## 🤝 Contribuição
1. Faça um Fork do projeto
2. Crie uma branch para sua feature (`git checkout -b feature/AmazingFeature`)
3. Commit suas mudanças (`git commit -m 'Add some AmazingFeature'`)
4. Push para a branch (`git push origin feature/AmazingFeature`)
5. Abra um Pull Request

## 📄 Licença
Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

## 👥 Autores
* **Humberto Alcântara** - *Trabalho inicial* - humbertojr85(https://github.com/humbertojr85)
