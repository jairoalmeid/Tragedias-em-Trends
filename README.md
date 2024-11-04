# Tragédias em Trends: Análise do Interesse Público em Desastres

Este script utiliza dados do [Google Trends](https://trends.google.com/) para monitorar e analisar o interesse público em tipos específicos de desastres reportados em diversos países, utilizando dados da base de dados internacional do [CRED Database](https://www.emdat.be/) (Centre for Research on the Epidemiology of Disasters).

O objetivo deste trabalho é compreender quais aspectos dos desastres geram maior interesse e repercussão global, utilizando indicadores do Google Trends como parâmetro de medição do interesse público. A análise permite identificar tendências de busca e avaliar a atenção dada a diferentes tipos de desastres, correlacionando fatores como número de pessoas atingidas, mortes, prejuízos financeiros e outros fatores com o índice de interesse e repercussão de cada desastre.

---

## :pushpin: Pré-requisitos

Para executar este projeto, você precisará dos seguintes requisitos:

- **Python 3.x**
- **Biblioteca [pytrends](https://pypi.org/project/pytrends/)** para acessar a API do Google Trends.
- **Biblioteca [psycopg2](https://pypi.org/project/psycopg2/)** para conectar ao banco de dados PostgreSQL.
- **Banco de dados PostgreSQL** (Script disponível no diretório `BancoDeDados`).

---

## :computer: Instalação

1. **Clone este repositório**:
   ```bash
   git clone https://github.com/jairoalmeid/Tragedias-em-Trends.git
   ```
2. **Navegue até o diretório do projeto**:
   ```bash
   cd Tragedias-em-Trends
   ```
3. **Instale as dependências**:
   ```bash
   pip install -r requirements.txt
   ```

---

## :bust_in_silhouette: Desenvolvedor

**Desenvolvido por Jairo Almeida**  
[GitHub: jairoalmeid](https://github.com/jairoalmeid)  

---

📅 **Última atualização:** 4 de novembro de 2024
