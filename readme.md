```sh
$ cp .env.example .env
$ touch database/database.sqlite
$ ./artisan key:generate


$ ./artisan make:auth

$ ./artisan make:model -m Laboratorio
$ ./artisan make:controller LaboratorioController --resource
$ ./artisan migrate

$ ./artisan make:model -m Medicamento
$ ./artisan make:controller MedicamentoController --resource
$ ./artisan migrate

$ ./artisan make:model -m Estoque
$ ./artisan make:controller EstoqueController --resource
$ ./artisan migrate

$ ./artisan make:model -m Venda
$ ./artisan make:controller VendaController

$ ./artisan make:migration create_table_medicamento_venda --create=medicamento_venda
```