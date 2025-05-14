#include <stdio.h>

int main(){

    char estado[50], codigocarta[70], nomecidade[50];
    int populacao, pontosturisticos;
    float areaEmKm, pib;

    printf("digite o estado: \n");
    scanf("%s", &estado),

    printf("codigo carta: \n");
    scanf("%s", &codigocarta),

    printf("nome da cidade: \n");
    scanf("%s", &nomecidade),

    printf("populacao: \n");
    scanf("%d", &populacao),

    printf("area em km: \n");
    scanf("%f", &areaEmKm),

    printf("PIB: \n");
    scanf("%f", &pib),

    printf("pontos turisticos: \n");
    scanf("%d", &pontosturisticos),




    printf("estado: %s\n", estado);
    
    
    printf("codigo carta: %s\n", codigocarta);


    printf("nome cidade: %s\n", nomecidade);


    printf("populacao: %d\n", populacao);


    printf("area em km²: %.2f\n", areaEmKm);


    printf("PIB: %.2f\n", pib);


    printf("pontos turisticos: %d\n", pontosturisticos);

    return 0;
 }