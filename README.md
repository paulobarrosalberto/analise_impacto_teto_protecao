# Análise Estrutural de Impacto — Teto de Proteção Metálico

Projeto de análise estrutural dinâmica explícita utilizando Método dos Elementos Finitos (FEM) para avaliação de impacto em estrutura metálica de proteção instalada em poço vertical.

## Objetivo

Avaliar a integridade estrutural de um teto metálico submetido ao impacto de uma massa de 55 kg em queda livre, verificando:

- tensões equivalentes de von Mises;
- deformações plásticas;
- deformações totais;
- estabilidade estrutural global;
- absorção de energia durante o impacto.

---

## Ferramentas Utilizadas

- ANSYS Explicit Dynamics
- Método dos Elementos Finitos (FEM)
- FreeCAD / CAD 3D
- Python para pós-processamento

---

## Principais Características da Simulação

- Análise dinâmica explícita
- Não linearidade geométrica
- Contato estrutural
- Grandes deformações
- Elementos de casca (shell)
- Avaliação transiente do impacto

---

## Parâmetros do Problema

| Parâmetro | Valor |
|---|---|
| Massa de impacto | 55 kg |
| Altura de queda | 10 m |
| Velocidade de impacto | 14 m/s |
| Energia potencial | 5395 J |
| Material | ASTM A36 |

---

## Resultados Obtidos

### Tensão de von Mises

- Pico máximo localizado: 554 MPa
- Região média estrutural: 80–100 MPa

### Deformação Total

- Deslocamento máximo: 107 mm

### Comportamento Global

- Estrutura estável
- Sem colapso estrutural global
- Plastificação localizada compatível com absorção de energia

---

## Imagens da Simulação

### Tensão de von Mises

![Von Mises](media/von_mises_top.png)

### Deformação Total

![Deformação](media/deformacao_total.png)

---

## Normas Utilizadas

- ABNT NBR 8800:2008
- ABNT NBR 16239:2013

---

## Autor

Paulo A. Barros  
Engenharia Física — Simulação Numérica e Análise Estrutural
