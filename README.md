# 4-em-C-
#include <stdio.h>

int main() {
    float distancia, consumo, precoCombustivel, custo;

    printf("Digite a distância da viagem (em km): ");
    scanf("%f", &distancia);

    printf("Digite o consumo médio de combustível do carro (em km/l): ");
    scanf("%f", &consumo);

    printf("Digite o preço do combustível por litro: ");
    scanf("%f", &precoCombustivel);

    custo = (distancia / consumo) * precoCombustivel;

    printf("O custo estimado de combustível para essa viagem é: R$%.2f", custo);

    return 0;
}
