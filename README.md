# CEP SYSTEM - Controle Estatístico de Processo

Sistema moderno, robusto e completo para Controle Estatístico de Processo (CEP), Cálculo de Capacidade (\(C_p, C_{pk}, P_p, P_{pk}\)), Cartas de Controle (\(\bar{X}-R, \bar{X}-S\)), Testes de Normalidade e Emissão de Relatório Técnico de Estudo de Capacidade de Processo em conformidade com as normas industriais e automotivas (Automotive Reference Manuals / IATF 16949).

---

## 🚀 Acesso Online (GitHub Pages)
Acesse a versão web diretamente no seu navegador, sem necessidade de instalação:
👉 **[Abrir CEP System Online](https://gvinih.github.io/CEP/)**

---

## 🖥️ Versão Aplicativo Desktop (.EXE)
O sistema acompanha o executável standalone para Windows:
- **`CEP_SYSTEM.exe`**: Executável único que inicia uma janela dedicada tipo aplicativo nativo (Edge/Chromium App Mode) com servidor HTTP local embutido, salvando os dados e histórico automaticamente em formato JSON (`cep_dados.json`) de forma transparente e em tempo real.

---

## ✨ Principais Funcionalidades

- **Rastreabilidade Completa**:
  - Código e Nome da Peça
  - Máquina / Linha de Produção
  - Instrumento e Código do Instrumento
  - Operação, Característica, Responsável e Data
- **Cálculo de Capacidade & Desempenho**:
  - Limites de Especificação: LSE (USL) e LIE (LSL) separados, com cálculo automático de **Tolerância** (\(LSE - LIE\))
  - Estimativa de desvio padrão intra-subgrupo (\(\sigma_{R/d_2}\)) e global (\(S\))
  - Índices \(C_p\), \(C_{pk}\), \(P_p\), \(P_{pk}\), \(C_{pm}\)
- **Cartas de Controle**:
  - Carta das Médias (\(\bar{X}\))
  - Carta das Amplitudes (\(R\))
  - Limites de controle calculados com constantes estatísticas automotivas padrão (\(A_2, D_3, D_4\))
- **Testes de Normalidade & Distribuição**:
  - Histograma com curva normal teórica sobreposta
  - Gráfico Quantil-Quantil (Q-Q Plot)
  - Assimetria (Skewness) e Curtose (Kurtosis)
- **Relatório Técnico A4 Completo**:
  - Diagramação profissional em 3 páginas A4 para impressão ou exportação em PDF
  - Resumo de rastreabilidade, fórmulas detalhadas, cartas de controle, histograma e tabela completa de subgrupos
- **Persistência & Exportação**:
  - Salvamento automático local em `cep_dados.json`
  - Exportação e importação de estudos individuais e base completa
  - Exportação de dados brutos para Excel (.xlsx / .csv)

---

## 🛠️ Tecnologias Utilizadas
- **Frontend**: HTML5, CSS3 moderno, JavaScript (ES6+), Chart.js
- **Desktop Wrapper**: C# (.NET Framework) nativo do Windows, sem dependências externas

---

## 📄 Licença
Distribuído sob a licença MIT. Sinta-se à vontade para utilizar e contribuir!
