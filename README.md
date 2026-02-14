# Sistema de Orçamentos Imobiliária R.M — Solução Digital Premium

[cite_start]Este projeto foi desenvolvido como parte integrante do desafio da disciplina **Algorithmic Thinking & Introduction to Object-Oriented Programming** no Centro Universitário UniFECAF [cite: 3-4, 11]. [cite_start]O sistema automatiza a gestão e negociação de locações residenciais para a empresa R.M, transformando regras de negócio em um cronograma financeiro detalhado e profissional[cite: 7, 12].

## 🚀 Funcionalidades Principais

A aplicação processa orçamentos personalizados baseados em parâmetros dinâmicos de locação:
* [cite_start]**Apartamentos**: Valor base de R$ 700,00, com acréscimo de R$ 200,00 por quarto extra e desconto estratégico de 5% para locatários sem crianças[cite: 17, 24, 28].
* [cite_start]**Casas**: Valor base de R$ 900,00, com acréscimo de R$ 250,00 por dormitório adicional[cite: 18, 25].
* [cite_start]**Estúdios**: Valor base de R$ 1.200,00, incluindo uma lógica progressiva para vagas de estacionamento (pacote inicial de R$ 250,00 para 2 vagas + R$ 60,00 por vaga excedente)[cite: 19, 27].

### Diferenciais de Realismo Financeiro
Para simular a realidade do mercado imobiliário e contábil, o sistema integra:
* [cite_start]**Taxa de Contrato**: Valor fixo de R$ 2.000,00 com parcelamento validado em até 5 vezes[cite: 20, 29].
* **Encargos Adicionais**: Provisão automática de **IPTU**, **Seguro Incêndio** e taxa de **Condomínio** (específica para apartamentos).
* [cite_start]**Exportação Premium**: Geração de planilha Excel em fonte **Arial 12**, com bordas profissionais e fórmulas de soma automática para o total acumulado de 12 meses[cite: 30].

---

## 🛠️ Tecnologias e Conceitos de POO

[cite_start]O projeto foi estruturado utilizando princípios avançados de Engenharia de Software para atender à rubrica de avaliação [cite: 76-77]:

1. **Abstração (ABC)**: Implementação da classe base `Imovel` como uma classe abstrata, definindo o contrato obrigatório para as subclasses.
2. **Herança e Polimorfismo**: Especialização dos tipos de imóveis, onde cada um sobrescreve o método de cálculo para aplicar suas regras específicas.
3. **Encapsulamento**: Uso de atributos protegidos e validação de regras de negócio (como o limite de parcelas do contrato).
4. **Tratamento de Exceções**: Robustez contra erros de entrada de dados via blocos `try-except`.

---

## 📦 Como Executar o Projeto

1.  Clone este repositório ou abra o arquivo `.ipynb` no **Google Colab**.
2.  Certifique-se de instalar a biblioteca necessária para a formatação do Excel:
    ```bash
    !pip install xlsxwriter
    ```
3.  Execute o script e interaja com o menu no terminal para inserir os dados do imóvel.
4.  O arquivo `orcamento_final_Leidiane.xlsx` será gerado automaticamente na raiz do diretório.

---

## 👤 Identificação do Estudante

* **Nome**: Leidiane Maria da Conceição Santos Castro
* **RA**: 3000000166281
* **Instituição**: UniFECAF
* **Curso**: Tecnologia em Gestão de TI
* [cite_start]**Vídeo Pitch**: [Insira o link do seu vídeo aqui] [cite: 65, 68]
