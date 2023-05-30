# Fintech 3al2ad
## Description  
This is a repo for a fintech project composed of two microservices, a telecom service (ex: Vodafone) and a payment aggregator (ex: Fawry)  
Further details can be found here and here.  


## Specification for telecom service
- [ ] System should support cards with multiple possible values.
- [ ] System should store cards in a database.
- [ ] Cards should have an expiration date.
- [ ] System should give each user an ID.
- [ ] System should allow user to buy a card(s).
- [ ] System should provide statistics about cards.
- [ ] System should provide statistics about users.
- [ ] User should be able to view his own statistics.
- [ ] Admin should be able to view all statistics.
- [ ] Priviledged endpoints should be secured with Spring Security.
- [ ] System should automatically refill cards when they are out of stock.
- [ ] System should emit events when card stock is low or when a card stock refill is initiated.

## Specification for payment service
- [ ] System should have users.
- [ ] System should allow user to pay for a card.
- [ ] User should be able to return unused cards.
- [ ] System should support recurring billing for subscription-based services.
- [ ] System should persisit all data in a database.
- [ ] System should integrate with telecom service.
- [ ] System should provide statistics about transactions.
- [ ] User should be able to view his own statistics.
- [ ] Admin should be able to view all statistics.
- [ ] Users should be able to view their transaction history.
- [ ] Priviledged endpoints should be secured with Spring Security.

## Technologies 
- Spring boot (Web, JPA, Security, Actuator)
- Java 17
- Postgres
- Azure 


