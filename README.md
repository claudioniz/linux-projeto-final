- Esse projeto foi baseado no fork do projeto de # denilsonbonatti/toshiro-shibakita
- Foi feita algumas modificações/melhorias.
- Foi reestruturada as pastas abaixo e utilização de dockerfile e docker-compose:

- __docker__: contém o arquivo do docker-compose __projeto-final.yml__.
- __mysql/init__: contém o arquivo de crição da tabela dados.
- __web-app__: contém o arquivo dockerfile para php e o arquivo index.php.

# Para executar subir aplicação siga os passos abaixo:

1. git clone https://github.com/claudioniz/linux-projeto-final.git
2. Entre na pasta __linux-projeto-final/docker__ através do comando: __cd linux-projeto-final/docker__
3. Execute o comando: __docker-compose -f ./projeto-final.yml up__

Deverão ser exibidos os containers __wep-app__ e __database-mysql__ 

4. Acessar o endereço __http://localhost:8081/__


# Resultado esperado: 
![Resultado esperado](resultado-final.gif)
