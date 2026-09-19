# 🥋 Sistema de Cadastramento de Alunos - Artes Marciais

Sistema em Python desenvolvido via terminal (CLI) para gerenciamento de matriculas em academias de artes marciais. O programa realiza o cadastro de dados pessoais, validação de regras de idade e responsáveis, seleção de modalidades/graduações, venda opcional de equipamentos e processamento de pagamento.

---

## 📌 Funcionalidades

- **Coleta e Validação de Dados:**
  - Cálculo exato da idade a partir da data de nascimento.
  - Tratamento diferenciado para menores de idade (cadastro de até 2 responsáveis e grau de parentesco).
  - Validação de dados (Telefone com 11 dígitos, CEP com 8 dígitos).

- **Gestão de Modalidades e Graduações:**
  - Suporte a 3 modalidades: **Jiu-Jitsu**, **Luta Livre Esportiva** e **Muay-Thai**.
  - Exibição de faixas/tarjas específicas ajustadas pela faixa etária (Infantil até 15 anos / Adulto a partir de 16 anos).

- **Venda de Equipamentos:**
  - Sugestão e cálculo de trajes/equipamentos para alunos iniciantes (faixa/tarja branca).
  - Seleção de tamanhos e cores para itens como Kimono, Faixa, Resguarde, Short e Tarja.

- **Processamento de Pagamento:**
  - Suporte a **PIX** e **Cartão** (Débito/Crédito).
  - Validação de dados do cartão (16 dígitos e CVV de 3 dígitos).
  - Opção de parcelamento no crédito (em até 3x).

---

## 🚀 Pré-requisitos

Para executar o projeto, você precisará ter o **Python 3.x** instalado em sua máquina e a biblioteca externa `emoji`.

### Instalação das dependências

Instale a biblioteca `emoji` executando o comando no terminal:

```bash
pip install emoji
