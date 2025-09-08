#include <stdio.h>

  // Desafio Super Trunfo - Países
  // Tema 1 - Cadastro das Cartas
  // Este código inicial serve como base para o desenvolvimento do sistema de cadastro de cartas de cidades.
// Siga os comentários para implementar cada parte do desafio.
//Teste Marco

int main() {

    // Variaveis para registro das duas cartas.

    char Codigo[10], nomecidade[50], Estado[5], Codigo1[10], nomecidade1[50], Estado1[5];
    int Populacao, Pturisticos, Populacao1, Pturisticos1;
    float area, PIB, area1, PIB1;


    // Entrada dos dados da carta 1.

    printf ("Adicionando Cartas ao Super Trunfo: Carta 1\n");
    printf ("\nInsira a letra do Estado: ");
    scanf ("%s", Estado);
    printf ("\nInsira o código do estado: ");
    scanf ("%s", Codigo);
    printf ("\nInsira o nome da capital: ");
    scanf ("%s", nomecidade);
    printf ("\nInsira a população: ");
    scanf ("%i", &Populacao);
    printf ("\nInsira a área total (km²): ");
    scanf ("%f", &area);
    printf ("\nInsira o PIB do Estado: ");
    scanf ("%f", &PIB);
    printf ("\nInsira a quantidade de pontos turisticos: ");
    scanf ("%i", &Pturisticos);

      // Entrada dos dados da carta 2.

    printf ("\nAdicionando Cartas ao Super Trunfo: Carta 2\n");
    printf ("\nInsira a letra do Estado: ");
    scanf ("%s", Estado1);
    printf ("\nInsira o código do estado: ");
    scanf ("%s", Codigo1);
    printf ("\nInsira o nome da capital: ");
    scanf ("%s", nomecidade1);
    printf ("\nInsira a população: ");
    scanf ("%i", &Populacao1);
    printf ("\nInsira a área total (km²): ");
    scanf ("%f", &area1);
    printf ("\nInsira o PIB do Estado: ");
    scanf ("%f", &PIB1);
    printf ("\nInsira a quantidade de pontos turisticos: ");
    scanf ("%i", &Pturisticos1);

    // Saida de dados da carta 1.
    printf ("\nCarta 1\n");
    printf("Estado: %s\n", Estado);
    printf("Código do estado: %s\n", Codigo);
    printf("Nome da cidade: %s\n", nomecidade);
    printf("População: %i\n", Populacao); 
    printf("Área: %.2f\n", area);
    printf("PIB: %.2f\n", PIB);
    printf("Número de pontos turísticos: %i\n", Pturisticos);

    // Saida de dados da carta 1.
    printf ("\nCarta 2\n");
    printf("Estado: %s\n", Estado1);
    printf("Código do estado: %s\n", Codigo1);
    printf("Nome da cidade: %s\n", nomecidade1);
    printf("População: %i\n", Populacao1); 
    printf("Área: %.2f\n", area1);
    printf("PIB: %.2f\n", PIB1);
    printf("Número de pontos turísticos: %i\n", Pturisticos1);
  
return 0;
}
    
    // Sugestão: Defina variáveis separadas para cada atributo da cidade.
    // Exemplos de atributos: código da cidade, nome, população, área, PIB, número de pontos turísticos.
    
    // Cadastro das Cartas:
    // Sugestão: Utilize a função scanf para capturar as entradas do usuário para cada atributo.
    // Solicite ao usuário que insira as informações de cada cidade, como o código, nome, população, área, etc.
    
    // Exibição dos Dados das Cartas:
    // Sugestão: Utilize a função printf para exibir as informações das cartas cadastradas de forma clara e organizada.
    // Exiba os valores inseridos para cada atributo da cidade, um por linha.

