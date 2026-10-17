
<!DOCTYPE html>
<html lang="pt-br">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Salão de Beleza - Agendamento</title>
</head>

<body>

    <div align="center">

        <p>
            <a href="javascript:history.back()">← Voltar à página anterior</a>
        </p>

        <h1>Salão de Beleza</h1>

        <p>Agende seu horário de forma simples e rápida.</p>

        <h2>Agendamento</h2>

        <form>

            <label for="nome">Nome completo:</label>
            <br>
            <input type="text" id="nome" name="nome"
                placeholder="Digite seu nome" required>

            <br><br>

            <label for="telefone">Telefone:</label>
            <br>
            <input type="tel" id="telefone" name="telefone"
                placeholder="Digite seu telefone" required>

            <br><br>

            <label for="servico">Serviço:</label>
            <br>
            <select id="servico" name="servico" required>
                <option value="">Selecione um serviço</option>
                <option value="cabeleireiro">Cabeleireiro</option>
                <option value="manicure">Manicure</option>
                <option value="sobrancelhas">Design de Sobrancelhas</option>
                <option value="depilacao">Depilação</option>
            </select>

            <br><br>

            <label for="profissional">Escolha o profissional:</label>
            <br>
            <select id="profissional" name="profissional" required>
                <option value="">Selecione um profissional</option>
                <option value="yuri">Yuri</option>
                <option value="juliana">Juliana</option>
                <option value="israel">Israel</option>
                <option value="ismael">Ismael</option>
                <option value="henry">Henry</option>
                <option value="rennan">Rennan</option>
                <option value="diego">Diego</option>
                <option value="lucas">Lucas</option>
                <option value="pereira">Pereira</option>
            </select>

            <br><br>

            <label for="data">Data:</label>
            <br>
            <input type="date" id="data" name="data" required>

            <br><br>

            <label for="horario">Horário:</label>
            <br>
            <input type="time" id="horario" name="horario" required>

            <br><br>

            <label for="observacao">Observação (opcional):</label>
            <br>
            <textarea id="observacao" name="observacao"
                rows="4" cols="30"
                placeholder="Digite aqui alguma observação"></textarea>

            <br><br>

            <button type="submit">Agendar</button>

        </form>

    </div>

</body>

</html>
