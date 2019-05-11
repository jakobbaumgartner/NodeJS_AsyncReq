ASYNC REQUESTS - AJAX, fetch
--------------------------------------------------------------------------
	More on the fetch API: https://developers.google.com/web/updates/2015/03/introduction-to-fetch

	More on AJAX Requests: https://developer.mozilla.org/en-US/docs/Web/Guide/AJAX/Getting_Started


	Omogoča nam spreminjanje le dela strani in komunikacijo s strežnikom, 
	brez posodabljanja strani. 

	Potrebujemo javascript kodo na client side.

	Komuniciramo v formatu json. 

	Podatke dobimo preko req.params.___ in ne
	preko req.body._____ . Poleg tega NE naredimo redirect.

	Na client side uporabimo fetch metodo, da pošljemo podatke backend.
	Iz backend frontendu še ne pošiljamo odgovora.
