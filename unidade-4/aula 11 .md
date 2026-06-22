# Aula 11 – Redes de Computadores: Topologias, Dispositivos e Meios

**Nome do estudante:** João Pedro Duarte  
**Matrícula:** 22607911

---

# Objetivo

Esta atividade tem como objetivo compreender as principais topologias de redes de computadores, identificar as funções dos dispositivos de rede e reconhecer os diferentes meios de transmissão utilizados para permitir a comunicação entre dispositivos.

---

# Descrição do Trabalho

Neste trabalho são apresentados diagramas das principais topologias de rede, um quadro comparativo entre Hub, Switch e Roteador, além da classificação dos meios de transmissão guiados e não guiados.

Os materiais foram elaborados com base nos conteúdos estudados em sala de aula e na bibliografia da disciplina.

---

# Conteúdo da Atividade

## 1. Diagramas de Topologias

Foram representadas as principais topologias utilizadas em redes de computadores.

### Estrela (Star)

Todos os dispositivos estão conectados a um equipamento central, normalmente um **Switch**.

**Vantagens**
- Fácil manutenção.
- Maior confiabilidade.
- Falha de um cabo não interrompe toda a rede.

**Aplicação**
- Redes domésticas.
- Empresas.
- Laboratórios de informática.

---

### Barramento (Bus)

Todos os computadores compartilham um único cabo principal.

**Vantagens**
- Baixo custo.
- Instalação simples.

**Limitações**
- Baixa escalabilidade.
- Uma falha no cabo principal compromete toda a rede.

---

### Anel (Ring)

Os dispositivos são conectados formando um círculo, onde os dados percorrem o anel.

**Vantagens**
- Organização da comunicação.
- Pouca colisão de dados.

**Limitações**
- Falhas podem interromper toda a rede.

---

### Malha (Mesh)

Cada dispositivo pode estar conectado diretamente a vários outros dispositivos.

**Vantagens**
- Alta disponibilidade.
- Grande tolerância a falhas.

**Limitações**
- Alto custo.
- Instalação mais complexa.

Arquivo:

- 📄 [Topologias de Rede](./topologia.pdf)

---

# 2. Quadro Comparativo dos Dispositivos

| Dispositivo | Função | Vantagens | Limitações | Exemplo |
|-------------|---------|-----------|------------|----------|
| **Hub** | Repassa os dados para todos os dispositivos | Simples e barato | Gera muitas colisões | Redes antigas |
| **Switch** | Envia os dados apenas ao destinatário correto | Maior desempenho e segurança | Custo maior que o Hub | Redes domésticas e empresariais |
| **Roteador** | Interliga redes diferentes e fornece acesso à Internet | Permite comunicação entre redes | Configuração mais complexa | Modem/roteador residencial |

Arquivo:

- 📄 [Dispositivos de Rede](./dispositivos.pdf)

---

# 3. Meios de Transmissão

Os meios de transmissão são responsáveis por transportar os dados entre os dispositivos da rede.

## Meios Guiados (com fio)

- Par trançado (UTP)
- Cabo coaxial
- Fibra óptica

### Características

- Maior estabilidade.
- Menor interferência (principalmente na fibra óptica).
- Altas velocidades de transmissão.

---

## Meios Não Guiados (sem fio)

- Wi-Fi
- Bluetooth
- Satélite
- Infravermelho

### Características

- Mobilidade.
- Facilidade de instalação.
- Maior suscetibilidade a interferências.

Arquivo:

- 📄 [Meios de Transmissão](./meios_transmissao.pdf)

---

# Organização dos Arquivos

```
Aula11/

├── README.md
├── topologia.pdf
├── dispositivos.pdf
└── meios_transmissao.pdf
```

---

# Reflexão Individual

## Qual topologia seria mais adequada para a rede da sua residência e por quê?

A topologia em estrela é a mais indicada para uma rede residencial. Nesse modelo, todos os dispositivos são conectados a um equipamento central, geralmente um roteador ou switch, facilitando a administração da rede e tornando a manutenção mais simples.

Outra vantagem importante é que, caso um cabo ou dispositivo apresente defeito, os demais equipamentos continuam funcionando normalmente. Além disso, essa topologia oferece melhor desempenho, maior organização e é a arquitetura utilizada pela maioria das redes domésticas atuais, permitindo conectar computadores, celulares, televisores, videogames e dispositivos inteligentes de forma eficiente.

Por esses motivos, a topologia em estrela é considerada a melhor escolha para uma residência.

---

# Conclusão

O estudo das topologias, dispositivos e meios de transmissão permite compreender como as redes de computadores são organizadas e como ocorre a comunicação entre diferentes equipamentos.

Além disso, conhecer as características de cada topologia, as funções dos dispositivos de rede e os diferentes meios de transmissão é fundamental para projetar redes eficientes, seguras e adequadas às necessidades de cada ambiente.

---

# Referências

TANENBAUM, Andrew S.; FEAMSTER, Nick; WETHERALL, David J. **Redes de Computadores**. 6. ed. São Paulo: Bookman, 2021.

Material da disciplina de Introdução à Computação.
