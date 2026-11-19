# Ferramentas Interativas de Física

**Laboratórios virtuais para explorar fenômenos físicos por meio de visualizações e parâmetros ajustáveis.**

Este projeto reúne ferramentas didáticas interativas voltadas ao ensino e à aprendizagem de física, com ênfase em eletricidade e eletromagnetismo e extensão para a transferência de calor. O objetivo é complementar a teoria com experimentos virtuais, permitindo observar como diferentes configurações físicas influenciam os campos e as grandezas envolvidas.

As aplicações utilizam **HTML, CSS e JavaScript** e foram concebidas para execução diretamente no navegador, sem necessidade de instalar softwares especializados.

## Ferramentas disponíveis

### Eletromagnetismo

#### 1. Laboratório Interativo de Eletrostática

**Arquivo:** [`laboratorio_interativo_eletrostatica.html`](./laboratorio_interativo_eletrostatica.html)

Permite investigar distribuições de cargas elétricas e suas interações por meio de representações bidimensionais.

**Funcionalidades:**
- Adicionar, remover e movimentar cargas positivas e negativas.
- Explorar dipolos, arranjos circulares de cargas e placas com cargas opostas.
- Visualizar vetores e linhas de campo elétrico.
- Examinar o potencial elétrico por meio de um mapa de cores.
- Exibir vetores de força elétrica entre pares de cargas.

#### 2. Laboratório de Migração de Cargas e Blindagem (Condutores)

**Arquivo:** [`laboratorio_interativo_condutores.html`](./laboratorio_interativo_condutores.html)

Explora a indução eletrostática em condutores e o efeito de blindagem, incluindo a gaiola de Faraday.

#### 3. Laboratório de Polarização em Isolantes

**Arquivo:** [`laboratorio_interativo_isolantes.html`](./laboratorio_interativo_isolantes.html)

Explora materiais dielétricos, cargas ligadas e o campo elétrico em isolantes.

#### 4. Laboratório de Campos Elétricos em Capacitores

**Arquivo:** [`laboratorio_interativo_capacitores.html`](./laboratorio_interativo_capacitores.html)

Permite comparar geometrias de capacitores e investigar a influência do dielétrico e das condições de operação sobre suas propriedades eletrostáticas.

**Funcionalidades:**
- Examinar capacitores de placas paralelas e de cilindros coaxiais.
- Visualizar linhas de campo, vetores do campo elétrico e representações esquemáticas da polarização.
- Alterar dimensões geométricas e permissividade relativa do dielétrico.
- Comparar condições de tensão fixa e carga fixa.
- Acompanhar grandezas como capacitância, tensão, carga, campo elétrico e energia armazenada.

#### 5. Laboratório Interativo de Circuitos

**Arquivo:** [`laboratorio_interativo_circuitos.html`](./laboratorio_interativo_circuitos.html)

Simulador visual de circuitos RC, RLC e filtros passivos, com fontes CC e CA, para construir, conectar e analisar circuitos no próprio navegador.

### Termodinâmica

#### 6. Laboratório Interativo de Transferência de Calor

**Arquivo:** [`laboratorio_interativo_transferencia_calor.html`](./laboratorio_interativo_transferencia_calor.html)

Compara os três mecanismos de transferência de calor: condução, convecção e irradiação.

**Funcionalidades:**
- Estimar a condução pela lei de Fourier em uma barra plana.
- Observar a circulação do fluido na convecção, com a superfície quente ou fria.
- Ajustar temperaturas e emissividade na troca de energia por irradiação.
- Visualizar animações cuja intensidade acompanha o fluxo de calor calculado.

## Como utilizar

Você pode abrir as ferramentas em um navegador atualizado (Chrome, Firefox ou Edge). Para uso local, baixe o arquivo `.html` desejado e abra-o no navegador.

Se o repositório estiver hospedado por meio do **GitHub Pages**, as mesmas aplicações poderão ser utilizadas online, sem download. O endereço do site, quando disponível, estará indicado na descrição do repositório.

## Finalidade e limites dos modelos

As aplicações destinam-se à **exploração conceitual e ao uso educacional**. Algumas representações utilizam modelos físicos ideais, aproximações geométricas, escalas adaptadas ou visualizações esquemáticas para facilitar a interpretação.

Em especial, os modelos de capacitores não substituem simulações tridimensionais de alta fidelidade. Para aplicações de engenharia, é necessário avaliar as hipóteses, unidades, condições de contorno e limites de validade de cada modelo.

## Desenvolvimento

O projeto poderá ser ampliado com outras ferramentas de física, em eletromagnetismo, termodinâmica ou outras áreas, mantendo o mesmo formato: um arquivo HTML autocontido por ferramenta, listado no `index.html` na seção do tema correspondente.

## Contribuições

Sugestões de melhorias, relatos de problemas e propostas de novas ferramentas são bem-vindos. Utilize as **Issues** para discussões e as **Pull Requests** para contribuições com o código.

Ao contribuir, procure manter a clareza didática e explicitar as hipóteses físicas empregadas.

## Licença

Este projeto é distribuído sob a **Licença MIT**. Consulte o arquivo [`LICENSE`](./LICENSE) para conhecer os termos.

**Desenvolvimento e curadoria:** Alvaro Busquet de Sant’Anna Junior.
