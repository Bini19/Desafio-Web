# Desafio-Web

Foram utilizadas as linguagens a seguir : Html e Css.
Uma tabela com modificações somente no código, não há interações entre usuario e interface, porém há um Rainbow nos Titulos das tabelas 1 e 2, o nome da tabela continuou o mesmo pois se tratava do mesmo andamento do projeto.

Código em HTML5:

<!DOCTYPE html>
<html>

<head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width">
	<title>repl.it</title>
	<link href="style.css" rel="stylesheet" type="text/css" />
</head>

<body>
	<script src="script.js">
	</script>
</body>
<table summary="Euax">
	<caption>Desafio Web Developer</caption>
	<thead>
		<tr>
			<th colspan="8">Tabela 1</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td rowspan="2"> EUAX</td>

			<td>Id Projeto</td>

			<td>Nome Projeto</td>

      <td>Data Inicio</td>

      <td>Data Final</td> 

      <td>% Completo</td>

      <td>Atrasado</td>
		</tr>
		<tr>

			<td>1</td>

			<td>Desafio Web</td>

			<td>01/04/2021</td>

      <td>08/04/2021</td>

      <td>90%</td>

      <td>Não</td>

		</tr>
	</tbody>
</table>
<table summary="Euax">

	<caption>Progresso Desafio Web Developer</caption>

	<thead>

		<tr>
			<th colspan="8">Tabela 1</th>
		</tr>

	</thead>
	<tbody>

		<tr>

			<td rowspan="2"> EUAX</td>

			<td>Id Atividade</td>

			<td>Nome Projeto</td>

      <td>Data Inicio</td>

      <td>Data Final</td> 

      <td>% Completo</td>

      <td>Finalizado</td>
		</tr>

		<tr>

			<td>1</td>

			<td>Desafio Web</td>

			<td>02/04</td>

      <td>08/04</td>

      <td>100%</td>

      <td>Sim</td>

      

		</tr>

	</tbody>

</table>

</html>



CÓDIGO EM Css:

table, td, th, tfoot {border:solid 1px #000; padding:5px;}
th {background: linear-gradient(124deg, #ff2400, #e81d1d, #e8b71d, #e3e81d, #1de840, #1ddde8, #2b1de8, #dd00f3, #dd00f3);
background-size: 1800% 1800%;
-webkit-animation: rainbow 18s ease infinite;
-z-animation: rainbow 18s ease infinite;
-o-animation: rainbow 18s ease infinite;
  animation: rainbow 18s ease infinite;}

caption {font-size:x-large;}
colgroup {background:#F60;}
.coluna1 {background:#F66;}
.coluna2  {background:#F33;}
.coluna3  {background:#F99;}
