# 1. Utworzenie klastra z trzema węzły roboczymi
<img width="719" height="37" alt="image" src="https://github.com/user-attachments/assets/4052d841-2bb6-4dcf-ad25-e093f211cfcc" />

## Utworzone węzły
<img width="727" height="164" alt="image" src="https://github.com/user-attachments/assets/61131822-6633-401b-bb81-0399b005c59d" />

## Labelowanie węzłów
<img width="477" height="242" alt="image" src="https://github.com/user-attachments/assets/b463dbab-c3af-4740-bbde-03f2d71d60f9" />

## Potwierdzenie labelowania
<img width="1062" height="268" alt="image" src="https://github.com/user-attachments/assets/0a75bf06-a18d-4693-83b1-744599911cec" />


# 2. Wdrożenie
## Zawartosc pliku wdrozenie.yaml
<img width="302" height="759" alt="image" src="https://github.com/user-attachments/assets/f72015e9-977d-404c-b6c4-9aa9a4b07cec" />

Wynik apply manifestu

<img width="243" height="122" alt="image" src="https://github.com/user-attachments/assets/ee2e305a-094a-48ff-ae23-ca747ceebc5e" />

# 3. Service dla frontendu
## Zawartosc manifestu frontend-svc.yaml
<img width="233" height="231" alt="image" src="https://github.com/user-attachments/assets/7fe8806d-09da-4cd8-9e89-afed3f0fba14" />

Wynik apply manifestu

<img width="260" height="46" alt="image" src="https://github.com/user-attachments/assets/dce8828c-874a-4ff3-a2d4-413b2d156cc4" />

<img width="520" height="47" alt="image" src="https://github.com/user-attachments/assets/9be3a0c6-0271-413d-a90e-df18895fc5b1" />

# 4. Service dla backendu i bazy danych
## Zawartosc manifestu db-backend-svc.yaml
<img width="261" height="389" alt="image" src="https://github.com/user-attachments/assets/df957212-2143-4dc8-a95e-fc03727c5142" />

Wynik działania:

<img width="518" height="207" alt="image" src="https://github.com/user-attachments/assets/7bd2c1ca-7bf6-4609-a9e7-dea12c4a4f02" />

# 5. Polityka sieciowa
## Zawartosc manifestu
<img width="271" height="319" alt="image" src="https://github.com/user-attachments/assets/70380702-62f6-466c-8a4d-a90180d8b5a1" />

Wynik działania:

<img width="435" height="132" alt="image" src="https://github.com/user-attachments/assets/27aa535d-9aea-414a-8471-6f9ab153e6fd" />

# 6. Testy: 

## Z backendu do bazy
<img width="729" height="47" alt="Zrzut ekranu 2025-12-9 o 9 06 39 AM" src="https://github.com/user-attachments/assets/e2267131-6bc6-4c15-904d-99589a8c3729" />

Wynik: 

```
* Host mysql-svc:3306 was resolved.
* IPv6: (none)
* IPv4: 10.96.188.130
*   Trying 10.96.188.130:3306...
* Connected to mysql-svc (10.96.188.130) port 3306
```

## Z frontendu do bazy

<img width="722" height="51" alt="image" src="https://github.com/user-attachments/assets/63d174ee-2e89-4811-b5e8-a0240588d8c9" />

Wynik:

```
* Host mysql-svc:3306 was resolved.
* IPv6: (none)
* IPv4: 10.96.188.130
*   Trying 10.96.188.130:3306...
* Connection timed out after 5002 milliseconds
* closing connection #0
```


