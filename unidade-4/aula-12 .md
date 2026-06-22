# Aula 12 – Internet: História, Conceitos, Protocolos e Navegadores

## Objetivo
Compreender como a Internet funciona desde sua origem até sua aplicação prática, entendendo sua evolução, arquitetura, protocolos fundamentais e o papel dos navegadores modernos.

---

## 1. História da Internet

A Internet não surgiu pronta: ela é resultado de décadas de evolução técnica e militar.

### ARPANET (1960–1970)
A ARPANET foi criada pelo Departamento de Defesa dos EUA com o objetivo de permitir comunicação descentralizada entre computadores. A ideia central era resistir a falhas em pontos específicos da rede.

### Expansão acadêmica e militar
Durante os anos 70 e 80, universidades e centros de pesquisa começaram a usar a rede. Nesse período, surgiram padrões de comunicação que permitiram a interconexão de diferentes sistemas.

### Comercialização (anos 1990)
A Internet deixou de ser restrita a instituições e passou a ser aberta ao público e empresas. Isso impulsionou a criação de provedores de acesso e sites comerciais.

### World Wide Web (WWW)
Criada por Tim Berners-Lee, a Web introduziu o conceito de páginas hipertextuais acessadas via navegador, usando HTTP e HTML como base.

---

## 2. Conceitos Fundamentais

### Internet vs Web
- **Internet**: infraestrutura global de redes conectadas.
- **Web (WWW)**: serviço que roda sobre a Internet usando páginas e links.

### Arquitetura cliente-servidor
- O **cliente** solicita informações (ex: navegador).
- O **servidor** processa e responde com dados.

Esse modelo é base de praticamente toda comunicação moderna na web.

### Endereço IP
É o identificador único de um dispositivo na rede.
Exemplo: `192.168.0.1`

Ele permite que dados saibam exatamente para onde devem ir.

---

## 3. Protocolos

### TCP/IP
É o conjunto base da Internet.
- **TCP**: garante entrega correta dos dados.
- **IP**: define o roteamento entre dispositivos.

Sem ele, não existiria comunicação confiável entre redes.

---

### HTTP / HTTPS
- **HTTP**: protocolo de transferência de hipertexto.
- **HTTPS**: versão segura com criptografia (TLS).

Exemplo: acesso a sites como Google ou YouTube.

---

### DNS
Converte nomes de domínio em endereços IP.
Exemplo:
`google.com → 142.250.x.x`

Sem DNS, precisaríamos decorar IPs.

---

### FTP
Protocolo usado para transferência de arquivos entre computadores.

Hoje é menos comum, mas ainda usado em ambientes internos.

---

## 4. Navegadores

Os navegadores são softwares responsáveis por interpretar e exibir conteúdo da web.

Eles processam:
- HTML (estrutura)
- CSS (estilo)
- JavaScript (interatividade)

### Motores de renderização
- **Blink** → usado no Chrome e Edge
- **Gecko** → usado no Firefox
- **WebKit** → usado no Safari

O motor define como a página será interpretada e exibida.

---

## 5. Exercício Prático – Análise de Protocolos

Ao analisar uma requisição em ferramentas como DevTools ou Wireshark, observe:

### 1. Request (requisição)
Exemplo:
- Método: GET
- URL: /index.html
- Headers: informações do navegador

### 2. Response (resposta)
Exemplo:
- Conteúdo HTML retornado
- Headers do servidor

### 3. Status Code
- 200 → sucesso
- 404 → não encontrado
- 500 → erro interno do servidor

Esses códigos indicam o resultado da comunicação.

---

## 6. Reflexão Individual

**Qual protocolo é mais essencial para a Internet?**

O TCP/IP é o mais fundamental, pois ele define a base da comunicação entre dispositivos. Sem ele, não haveria entrega confiável de dados nem roteamento entre redes diferentes. Todos os outros protocolos dependem dele para funcionar corretamente.

---

## Referências

- :contentReference[oaicite:0]{index=0}  
- :contentReference[oaicite:1]{index=1}  
- :contentReference[oaicite:2]{index=2}  
- :contentReference[oaicite:3]{index=3}  
- :contentReference[oaicite:4]{index=4}  
