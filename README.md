# AC2_Mobile
Prova AC2 Desenvolvimento de Apps para Mobile.
![ANDROID](https://img.shields.io/badge/android-3DDC84?style=for-the-badge&logo=android&logoColor=white)

## Crie um app que ajude o usuário a realizar circuitos de treino físico com descanso
programado. O app deve permitir que o usuário cadastre uma sequência simples
de exercícios com seus respectivos tempos, e o app deve guiá-lo com notificações
e contagem regressiva com o uso de banco de dados facultativo.

## Tela Principal: 📝
🔹 Lista dos exercícios em sequência (Ex: Agachamento – 30s, Flexão – 20s,
Descanso – 10s...).
🔹 Botão “Iniciar Treino”.
🔹 Contador na tela mostrando o tempo restante do exercício atual.
🔹 Exibição do nome do exercício atual em destaque.

## Tela de Cadastro do circuito: 📝
🔹 Nome do exercício.
🔹 Duração (em segundos).

## Execução do Treino: 📝
🔹 Ao clicar em "Iniciar Treino", o app deve executar cada exercício em
sequência, mostrando o tempo decrescente.
🔹 Quando o tempo de um exercício acabar, o próximo deve iniciar
automaticamente.
🔹 O usuário deve ser avisado por notificação com o nome do exercício atual
(mesmo com o app em segundo plano).
🔹 Ao final do treino, uma notificação deve informar "Treino concluído!
Parabéns!".
🔹 O tempo deve rodar mesmo se o app estiver em segundo plano (pode ser
com Service, Handler, CountDownTimer ou Thread com sleep).
