Esse código foi desenvolvido com o propósito de criar um cadastro de reservas para um hotel.
Nele há três fazes, sendo que na primeira a lógica de captura de exceções está na classe principal, isso faz com que o código seja 
mais bagunçado e difícil de prestar assistência.
No segundo, está mais organizado, porém ainda a lógica na classe principal fazendo com que isso possa dificultar a manutenção do código.
No terceiro, a lógica foi inteiramente para classe secundária onde poderá ser prestado a manutenção do código sem interfir com a classe principal, 
para assim ser possível adicionar quantas chamadas de exceções e soluções para estas exceções for necessária.
