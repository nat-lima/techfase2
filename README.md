# Carteira do Dia - B3

Este é um projeto que consiste na implementacao de web scraping na página disponibilidade pela Bolsa de Valores B3 https://sistemaswebb3-listados.b3.com.br/indexPage/day/IBOV?language=pt-br.

## Link video

https://drive.google.com/file/d/1Djv6WuDLjq5WlXORIwZNzggRa4w_Fael/view?usp=sharing

## 🚀 Função

- **Web Scraping**: Extrai dados de páginas web (https://sistemaswebb3-listados.b3.com.br/indexPage/day/IBOV?language=pt-br)/ (label, table, tbody, tr, td) usando selenium e python.

## 📁 Estrutura do Projeto

```bash
techfase2/
├── data/
│   ├── ibovespa_[date].csv
│   ├── ibovespa_[date].parquet
├── README.md
├── requirements.txt
├── scrape_ibovespa.ipynb
```

- **`data/`**: O algoritmo escrito no notebook Jupyter persiste o resultado proveniente do site https://sistemaswebb3-listados.b3.com.br/indexPage/day/IBOV?language=pt-br num arquivo formato .parquet.
- **`README.md`**: Documentação do projeto.
- **`requirements.txt`**: Lista de dependências do projeto.
- **`scrape_ibovespa`**: Algoritmo responsável pelo processamento dos dados disponíveis no https://sistemaswebb3-listados.b3.com.br/indexPage/day/IBOV?language=pt-br.


## 🛠️ Como Executar o Projeto

### 1. Clone o Repositório

```bash
git clone https://github.com/nat-lima/techfase2
cd techfase1
```

### 2. Crie um Ambiente Virtual

```bash
python -m venv venv
source venv/bin/activate  # No Windows: venv\Scripts\activate
```

### 3. Instale as Dependências

```bash
pip install -r requirements.txt
```

### 4. Execute o Aplicativo

```bash
python run.py
```

### 5. Arquitetura

![image](https://github.com/user-attachments/assets/41786e0d-7c39-424d-98a8-875e34f16295)


## 🤝 Contribuindo

1. Fork este repositório.
2. Crie sua branch (`git checkout -b feature/nova-funcionalidade`).
3. Faça commit das suas alterações (`git commit -m 'Adiciona nova funcionalidade'`).
4. Faça push para sua branch (`git push origin feature/nova-funcionalidade`).
5. Abra um Pull Request.
instalar, configurar e usar o projeto. Ele também cobre contribuições, contato, licença e agradecimentos, tornando-o completo e fácil de entender para novos desenvolvedores.
