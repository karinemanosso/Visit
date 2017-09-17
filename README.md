<html>
	<head>
	<title>Visitante</title>
	</head>
	<body>
	<style>
		table
		td {
		text-align:right
		}
	</style>
		<h1>Visitante</h1>
	<hr>
		<table style="width:25%">
			<tr>
			<td>Nome:</td>
			<td><input type="text" ID="Nome" value=""/></td>
		</tr>
			<tr>
			<td>CPF:</td>
			<td><input type="text" ID="CPF" value=""/></td>
		</tr>
			<tr>
			<td>RG:</td>
			<td><input type="text" ID="RG" value=""/></td>
		</tr>
			<tr>
			<td>Data de Nascimento:</td>
			<td><input type="text" ID="Data de Nascimento" value=""/></td>
		</tr>
			<tr>
		<td>Data da Visita:</td>
		<td><input type="text" ID="Data da Visita" value=""/></td>
		</tr>
			<tr>
		<td>Hora da Visita:</td>
		<td><input type="text" ID="Hora da Visita" value=""/></td>
		</tr>
		<tr>
		<td></td>
		<td><button type="button">Salvar</button>
		<button type="button">Cancelar</button></td>
		</tr>
		
		
		<h3>Histórico do Visitante<h3>

                <div class="container">

  <div class="table-responsive">
    <table class="table table-striped table-bordered table-hover">
      <thead>
        <tr>
          <th>#</th>
          <th>Visitante</th>
          <th>CPF</th>
          <th>Data Visita</th>
          <th>Hora</th>
          <th> Entrada/Saida</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <th>1</th>
          <td>Caroline Oliveira </td>
          <td>2341678</td>
          <td>10/09/2017</td>
          <td>12:32</td>
          <td>Entrada</td>
            <td>
					<a href="/assets/javascripts/manual/fake-response/save.json" data-action-modal="edit">Editar</a>
					<a href="/assets/javascripts/manual/fake-response/save.json" data-confirm-text="Confirma exclusão do item?" class="text-danger">
						Excluir
					</a>
				</td>
        </tr>
        <tr>
          <th>2</th>
          <td>Ricardo Muller</td>
          <td>10198765</td>
          <td>20/06/2017</td>
          <td>12:54</td>
          <td>Saida</td>
            <td>
					<a href="/assets/javascripts/manual/fake-response/save.json" data-action-modal="edit">Editar</a>
					<a href="/assets/javascripts/manual/fake-response/save.json" data-confirm-text="Confirma exclusão do item?" class="text-danger">
						Excluir
					</a>
				</td>
        </tr>
          <tr>
          <th>3</th>
          <td>Aline Espanha</td>
          <td>9856012</td>
              <td>15/08/2017</td>
          <td>16:12</td>
          <td>Entrada</td>
              <td>
					<a href="/assets/javascripts/manual/fake-response/save.json" data-action-modal="edit">Editar</a>
					<a href="/assets/javascripts/manual/fake-response/save.json" data-confirm-text="Confirma exclusão do item?" class="text-danger">
						Excluir
					</a>
				</td>
              
        </tr>
	</table>
	<hr>
	</body>
</html> 
		
		
