// Obtener el contador actual de visitas desde el almacenamiento local
let visitCount = localStorage.getItem('visitCount');

// Si no existe el contador, inicializarlo en 0
if (!visitCount) {
    visitCount = 0;
}

// Incrementar el contador
visitCount++;

// Guardar el nuevo valor en localStorage
localStorage.setItem('visitCount', visitCount);

// Mostrar el contador en el elemento con id "visit-badge"
document.getElementById('visit-badge').innerText = visitCount;
