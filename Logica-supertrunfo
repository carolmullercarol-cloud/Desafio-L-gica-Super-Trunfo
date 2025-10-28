#include <stdio.h>
#include <string.h>

int main() {
    // Cadastro das duas cartas (reaproveitado do nível anterior)
    char pais1[50], pais2[50];
    int populacao1, populacao2;
    float area1, area2, pib1, pib2;
    int pontosTuristicos1, pontosTuristicos2;

    float densidade1, densidade2;
    float pibPerCapita1, pibPerCapita2;

    printf("Cadastro da Carta 1:\n");
    printf("Nome do pais: ");
    scanf("%s", pais1);

    printf("Populacao: ");
    scanf("%d", &populacao1);

    printf("Area (km²): ");
    scanf("%f", &area1);

    printf("PIB: ");
    scanf("%f", &pib1);

    printf("Numero de pontos turisticos: ");
    scanf("%d", &pontosTuristicos1);

    printf("\nCadastro da Carta 2:\n");
    printf("Nome do pais: ");
    scanf("%s", pais2);

    printf("Populacao: ");
    scanf("%d", &populacao2);

    printf("Area (km²): ");
    scanf("%f", &area2);

    printf("PIB: ");
    scanf("%f", &pib2);

    printf("Numero de pontos turisticos: ");
    scanf("%d", &pontosTuristicos2);

    // Cálculos base
    densidade1 = populacao1 / area1;
    densidade2 = populacao2 / area2;
    pibPerCapita1 = pib1 / populacao1;
    pibPerCapita2 = pib2 / populacao2;

    // Menu interativo
    int opcao;

    printf("\n===== MENU DE COMPARACAO =====\n");
    printf("Escolha o atributo para comparar:\n");
    printf("1 - Populacao\n");
    printf("2 - Area\n");
    printf("3 - PIB\n");
    printf("4 - Pontos Turisticos\n");
    printf("5 - Densidade Demografica\n");
    printf("\nOpcao: ");
    scanf("%d", &opcao);

    printf("\nComparando %s e %s...\n\n", pais1, pais2);

    switch(opcao) {
        case 1:
            printf("Atributo: Populacao\n");
            printf("%s: %d habitantes\n", pais1, populacao1);
            printf("%s: %d habitantes\n", pais2, populacao2);

            if (populacao1 > populacao2)
                printf("Resultado: %s venceu!\n", pais1);
            else if (populacao2 > populacao1)
                printf("Resultado: %s venceu!\n", pais2);
            else
                printf("Resultado: Empate!\n");
            break;

        case 2:
            printf("Atributo: Area\n");
            printf("%s: %.2f km²\n", pais1, area1);
            printf("%s: %.2f km²\n", pais2, area2);

            if (area1 > area2)
                printf("Resultado: %s venceu!\n", pais1);
            else if (area2 > area1)
                printf("Resultado: %s venceu!\n", pais2);
            else
                printf("Resultado: Empate!\n");
            break;

        case 3:
            printf("Atributo: PIB\n");
            printf("%s: %.2f trilhoes\n", pais1, pib1);
            printf("%s: %.2f trilhoes\n", pais2, pib2);

            if (pib1 > pib2)
                printf("Resultado: %s venceu!\n", pais1);
            else if (pib2 > pib1)
                printf("Resultado: %s venceu!\n", pais2);
            else
                printf("Resultado: Empate!\n");
            break;

        case 4:
            printf("Atributo: Pontos Turisticos\n");
            printf("%s: %d\n", pais1, pontosTuristicos1);
            printf("%s: %d\n", pais2, pontosTuristicos2);

            if (pontosTuristicos1 > pontosTuristicos2)
                printf("Resultado: %s venceu!\n", pais1);
            else if (pontosTuristicos2 > pontosTuristicos1)
                printf("Resultado: %s venceu!\n", pais2);
            else
                printf("Resultado: Empate!\n");
            break;

        case 5:
            printf("Atributo: Densidade Demografica\n");
            printf("%s: %.2f hab/km²\n", pais1, densidade1);
            printf("%s: %.2f hab/km²\n", pais2, densidade2);

            if (densidade1 < densidade2)
                printf("Resultado: %s venceu! (menor densidade)\n", pais1);
            else if (densidade2 < densidade1)
                printf("Resultado: %s venceu! (menor densidade)\n", pais2);
            else
                printf("Resultado: Empate!\n");
            break;

        default:
            printf("Opcao invalida! Selecione entre 1 e 5.\n");
            break;
    }

    return 0;
}
