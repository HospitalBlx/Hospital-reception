<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Recepción del Hospital</title>
    <style>
        body { font-family: Arial, sans-serif; text-align: center; }
        .container { max-width: 500px; margin: auto; }
        .urgencia-leve { background-color: lightgreen; }
        .urgencia-moderado { background-color: yellow; }
        .urgencia-grave { background-color: red; color: white; }
        .paciente { padding: 10px; margin: 5px; border-radius: 5px; }
    </style>
</head>
<body>
    <h1>Recepción del Hospital</h1>
    <div class="container">
        <h2>Registrar Paciente</h2>
        <input type="text" id="nombre" placeholder="Nombre del paciente">
        <input type="text" id="motivo" placeholder="Motivo de consulta">
        <select id="urgencia">
            <option value="leve">Leve</option>
            <option value="moderado">Moderado</option>
            <option value="grave">Grave</option>
        </select>
        <button onclick="registrarPaciente()">Registrar</button>

        <h2>Pacientes en espera</h2>
        <div id="listaPacientes"></div>
        <button onclick="llamarPaciente()">Llamar al siguiente</button>
    </div>

    <script>
        let pacientes = [];
        
        function registrarPaciente() {
            let nombre = document.getElementById("nombre").value;
            let motivo = document.getElementById("motivo").value;
            let urgencia = document.getElementById("urgencia").value;
            
            if (nombre && motivo) {
                pacientes.push({ nombre, motivo, urgencia });
                actualizarLista();
                document.getElementById("nombre").value = "";
                document.getElementById("motivo").value = "";
            }
        }

        function actualizarLista() {
            let lista = document.getElementById("listaPacientes");
            lista.innerHTML = "";
            
            pacientes.sort((a, b) => {
                let prioridad = { "grave": 1, "moderado": 2, "leve": 3 };
                return prioridad[a.urgencia] - prioridad[b.urgencia];
            });

            pacientes.forEach((p, index) => {
                let div = document.createElement("div");
                div.classList.add("paciente", `urgencia-${p.urgencia}`);
                div.textContent = `${p.nombre} - ${p.motivo} (${p.urgencia})`;
                lista.appendChild(div);
            });
        }

        function llamarPaciente() {
            if (pacientes.length > 0) {
                alert(`Llamando a: ${pacientes[0].nombre}`);
                pacientes.shift();
                actualizarLista();
            } else {
                alert("No hay pacientes en espera");
            }
        }
    </script>
</body>
</html>

