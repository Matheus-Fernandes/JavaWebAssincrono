# JavaWebAssincrono
Faz com que uma pagina web influencie o comportamento de outra página que está num navegador diferente

A pagina "receptor.html" faz uma requisição para uma servlet assincrona "ServletReceptor".

Ao requisitar a servlet novamente dessa vez com o parametro "operacao=atualizar", de outro navegador, 
o servlet libera a requisição assincrona, atualizando a pagina receptor.html que aguardava a resposta.
