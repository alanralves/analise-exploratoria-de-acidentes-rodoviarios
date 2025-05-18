# Análise de Acidentes Rodoviários - PRF

## 1. Introdução

Este projeto é o resultado de uma atividade proposta na disciplina **Segurança de Dados**, do curso **Técnologo em Ciência de Dados**. Este repositório documenta a **análise exploratória de acidentes rodoviários** com base no conjunto de dados fornecido pela **Polícia Rodoviária Federal (PRF)**.  
O principal objetivo foi identificar padrões de ocorrência e gravidade dos acidentes, relacionando-os com variáveis como **condições meteorológicas**, **tipo de pista** e **horário**, além de extrair **insights** a partir das descrições textuais das causas.

A partir desses insights, foram elaboradas **recomendações práticas** para orientar campanhas de conscientização e políticas públicas de segurança viária.

As análises foram realizadas no **Google Colab**, permitindo a organização do código em blocos.  
As análises são **descritivas** e organizadas em tópicos para maior objetividade. Cada seção inclui o gráfico correspondente à análise descrita. Ao final do relatório, está disponível o código completo com seus resultados.

---

## 2. Análises

### 2.1. Frequência de Tipos de Acidente

**Análise Descritiva:**
- Colisão traseira: 11.564 registros  
- Saída de leito carroçável: 8.787 registros  
- Colisão transversal: 7.784 registros  
- Tombamento: 5.346 registros  
- Derramamento de carga: 278 registros  
- Sinistro pessoal de trânsito: 112 registros  

**Figura 1:** Gráfico de barras das frequências de tipos de acidente.
![image](https://github.com/user-attachments/assets/79328b22-84e8-41f0-8fee-c4f8dd8ccb1b)


### 2.2. Proporção de Gravidade dos Acidentes

**Análise Descritiva:**
- Feridos: 76,7%  
- Sem Vítimas: 16,2%  
- Fatais: 7,1%  

**Figura 2:** Gráfico de pizza da proporção de gravidade.
![image](https://github.com/user-attachments/assets/e4109ab1-f1ad-4c9b-a4dd-388929b74f29)


### 2.3. Gravidade vs Condição Meteorológica

**Análise Descritiva:**
- **Chuva:** 6,9% fatais, 76,5% feridos, 16,6% sem vítimas  
- **Céu Claro:** 7,8% fatais, 75,9% feridos, 16,3% sem vítimas  
- **Garoa/Chuvisco:** 5,5% fatais, 80,6% feridos, 13,9% sem vítimas  
- **Névoa/Nevoeiro:** 10,4% fatais, 73,1% feridos, 16,5% sem vítimas  

**Figura 3:** Gráfico empilhado de gravidade por condição meteorológica.
![image](https://github.com/user-attachments/assets/830ecdb8-7865-4e21-bf2c-3b10468cf61a)


### 2.4. Gravidade vs Tipo de Pista

**Análise Descritiva:**
- **Pista Simples:** 10,1% fatais, 73,0% feridos, 16,9% sem vítimas  
- **Pista Múltipla:** 4,3% fatais, 81,1% feridos, 14,6% sem vítimas  
- **Pista Dupla:** 5,0% fatais, 78,0% feridos, 17,0% sem vítimas  

**Figura 4:** Gráfico empilhado de gravidade por tipo de pista.
![image](https://github.com/user-attachments/assets/4fd21ac1-fe73-410f-81f9-67f658f49782)


### 2.5. Gravidade vs Hora do Acidente

**Análise Descritiva:**
- **1h–4h:** 12–13% fatais, 59–65% feridos, 24–28% sem vítimas  
- **7h–9h:** 4–6% fatais, 78–83% feridos, 13–16% sem vítimas  
- **17h–19h:** 5–6% fatais, 80–81% feridos, 13–15% sem vítimas  

**Figura 5:** Gráfico de linhas de gravidade por hora.
![image](https://github.com/user-attachments/assets/4d872266-78c5-499b-b165-4927f1e82036)


### 2.6. Recomendações

Com base nos resultados, as principais recomendações incluem:

- **Intensificar fiscalização** nos horários de maior letalidade (1h–4h) e em condições de **neblina**  
- **Implementar divisores centrais** em pistas simples para reduzir colisões frontais  
- **Campanhas educativas** sobre excesso de velocidade e consumo de álcool  
- **Sinalização dinâmica** e **limites de velocidade adaptativos** em dias de chuva

---

### 2.7. Considerações sobre Segurança de Dados

Para garantir a segurança e privacidade dos dados utilizados, recomenda-se:

- **Anonimização** das coordenadas geográficas por agregação em malhas  
- Uso de **criptografia em repouso e em trânsito**  
- **Controles de acesso** baseados em perfis, com **registros de auditoria**

---

## 3. Conclusão

A análise dos dados de acidentes rodoviários permitiu identificar **padrões relevantes** para a formulação de ações preventivas. Constatou-se que determinados tipos de acidente e fatores como **horário**, **clima** e **tipo de pista** influenciam significativamente na **gravidade** das ocorrências.

As **vias de pista simples** apresentam maior proporção de acidentes com vítimas, reforçando a necessidade de **melhorias estruturais**.  
Esses dados são valiosos para orientar **ações educativas**, **reforçar a fiscalização** em horários críticos e aprimorar a **infraestrutura viária**.

Além disso, destaca-se a importância da **proteção dos dados** utilizados em análises, garantindo privacidade e conformidade com boas práticas de segurança da informação.
