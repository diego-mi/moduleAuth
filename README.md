<h1>Modulo para Login - Zend Framework2</h1>

<h2>Dependencias</h2>

<p>
Doctrine ORM
Modulo independente
</p>

<h2>Banco exemplo</h2>

<pre>
Create Table User (
	id int NOT NULL PRIMARY KEY,
	nome varchar(50) NOT NULL,
	login varchar(50) NOT NULL,
	email varchar(50) NOT NULL,
	password varchar(50) NOT NULL
)
</pre>