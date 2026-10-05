# 🧮 Calculadora de IMC

Calculadora de **Índice de Massa Corporal (IMC)** feita com HTML, CSS e JavaScript puro. O usuário informa o peso e a altura, e o app mostra o valor do IMC e a classificação correspondente.

O visual segue um tema escuro com tons neon roxo/magenta e efeitos de brilho.

## ✨ Funcionalidades

- Cálculo do IMC a partir do peso (kg) e da altura (m)
- Classificação automática de acordo com a tabela da OMS
- Resultado exibido somente após o cálculo
- Layout responsivo (a imagem passa para cima da calculadora em telas pequenas)
- Ícones com Font Awesome e ilustração da [unDraw](https://undraw.co/)

## 📐 Como o IMC é calculado

```
IMC = peso (kg) ÷ altura² (m)
```

Exemplo: 70 kg e 1,75 m → 70 ÷ (1,75 × 1,75) ≈ **22,9**

| IMC | Classificação |
|---|---|
| Abaixo de 18,5 | Abaixo do peso |
| 18,5 a 24,9 | Peso normal |
| 25 a 29,9 | Sobrepeso |
| 30 a 34,9 | Obesidade grau I |
| 35 a 39,9 | Obesidade grau II |
| 40 ou mais | Obesidade grau III |

> ⚠️ O IMC é apenas um indicador geral e não substitui a avaliação de um profissional de saúde.

## 🛠️ Tecnologias

- **HTML5**: estrutura da página e formulário
- **CSS3**: layout com Flexbox, tema escuro, efeitos de brilho e responsividade
- **JavaScript (ES6)**: leitura do formulário, cálculo e exibição do resultado
- **Font Awesome**: ícones
- **Google Fonts (Open Sans)**: tipografia

## 📁 Estrutura do projeto

```
calculadora-imc/
├── index.html
├── README.md
└── assents/
    ├── css/
    │   └── styles.css
    ├── js/
    │   └── main.js
    └── img/
        └── undraw_healthy-habit_2ata.svg
```

## 🚀 Como executar

1. Clone o repositório:
   ```bash
   git clone https://github.com/SEU-USUARIO/calculadora-imc.git
   ```
2. Entre na pasta do projeto:
   ```bash
   cd calculadora-imc
   ```
3. Abra o arquivo `index.html` no navegador (dê dois cliques nele ou use a extensão *Live Server* do VS Code).

Não precisa instalar nada: o projeto roda direto no navegador.

## 🧠 O que eu aprendi

- Selecionar elementos do HTML com `getElementById`
- Escutar eventos de formulário com `addEventListener("submit")` e usar `event.preventDefault()`
- Converter texto em número com `Number()`
- Estruturas condicionais com `if / else if / else`
- Mostrar resultados na tela com `textContent` e `toFixed()`
- Estilização com Flexbox, `:focus-within`, `:has()` e media queries

## 🔮 Melhorias futuras

- [ ] Validar valores inválidos (altura ou peso iguais a zero)
- [ ] Mudar a cor da etiqueta de classificação conforme a faixa
- [ ] Adicionar link real na seção "Para mais informações sobre IMC"
- [ ] Publicar online com GitHub Pages

## 👨‍💻 Autor

**Marcos Silari**
Estudante de Análise e Desenvolvimento de Sistemas (ADS) na Cruzeiro do Sul.

- GitHub: [@SEU-USUARIO](https://github.com/SEU-USUARIO)

## 🖼️ Créditos

- Ilustração: [unDraw](https://undraw.co/)
- Ícones: [Font Awesome](https://fontawesome.com/)
