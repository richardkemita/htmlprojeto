<!DOCTYPE html>

<html>

<head>


	<title>Projeto</title>
	<link rel="stylesheet" type="text/css" href="style.css">
	<link rel="stylesheet" type="text/css" href="">

</head>

<body text="#000000" id="tabela">

	<h2 class="Titulos" style="border: solid;">Proposta / Requisição</h2>
	<h2 class="Titulos" style="border: solid;">Admissão / Férias / Rescisão Contratual</h2>

<div >
	<h2 class="Perguntas">DADOS PESSOAIS (PREENCHIMENTO OBRIGATÓRIO EM CASO DE FÉRIAS E/OU DESLIGAMENTO)</h2>
	<h3><label for="NOME">NOME: </label>
	<input type="text" name="NOME"required pattern="[0-9]{2} [0-9]{5}-[0-9]{4}" placeholder="NOME E SOBRENOME">

	<h3><label for="RC">REGISTRO/CRÁCHA</label>
	<input type="text" name="RC" required pattern="[0-9]{2} [0-9]{5}-[0-9]{4}" placeholder="38DM3AS3">

	<h3><label for="CARGO">CARGO:
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
		<input type="number" name="SALARIO" required pattern="[0-9]{2} [0-9]{5}-[0-9]{4}" placeholder="1.212">
		<label for="DATA">DATA ADMISSÃO</label>
		<input type="date" name="DATA">
</div>

	<h1 class="cor" style="border: solid"> SO EXCLUSIVO EM FERIAS </h2>

<div>
		<h2 class="Perguntas"> INICIO DAS FÉRIAS</h2>
		<input type="date" name="Ferias">
	
	<p>Opções:</p>
	
	<h3><input type="radio" id="Ferias" name="Opções" value="30 Dias sem descanso">
	<label for="Ferias" class="Perguntas">30 Dias em descanso</label>
	
	<h3><input type="radio" id="Ferias" name="Opções" value="20 Dias em descanso + 10 Remunerado">
	<label for="Ferias" class="Perguntas">20 Dias em descanso + 10 Remunerado</label>

	<h3><input type="radio" id="Ferias"name="Opções" value="Opção pelo 13 Salario">
	<label for="Ferias" class="Perguntas">Opção pelo 13 salario</label>

	<h2>NOTA:Esta proposta deve chegar ao Depto Rec. Humanos com antecêdencia mínima de 10 (DEZ) dias da data prevista para as férias do colaborador.</h2>
</div>


		<h1 class="cor" style="border: solid;">USO EXCLUSIVO EM CASO DE DESLIGAMENTO</h1>

		<div>
			<h3><input type="radio" id="DESLIGAMENTO" name="DESLIGAMENTO">
				<label for="DESLIGAMENTO" class="Perguntas">Demissão</label>
				<h3><input type="radio" id="DESLIGAMENTO" name="DESLIGAMENTO">
				<label for="DESLIGAMENTO" class="Perguntas">Demissionario</label>
				<h3><input type="radio" id="DESLIGAMENTO" name="DESLIGAMENTO">
				<label for="DESLIGAMENTO" class="Perguntas">Reprova De Experiência</label>
				<h3><input type="radio" id="DESLIGAMENTO" name="DESLIGAMENTO">
				<label for="DESLIGAMENTO" class="Perguntas">Outros</label>
				<label for="OUTROS">Justificativa / Motivo Alegado</label>
				<input type="text" name="OUTROS">

					<h2>OBS:Em caso de dispensa com substituição, favor preencher os itens abaixo.</h2>
		</div>

<div>
				<h1 class="cor" style="border: solid;">USO EXCLUSIVO EM CASO DE DESLIGAMENTO</h1>
				<h2 style="border: double;">EM CASO DE APROVEITAMENTO INTERNO, FAZ-SE NECESSÁRIO O PREENCHIMENTO DO IMPRESSO PROPOSTA DE ALTERAÇÃO PELA ÁREA REQUISITANTE</h2>
				
				<h3><label for="CARGO1">CARGO:</label>
				<input type="text" name="CARGO1">
				<h3><label for="DEPTO">DEPTO/SETOR:</label>
				<input type="text" name="DEPTO">

				<h3><label for="TDC">TIPOS DE CONTRATO:</label>
				<select id="TDC" name="TDC">

		<option value="EFETIVO">Efetivo</option>
		<option value="PRODUÇÃO">Terceirizado</option>
		<option value="T.I">Estagiário</option>
		<option value="Financeiro">Temporário</option>
	</select>

	<h3><label for="Motivo1">Motivo:</label>
				<select id="Motivo1" name="Motivo1">
				<option value="Licença Maternidade">Liçença Maternidade</option>
				<option value="Aumento de Quadro">Aumento de Quadro</option>
				<option value="Efetivação">Efetivação</option>
				<option value="Substituição1">Substituição</option>
	</select>	
				<h3><label for="AAAA">Requisitos Desejáveis, para Contratação:</label>
				<input type="text" name="AAAA">
	</div>	

