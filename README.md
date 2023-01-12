# kitaNetwork-backend

## App Diagram

This is an app diagram. These are services planned to be implemented

```mermaid
graph TD
	UI-->API_Gateway;
	API_Gateway-->AuthService;
	API_Gateway-->MailService;
	API_Gateway-->NewsService;
	
	AuthService-->AuthPostgresSQL;
	
	MailService-->MailMongoDB;
	
  NewsService-->NewsMongoDB;
```
