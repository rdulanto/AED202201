#include<iostream>

using namespace std;

int main() {

   int num, aux;
   int comparaciones = 0;
   int intercambios = 0;
   int* arreglo;
   cout << "Cuantos numeros seran: ";
   cin >> num;
   arreglo = new int[num];
   cout << endl << "***CAPTURA DE NUMEROS***" << endl;

   for(int x = 0; x < num; x++) {
      cout << "Ingresa el numero " << x << " de la serie: ";
      cin >> arreglo[x];
      cout << endl;
   }
   cout << "***MUESTRA DE NUMEROS***" << endl;

   for(int y = 0; y < num; y++) {
      cout << "Numero " << y << ".- " << arreglo[y] << endl;
   }

   for(int z = 1; z < num; ++z) {
      for(int v = 0; v < (num - z); v++) {
         comparaciones++;
         if(arreglo[v] > arreglo[v+1]){
            aux = arreglo[v];
            arreglo[v] = arreglo[v + 1];
            arreglo[v + 1] = aux;
            intercambios++;
         }
      }
    }

   cout << "***NUMEROS ARREGLADOS***" << endl;

   for(int w = 0; w < num; w++) {
      cout << "Numero " << w << ".- " << arreglo[w] << endl;
   }

   cout << "Numero de comparaciones: " << comparaciones << endl;
   cout << "Numero de intercambios: " << intercambios << endl;
  
   delete[] arreglo;
   return 0;
}