<div>


	<h2 class="Perguntas">USO EXCLUSIVO DO DEPTO DE RECURSOS HUMANOS</h2>
	<h3><label for="CARGO2">CANDIDATO APROVADO: </label>
	<input type="text" name="CARGO2">
	<label for="REGISTRO1">REGISTRO/CHAPA</label>
	<input type="text" name="REGISTRO1"required pattern="[0-9]{2} [0-9]{5}-[0-9]{4}" placeholder="38DM3AS">
	
	<h3><label for="CARGO3">CARGO</label>
		<input type="text" name="CARGO3">
		<label for="SALARIO1">SALARIO R$</label>
		<input type="number" name="SALARIO1" required pattern="[0-9]{2} [0-9]{5}-[0-9]{4}" placeholder="1.212">

		<label for="DATA1">DATA</label>
		<input type="date" name="DATA1">
		<label for="HORAS">HORA</label>
		<input type="time" name="HORAS">

	<h3><label>DATA ADMISSÃO</label>
		<input type="date" name="DATAA">
		<label>DEPTO/SETOR</label>
		<input type="text" name="DS2">
		<label>CENTRO CUSTO</label>
		<input type="text" name="CC">

		<h3><label>HORARIO DE TRABALHO</label>
			<input type="date" name="HDT">
			<label>OBSERVAÇÕES</label>
			<input type="text" name="OBS1">

			<h3>APROVEITAMENTO POR SELEÇÃO INTERNA</h3>
			<h3><input type="radio" id="DESLIGAMENTO" name="NAO">
				<label for="SIM" class="Perguntas">SIM</label>
				<h3><input type="radio" id="DESLIGAMENTO" name="NAO">
				<label for="NÃO" class="Perguntas">NÃO</label>

</div>

<h2> OBS: NENHUMA CONTRATAÇÃO SERÁ OFICIALIZADA, SEM AS DEVIDAS APROVAÇÕES</h2>

<div>
	<h3>AREA REQUISITANTE:</h3>
	<h3><label for="DD">Data:</label>
	<h3><input type="date" name="DD">
		<h3>DIRETORIA:</h3>
	<h3><label for="DIRETORIA">DATA</label>
	<h3><input type="date" name="DIRETORIA">
		<h3>RECURSOS HUMANOS:</h3>
	<h3><label for="DIRETORIA">DATA</label>
	<h3><input type="date" name="DIRETORIA">
</div>
<script>
    function CriaPDF() {
        var minhaTabela = document.getElementById('tabela').innerHTML;
        var style = "<style>";
        style = style + "table {width: 100%;font: 20px Calibri;}";
        style = style + "table, th, td {border: solid 1px #DDD; border-collapse: collapse;";
        style = style + "padding: 2px 3px;text-align: center;}";
        style = style + "</style>";
        // CRIA UM OBJETO WINDOW
        var win = window.open('', '', 'height=700,width=700');
        win.document.write('<html><head>');
        win.document.write('<title>FORMULARIO</title>');   
        win.document.write(style);                                     
        win.document.write('</head>');
        win.document.write('<body>');
        win.document.write(minhaTabela);                          
        win.document.write('</body></html>');
        win.document.close(); 	                                         
        win.print();                                                          
    }
</script>
</head>
<p>
        <input type="button" value="Criar PDF" id="btnImprimir" onclick="CriaPDF()" />
    </p>
  </body>
</html>
		
		
		CSS
		
		
		body{
  font-style: italic;
  background: #FFFACD
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
h1{
	background: yellow
}
h4{
	background: orange
}
h6{
	background: 	#4169E1
}
h2{
	text-align: center;
}
.enviar{
	width:50%;
	padding:20px 0;
	cursor:pointer;
}
