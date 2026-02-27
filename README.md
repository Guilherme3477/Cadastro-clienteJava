Cadastro de:

Nome

Idade (via JSlider)

CPF

Cidade

Bairro

Estado

Gênero (Masculino, Feminino ou Outro)

Exibição dos dados em uma caixa de diálogo (JOptionPane)

Interface gráfica construída com JFrame

Utilização do tema Nimbus (quando disponível)

🖥️ Demonstração

A aplicação possui:

Campos de texto (JTextField)

Botões de seleção de gênero (JRadioButton)

Controle deslizante de idade (JSlider, 0 a 100 anos)

Botão Salvar

Botão Fechar (X)

Ao clicar em Salvar, os dados inseridos são exibidos em uma janela de mensagem.

🛠️ Tecnologias Utilizadas

Java (JDK 8+)

Java Swing

JFrame

JOptionPane

📂 Estrutura do Projeto
cadastro/
 └── telacadastro.java

Classe principal:

public class telacadastro extends javax.swing.JFrame
▶️ Como Executar
🔹 Via IDE (Recomendado)

Abra o projeto no NetBeans, Eclipse ou IntelliJ.

Execute a classe telacadastro.

A janela do sistema será exibida.

🔹 Via Terminal

Compile:

javac cadastro/telacadastro.java

Execute:

java cadastro.telacadastro
📌 Funcionamento

O usuário preenche os campos do formulário.

Seleciona o gênero.

Define a idade utilizando o slider.

Clica em Salvar.

O sistema exibe todas as informações em um JOptionPane.
