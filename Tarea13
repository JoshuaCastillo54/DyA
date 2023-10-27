function encontrarElementosDominantes(arreglo) {
  const dominantes = [];
  let maxDerecha = -Infinity;

  for (let i = arreglo.length - 1; i >= 0; i--) {
    if (arreglo[i] > maxDerecha) {
      dominantes.push(arreglo[i]);
      maxDerecha = arreglo[i];
    }
  }

  return dominantes;
}

// Ejemplos de uso:
const arreglo1 = [1, 21, 4, 7, 5];
const arreglo2 = [5, 4, 3, 2, 1];

console.log(encontrarElementosDominantes(arreglo1)); // Debería mostrar [21, 7, 5]
console.log(encontrarElementosDominantes(arreglo2)); // Debería mostrar [5, 4, 3, 2, 1]
