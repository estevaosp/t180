<!DOCTYPE html>
<html lang="pt-br">
	<head>
		<title>HTML - Listas e Links</title>
		<meta charset="UTF-8">
		<meta name"viewport" content="width=device-width initial-scale-1">
		<link rel="stylesheet" type="text/css" href="lista.css">
	</head>
	<body>
		<h1>Listas e Links</h1>

		<h2 id="lista-nao-ordenada">Lista não ordenada</h2>
		
		<ul>
			<li>
				Brasil
				<ul>
					<li>Amapá</li>
						<ol>
							<li>Macapá</li>
						</ol>
					</li>
					<li>Rio de Janeiro</li>
					<li>Minas Gerais</li>
						<ol>
							<li>Belo Horizonte</li>
						</ol>
					</li>
					<li>Pará
						<ul>
							<li>Belém</li>
						</ul>
					</li>
				</ul>
			</li>
			<li>Argentina</li>
			<li>Uruguai</li>
			<li>Paraguai</li>
		</ul>

		<h2>Lista ordenada</h2>

		<ol>
			<li>Corinthians</li>
			<li>Palmeiras</li>
			<li>Santos</li>
			<li>São Paulo</li>
		</ol>

		
		<h2>Lista de Definições</h2>		

		<dl>
			<dt>TV</dt>
				<dd>32 polegadas, smart, ...</dd>
				<dd>127 volts</dd>
			<dt>PC</dt>
				<dd>USB, 19 polegadas, Core I5</dd>
		</dl>

		<h2>Links</h2>

		<nav>
			<ul>
				<li><a href="https://www.mg.senac.br/Paginas/default.aspx" target="_blank">SENAC MG</a></li>
				<li><a href="#top">Voltar ao topo</a> </li>
				<li><a href="#lista-nao-ordenada">Ver a lista não ordenada</a></li>
			</ul>
		</nav>

	</body>
</html>
