<script>
    const form = document.getElementById('telemetry-form');
    const list = document.getElementById('telemetry-list');

    // Carregar dados salvos ao abrir a página
    function loadTelemetry() {
        const data = JSON.parse(localStorage.getItem('telemetry')) || [];
        list.innerHTML = '';

        data.forEach(item => {
            const li = document.createElement('li');
            li.textContent = item;
            list.appendChild(li);
        });
    }

    // Salvar no LocalStorage
    function saveTelemetry(entry) {
        const data = JSON.parse(localStorage.getItem('telemetry')) || [];
        data.push(entry);
        localStorage.setItem('telemetry', JSON.stringify(data));
    }

    form.addEventListener('submit', function(e) {
        e.preventDefault();

        const deviceId = document.getElementById('device-id').value;
        const temperature = document.getElementById('temperature').value;
        const humidity = document.getElementById('humidity').value;

        const timestamp = new Date().toLocaleString();

        const entry = `[${timestamp}] Dispositivo: ${deviceId} | Temperatura: ${temperature}°C | Umidade: ${humidity}%`;

        // Adiciona na tela
        const listItem = document.createElement('li');
        listItem.textContent = entry;
        list.appendChild(listItem);

        // Salva
        saveTelemetry(entry);

        form.reset();
    });

    // Carrega ao iniciar
    loadTelemetry();
</script>
