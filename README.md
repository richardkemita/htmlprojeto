<!DOCTYPE html>

<html>

<head>


	<title>Projeto</title>
	<link rel="stylesheet" type="text/css" href="style.css">
	<link rel="stylesheet" type="text/css" href="reset.css">

</head>

<body text="#000000">

	<h1 class="Titulos" style="border: solid;">Proposta / Requisição</h1>
	<h1 class="Titulos" style="border: solid;">Admissão / Férias / Rescisão Contratual</h1>

<div>
	<h1 class="Perguntas">DADOS PESSOAIS (PREENCHIMENTO OBRIGATÓRIO EM CASO DE FÉRIAS E/OU DESLIGAMENTO)</h1>
	<label for="NOME">NOME: </label>
	<input type="text" name="NOME">

	<label for="RC">REGISTRO/CRÁCHA</label>
	<input type="text" name="RC">

	<p><label for="CARGO">CARGO:
	<input type="text" name="CARGO">
	<label for="DS">DEPTO/SETOR</label>
	<select id="DEPTO/SETOR" name="DS">
		<option value="MARKETING">Marketing</option>
		<option value="PRODUÇÃO">Produção</option>
		<option value="T.I">T.I</option>
		<option value="Financeiro">Financeiro</option>
		<option value="IC">IC</option>
		<option value="R.H">R.H</option>
		<option value="Outros">Outros</option>
	</select>



	<p><label for="SALARIO">SALARIO ATUAL R$</label>
		<input type="number" name="SALARIO">
		<label for="DATA">DATA ADMISSÃO</label>
		<input type="date" name="DATA">
</div>

	<h2 class="cor" style="border: solid"> SO EXCLUSIVO EM FERIAS </h2>

<div>
		<h1 class="Perguntas"> INICIO DAS FÉRIAS</h1>
		<input type="date" name="Ferias">
	
	<p>Opções:</p>
	
	<h3><input type="radio" id="Ferias" name="Opções" value="30 Dias sem descanso">
	<label for="Ferias" class="Perguntas">30 Dias em descanso</label>
	
	<h3><input type="radio" id="Ferias" name="Opções" value="20 Dias em descanso + 10 Remunerado">
	<label for="Ferias" class="Perguntas">20 Dias em descanso + 10 Remunerado</label>

	<h3><input type="radio" id="Ferias"name="Opções" value="Opção pelo 13 Salario">
	<label for="Ferias" class="Perguntas">Opção pelo 13 salario</label>

	<h1>NOTA:Esta proposta deve chegar ao Depto Rec. Humanos com antecêdencia mínima de 10 (DEZ) dias da data prevista para as férias do colaborador.</h1>
</div>


		<h2 class="cor" style="border: solid;">USO EXCLUSIVO EM CASO DE DESLIGAMENTO</h2>

		<div>
			<h3><input type="radio" id="DESLIGAMENTO" name="DESLIGAMENTO">
				<label for="DESLIGAMENTO" class="Perguntas">DEMISSÃO</label>
				<h3><input type="radio" id="DESLIGAMENTO" name="DESLIGAMENTO">
				<label for="DESLIGAMENTO" class="Perguntas">Demissionario</label>
				<h3><input type="radio" id="DESLIGAMENTO" name="DESLIGAMENTO">
				<label for="DESLIGAMENTO" class="Perguntas">Reprova de experiencia</label>
				<h3><input type="radio" id="DESLIGAMENTO" name="DESLIGAMENTO">
				<label for="DESLIGAMENTO" class="Perguntas">Outros</label>
				<label for="OUTROS">Justificativa / Motivo Alegado</label>
				<input type="text" name="OUTROS">

		</div>
		
</body>
</html>



CSS
				
				body{
  font-style: italic;

}

.Perguntas{
	font-size: 18px
	text-color
}

.Titulos{
	text-align: center;
	font-size: 22px
	border:groove;
}
div{
border: double;
	font-style

}
.cor{
	text-align: center;
	font-size: 22px
	border-solid:
	background:yellow 
}
label{
	color: #000000
}
h2{
	background: yellow
}
h4{
	background: orange
}
