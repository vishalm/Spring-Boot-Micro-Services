# Micorservices 
--- 
 Creating MicroServices with the help of spring boot and Docker.
### Tech Stack
- Java 8
- Sprint Boot
- Maven
- H2 (With the dev profile you can use H2, but with the Prod Profile you need to use MySQL)
- tomcat

## Getting Start with MicroServices
Run Discovery server as spring boot

### Micro Services
  - Currency Converter
  - Exchange Rates
  - Text Translation
  - Weather  

### Configuration 
  Port for each Service should be unique. 

Spring Boot
#### URLs
 - http://localhost:8320/exchange-rates/from/EUR/to/INR
 - http://localhost:8220/currency-converter/from/EUR/to/INR/quantity/100
 - http://localhost:8220/currency-converter-feing/from/EUR/to/INR/quantity/1001
