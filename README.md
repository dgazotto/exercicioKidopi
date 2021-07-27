# exercicioKidopi
Exercício para o processo seletivo da Kidopi

Descrição: Por meio do serviço disponibilizado gratuitamente em https://covid-api.mmediagroup.fr/v1, é possível obter dados a respeito do número de casos confirmados, recuperações e mortes de várias países afetados pela COVID-19. 
Exemplo: 
- Método: GET  
- URL: https://covid-api.mmediagroup.fr/v1/cases?country=Brazil 
- Retorno: { "All": 
            { 		"confirmed": 19707662, 		
                  "recovered": 17704701, 		
                  "deaths": 550502, 		
                  "country": "Brazil", 		
                  "population": 209288278, 		
                  "sq_km_area": 8547403, 		
                  "life_expectancy": "62.9", 		
                  "elevation_in_meters": 320, 		
                  "continent": "South America", 		
                  "abbreviation": "BR", 		
                  "location": "South America", 		
                  "iso": 76, 		
                  "capital_city": "Brasília" 	
               } 
           } 
Veja mais em: https://github.com/M-Media-Group/Covid-19-API  

1º parte:  
- Você deverá criar um script (em sua linguagem de preferência) que, ao escolher um país (Brazil, France ou US), efetue a comunicação com o serviço descrito acima e retorne o número total de casos confirmados, recuperações e mortes (o serviço também traz os dados de cada estado e você pode ignorá-los).  

2ª parte: 
- Você também deverá armazenar em um banco de dados (de sua preferência) a data de todos os acessos que seu script fez a Covid-19-API, bem como qual o país escolhido para a consulta.  

3ª parte: - Você deverá criar uma interface gráfica que permita ao usuário escolher o país e visualizar os números de casos confirmados, recuperações e mortes. Além disso, a interface deve conter um aviso no rodapé, informando a data do último acesso à Covid-19-API.

Crie seu repositório em modo privado e compartilhe com o usuário dgazotto.

Boa sorte :)
