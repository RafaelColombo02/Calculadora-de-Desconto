import java.util.Scanner;

public class CalculadoraDesconto {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        // Receber o valor do produto
        System.out.print("Digite o valor do produto: ");
        double valorProduto = scanner.nextDouble();

        // Receber a porcentagem de desconto
        System.out.print("Digite a porcentagem de desconto: ");
        double porcentagemDesconto = scanner.nextDouble();

        // Calcular o valor do desconto
        double valorDesconto = (porcentagemDesconto / 100) * valorProduto;

        // Calcular o preço final do produto após aplicar o desconto
        double precoFinal = valorProduto - valorDesconto;

        // Exibir o valor do desconto e o preço final do produto
        System.out.println("O valor do desconto é: R$" + valorDesconto);
        System.out.println("O preço final do produto após o desconto é: R$" + precoFinal);

        // Fechar o scanner
        scanner.close();
    }
}
