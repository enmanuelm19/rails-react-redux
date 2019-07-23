## Tutorial de como configurar react-redux dentro de rails 5+

Se necesita tener instalada la version 2.6.3 de ruby para correr el siguiente comando:

> rails new my-app --webpack=react

Creamos nuestra vista estatica donde se alojara nuestro componente base

> rails g controller home index

Modificamos las rutas (**condig/routes.rb**) para colocarlo como la ruta raiz

```ruby
...
root 'home#index'
...
```

