
# 🧮 Calculadora de IMC - Android

Um aplicativo Android simples para calcular o **Índice de Massa Corporal (IMC)** com base no peso e altura do usuário.

## 📱 Funcionalidades

- Entrada de peso (kg)
- Entrada de altura (cm ou metros)
- Cálculo automático do IMC
- Classificação do resultado com base na tabela da OMS (Abaixo do peso, Normal, Sobrepeso, Obesidade)

## 🖼️ Screenshots
<!-- Adicione aqui imagens da tela do app -->
![Exemplo 1](screenshots/exemplo1.png)
![Exemplo 2](screenshots/exemplo2.png)

## 🚀 Como usar

1. Clone o repositório:
   ```bash
   git clone https://github.com/leninenunes/calculadora-imc.git
   ```

2. Abra o projeto no **Android Studio**

3. Execute o app em um emulador ou dispositivo físico

## 🧮 Fórmula usada

```text
IMC = peso / (altura * altura)
```

- Altura deve estar em **metros**
- Exemplo: 1.75m e 70kg ⇒ IMC = 70 / (1.75 * 1.75) ≈ 22.86

## 📊 Classificação do IMC (OMS)

| IMC             | Classificação         |
|-----------------|-----------------------|
| Menor que 18.5  | Abaixo do peso        |
| 18.5 a 24.9     | Peso normal           |
| 25 a 29.9       | Sobrepeso             |
| 30 a 34.9       | Obesidade grau I      |
| 35 a 39.9       | Obesidade grau II     |
| 40 ou mais      | Obesidade grau III    |

## 🛠️ Tecnologias usadas

- [Android Studio](https://developer.android.com/studio)
- [Java](https://www.java.com/)
- XML para layout

## 📄 Licença

Este projeto está licenciado sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

## 🙋‍♂️ Autor

- [Lenine Nunes](https://github.com/leninenunes)