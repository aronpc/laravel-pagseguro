## Laravel PagSeguro

[![Build Status](https://travis-ci.org/michaeldouglas/laravel-pagseguro.svg?branch=master)](https://travis-ci.org/michaeldouglas/laravel-pagseguro)
[![Latest Unstable Version](https://poser.pugx.org/leaphly/cart-bundle/v/unstable.svg)](//packagist.org/packages/michael/laravelpagseguro)
[![License](https://poser.pugx.org/leaphly/cart-bundle/license.svg)](https://packagist.org/packages/michael/laravelpagseguro)

O laravel-pagseguro consome a API do PagSeguro e prove uma forma 
simples de gerar o pagamento, a notificação e as transações de sua loja ou etc.

## Manual PagSeguro
[http://download.uol.com.br/pagseguro/docs/pagseguro-checkout-transparente.pdf](http://download.uol.com.br/pagseguro/docs/pagseguro-checkout-transparente.pdf)

## Instalação

Abra o arquivo `composer.json` e insira a seguinte instrução:

    "require": {
        "michael/laravelpagseguro": "dev-master"
    }

Após inserir no require o `Laravel PagSeguro`, você deverá executar o comando:

    composer update

## Service Provider Laravel PagSeguro

Abra o arquivo `app/config/app.php` e adicione no array `providers` a seguinte instrução:

    'laravel\pagseguro\PagseguroServiceProvider'

## Licença

O Laravel PagSeguro utiliza a licença MIT, para saber mais leia no link: [MIT license](http://opensource.org/licenses/MIT)