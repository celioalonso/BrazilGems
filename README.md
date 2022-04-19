# BrazilGems

Brazilian Rails é um conjunto de gems para serem usadas com Ruby e com o Ruby on Rails e tem como objetivo unir alguns recursos úteis para os desenvolvedores brasileiros.

Quais as gems que compõe o Brazilian Rails?
brcep
brdata
brdinheiro
brhelper
brnumeros
brstring
brcpfcnpj
brI18n
OBS: A gem brtraducao foi removida do Brazilian Rails devido a adição do suporte i18n do Rails. Ele continua podendo ser usada, porém não faz mais parte desse projeto. Para maiores detalhes, leia o post O Brazilian Rails e o suporte i18n

OBS: A gem brI18n foi criada para acomodar as traduções usando suporte i18n das versões mais recentes do Rails.

Como faço para instalar?
É muito difícil...

com Bundler
Adicionar ao seu Gemfile:

gem 'brazilian-rails'
sem Bundler
require "brazilian-rails"

Por padrão, a pluralização vem desabilitada, isso para não atrapalhar os projetos que já existem.

I18n
Por padrão a gem não carrega o suporte de traduções do Rails, para usa-la você deve fazer o require abaixo:

require 'brI18n'
Como funciona?
Está tudo explicado na nossa api.

Achei um BUG, o que eu faço?
No melhor seria fazer um fork, adicionar os testes para reproduzir o erro, implementar a devida correção e fazer um pull request. Se acha que não tem capacidade para isso (tá com preguiça), por favor, nos avise! Isso é fácil e rápido. Isso pode ser feito em http://github.com/tapajos/brazilian-rails/issues

Como contribuir?
Fazer um fork do projeto
Instalar as dependências: bundle install (Se não tiver o bundler instalado, faça antes: gem install bundler)
Fazer os devidos ajustes com os respectivos testes (TestUnit se possível e tente fazer commits atômicos)
Fazer pull request
Quem está por traz disso tudo?
O Marcos Tapajós tomou coragem para publicar todas as funcionalidades em um plugin, com testes unitários para garantir que tudo funcione conforme manda o figurino. Além do Tápa, outros loucos mantém tudo organizado, são: Celestino Gomes, André Luiz Kupkovski, A galera da Improve It e mais alguns que ficam escondidos para não pagar esse mico...

Muitos já contribuíram com o projeto.
