# 🤖 Projeto: Engenharia de Instrução (Prompt Engineering)

## 📝 Descrição do Projeto
Este projeto foi desenvolvido como parte da disciplina de **Inteligência Artificial (2026.1)**. O objetivo principal foi dominar as técnicas de comunicação com Modelos de Linguagem de Larga Escala (LLMs), atuando como engenheiros de instrução para obter resultados de alta precisão no menor tempo e com o menor número de interações possíveis.

O desafio consistiu em duas frentes principais:
1. **Geração de Texto:** Criação de um e-mail formal (e posteriormente informal) de um pirata para um rei, com contextos específicos que evoluíram a cada iteração.
2. **Geração de Imagem:** Desenvolvimento de um prompt complexo para gerar uma imagem 4K de um astronauta barroco em Marte.

**Autor:** Ana Beatris Alves da Silva  

---

## 🚀 Tecnologias Utilizadas
* **Modelo de IA:** Gemini 3 Flash (via interface de chat)
* **Metodologias:** Engenharia de Prompt, Design de Instrução Iterativo
* **Plataforma de Registro:** GitHub (Markdown)

---

## 📊 Processo de Refinamento (Log de Iterações)

Abaixo, detalhamos o ciclo de Avaliação e Integração utilizado para atingir o "Alvo" em apenas 5 iterações.

### 📧 Desafio 1: O E-mail do Pirata

| Iteração | Prompt Enviado | Avaliação da Resposta |
| :---: | :--- | :--- |
| 1 | "gere um e-mail formal de desculpas de um pirata para um rei" | O e-mail ficou formal demais, sem nomes específicos. |
| 2 | "o pirata deve se chamar 'barba branca' e o rei deve se chamar 'arthur'" | Adicionou os nomes, mas o conteúdo ainda era genérico. |
| 3 | "o pirata está se desculpando por ter sequestrado a princesa do rei" | Contexto corrigido, tom formal mantido. |
| 4 | "deixe num sotaque pirata, mais informal" | O tom mudou para a "persona" correta, mas faltava o clímax. |
| 5 | "adicione no final que o navio está afundando e a princesa não sabe nadar" | **Resultado Final:** Equilíbrio perfeito entre humor, urgência e sotaque. |

---

### 🎨 Desafio 2: A Imagem do Astronauta

> 📷 **Figura 1:** *Representação visual do astronauta barroco tocando violoncelo em chamas.*

Para este desafio, a estratégia focou em consolidar os elements de cenário, estilo artístico e iluminação em um comando descritivo robusto.

#### Prompt Final Utilizado:
```text
Realistic 4k photography of an astronaut in ornate Baroque-style armor, sitting on a chair and playing a cello that is engulfed in flames. The scene is set on the dusty red surface of Mars under a dark night sky filled with countless stars. A futuristic spacecraft is landed nearby in the background. High detail, cinematic lighting, dramatic shadows.
