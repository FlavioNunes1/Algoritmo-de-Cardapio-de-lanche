#include <stdio.h> //é uma etapa fundamental na criação de programas em C

int main() { // Declaração das variáveis
    int codigo, quantidade;
    float preco, valorTotal = 0;

    // Menu de preços (poderia ser armazenado em um array para maior flexibilidade)
    printf("Cardápio:\n");
    printf("100 - Cachorro quente - R$ 1.70\n");
    printf("101 - Bauru Simples - R$ 2.30\n");
    printf("102 - Bauru com ovo - R$ 2.60\n");
    printf("103 - Hamburguer - R$ 2.40\n");
    printf("104 - Cheeseburger - R$ 2.50\n");
    printf("105 - Refrigerante - R$ 1.00\n");

    // Solicita o código do produto e a quantidade
    printf("\nDigite o código do produto: ");
    scanf("%d", &codigo);
    printf("Digite a quantidade: ");
    scanf("%d", &quantidade);

    // Calcula o preço unitário com base no código
    switch (codigo) {
        case 100:
            preco = 1.70;
            break;
        case 101:
            preco = 2.30;
            break;
        case 102:
            preco = 2.60;
            break;
        case 103:
            preco = 2.40;
            break;
        case 104:
            preco = 2.50;
            break;
        case 105:
            preco = 1.00;
            break;
        default:
            printf("Código inválido.\n");
            return 1; // Encerra o programa com erro
    }

    // Calcula o valor total
    valorTotal = preco * quantidade;

    // Exibe o valor total
    printf("O valor total a pagar é: R$ %.2f\n", valorTotal);

    return 0;
}
