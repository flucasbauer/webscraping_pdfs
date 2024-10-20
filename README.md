## Web Scraping para Download de +1000 PDFs

Desenvolvi um script de web scraping com o objetivo de criar um banco de dados para apoiar o Núcleo de pesquisa no qual atuo. O projeto envolveu a parametrização de diversos campos e a automação de CAPTCHAs, integrando-se a um pipeline de ETL.

Utilizei a biblioteca Selenium e a técnica 2captcha, amplamente empregada para resolver CAPTCHAs. O código foi projetado para lidar com CAPTCHAs incorretos, repetindo a chamada à API 2captcha até que o desafio seja resolvido com sucesso, garantindo o download automático dos PDFs antes de prosseguir.

![Execução do Script](./video/execucao_script.gif)

