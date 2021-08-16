# tcc-mimiciii-sepse
## Trabalho de conclusão de curso da Especialização em Microbiologia Clínica da UFRGS.

O objetivo do trabalho foi avaliar dados clínicos epidemiológicos em relação à doença sepse usando dados de um banco de dados público 
PostgreSQL - Medical Information Mart for Intensive Care III (MIMIC-III), que inclui dados de saúde de pacientes não identificados, internados na UTI,  registrados de 2002 a 2014.

O MIMIC é disponibilizado amplamente através do trabalho de pesquisadores do Laboratório de Fisiologia Computacional do Instituto de Tecnologia de Massachusetts (MIT) e de 
grupos de pesquisa colaboradores. 
Para ter acesso aos dados foi necessário concluir o curso de treinamento online do National Institutes of Health "Data or Specimens Only Research” (Número do certificado: 34468843).

## Extração de dados 

Os dados foram extraídos utilizando uma query no banco de dados incluindo: idade, sexo, exames culturais constando nome do microrganismo e perfil de suscetibilidade. 
Foram utilizadas para esta busca as seguintes tabelas: ADMISSIONS, PACIENTS, DIAGNOSIS_ICD, LABEVENTS e MICROBIOLOGYEVENTS. A relação das tabelas utilizadas para a extração 
estão demonstrados em um ![Diagrama Entidade-Relacionamento](https://drive.google.com/file/d/1UIqWT7GCGXALFItpKYbzJANEzmONNKmM/view)

## Análise dos dados

Realizou-se uma análise exploratória de pacientes com sepse do banco de dados MIMIC-III utilizando a ferramenta Jupyter Notebook com código em Python.
