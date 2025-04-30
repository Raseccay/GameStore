1. skapa azure app service

Först loggade ja in i Azure Portal och skapade en ny app Service.
 Det är i princip en molntjänst där man kan köra olika webbapplikationer. 
Jag valde en resource group, gav 
appen ett namn, valde rätt runtime stack, valde en region nära användarna.
 Jag satte också upp en App Service Plan, vilket bestämmer prestanda och prisnivå för tjänsten.

2. Deployment / Github

jag kopplade mitt repo till azure via deployment center i app service 
De som azure gör bra är att de automatist skapar ett action arbets flöde vilket förenklar 
Sedan kopplade jag mitt repo till Azure. Jag gick till deployment center i app service inställningarna och anslöt 
mitt GitHub konto, sen valde jag rätt repository samt branch som innehåller min kod.


3.
Jag gick in på appens URL som jag fick ifrån Azure jag o checkade att allt funka som det skulle
Jag kolla att applikationen och  alla funktionerna fungerade som de skulle


4.
För att jag ska kunna ha mer information och kontroll över min nya app så kommer jag använda mig av Application Insights
det är ett verktyg som låter användaren se prestanda data, varningar, felmeddelanden i realtime.

5.
jag valde 2 verktyg för o hantera min säkerhet. Det första blev Åtkomstkontroll (IAM).
sen körde jag SSL-kryptering som kryptering. Anledningen till att jag valde IAM är för att den ger mig möjliheten
att ha kontrol över min app och en överblick över användare.
Jag aktiverade också HTTPS så att alla trafik är krypterad och säker
Det skyddar även användardata och all kommuniktion sker säkert
