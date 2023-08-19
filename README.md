# PostgreSQL-MySQL-Comandos

<h2>Acessar banco de dados Postgresql no Ubuntu</h2>
<ul>
   <li><strong>iniciar um shell (interface de comando) como outro usuário</strong> == sudo -i -u postgres</li>
   <li><strong>acessar e interagir com o banco de dados PostgreSQL</strong> == psql</li>
</ul>
<h2>Comandos PostgresSQL</h2>
<ul>  
   <li><strong>exibe informações sobre a conexão atual, como nome de usário por exemplo</strong> == \conninfo</li>
  <li><strong>listar os bancos de dados</strong> == \l</li>
  <li><strong>acessar um banco de dados existente</strong> == \c nomeDoBanco</li>
  <li><strong>listar as tabelas</strong> == \dt</li>
  <li><strong>apagar linha de uma tabela passando o id</strong> == DELETE  from <tabela> WHERE id = 1</li>
</ul>

<h3>Comandos em tabelas</h3>
<ul>
<li><strong>update nome_da_tabela SET nome_coluna = 'novo valor para atualizar' WHERE id = 1;</strong> 
<p>Atualizar uma coluna específica de uma tabela, passando como condição o id.</p>
</li>
</ul>
