# Calculadora de Rendimento CDI

## Descrição

Este projeto é uma calculadora de rendimento CDI (Certificado de Depósito Interbancário) que permite ao usuário calcular o rendimento bruto e líquido de um investimento baseado na taxa CDI anual, valor investido mensalmente, tempo de investimento e alíquota do Imposto de Renda.

## Funcionalidades

- Cálculo do rendimento total bruto após um determinado período.
- Cálculo do rendimento total líquido após a aplicação do Imposto de Renda.
- Cálculo do saldo total acumulado após o período de investimento.

## Estrutura do Projeto

O projeto é organizado em três classes principais:

- **Investimento**: Representa os parâmetros do investimento.
- **CalculadoraCDI**: Contém métodos para calcular o rendimento bruto, líquido e o saldo total.
- **Main**: Gerencia a interação com o usuário e exibe os resultados.

## Como Usar

### Pré-requisitos

- JDK 11 ou superior instalado em seu computador.

### Passos para Executar

1. **Clone o repositório**:
   ```bash
   git clone https://github.com/seuusuario/CalculadoraCDI.git
   cd CalculadoraCDI
   
import org.jfree.chart.ChartFactory;
import org.jfree.chart.ChartPanel;
import org.jfree.chart.JFreeChart;
import org.jfree.data.category.CategoryDataset;
import org.jfree.data.category.DefaultCategoryDataset;

public class GraficoRendimento {
    public static void main(String[] args) {
        DefaultCategoryDataset dataset = new DefaultCategoryDataset();
        dataset.addValue(1000, "Rendimento Bruto", "Mês 1");
        dataset.addValue(1200, "Rendimento Bruto", "Mês 2");
        dataset.addValue(1400, "Rendimento Bruto", "Mês 3");
        dataset.addValue(1600, "Rendimento Bruto", "Mês 4");

        JFreeChart chart = ChartFactory.createBarChart(
                "Rendimento Bruto ao Longo do Tempo",
                "Meses",
                "Rendimento (R$)",
                dataset
        );

        ChartPanel chartPanel = new ChartPanel(chart);
        
    }
}
   
