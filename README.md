Demo: https://pasquale-cs.github.io/format-number/

***

# [EN] - Plugin format number for jQuery
Plugin format number with currency for jQuery

Include "js/pcsFormatNumber.jquery.js" in your project and use the function "$(selector).pcsFormatNumber()" in your script.

### Example include plugin (JS):
```js
<body>
  ...
  <script src="js/pcsFormatNumber.jquery.js"></script>
  ...
</body>
```

### Example use function:
```js
<body>
  ...
  <input class="pcs-format-number" type="text">
  ...
  <script>
    $(document).ready(function() {
			$('.pcs-format-number').pcsFormatNumber({	// Set selector for input element (ID or Class)
	      decimal_separator: ".",					        // Set copy element
	      number_separator: ",",					        // Set button for copy element
			  to_fixed: 2,							              // Set fixed of decimal
			  currency: "€"							              // Set currency (€, $, £...)
			});
		});
  </script>
  ...
</body>
```

## Do you Like!
Give me a coffee: https://www.paypal.me/pasqualecs
Thank you =)

***

# [IT] - Formattare un numero con jQuery
Plugin per la formattazione di un numero.

Includere il file "js/pcsFormatNumber.jquery.js" net tuo progetto e usare la funzione "$(selector).pcsFormatNumber()" nel tuo script.

### Esempio per l'inclusione del plugin (JS):
```js
<body>
  ...
  <script src="js/pcsFormatNumber.jquery.js"></script>
  ...
</body>
```

### Esempio per l'uso:
```js
<body>
  ...
  <input class="pcs-format-number" type="text">
  ...
  <script>
    $(document).ready(function() {
			$('.pcs-format-number').pcsFormatNumber({	// Set selector for input element (ID or Class)
	      decimal_separator: ".",					        // Set copy element
	      number_separator: ",",					        // Set button for copy element
			  to_fixed: 2,							              // Set fixed of decimal
			  currency: "€"							              // Set currency (€, $, £...)
			});
		});
  </script>
  ...
</body>
```
## Ti Piace!
Mi offri un caffè: https://www.paypal.me/pasqualecs
Grazie =)