While Basic

Declare @Codigo int
	  Set @Codigo  = 1

	  While @Codigo < 6
	     BEGIN
			Select Id_Livro as ID,
			Nome_Livro as Livro,
			Preco_Livro as Preco
			from tb_Livro
			where Id_Livro = @Codigo
			Set @Codigo = @Codigo +1
		 END;



*tabelas ja existentes*

Autor : Bóson Treinamentos
