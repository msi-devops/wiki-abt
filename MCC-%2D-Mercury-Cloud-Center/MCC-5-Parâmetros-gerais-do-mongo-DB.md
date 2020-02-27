Abaixo seguem os parâmetros encontrados dentro do mongoDB para o MCC.

Dentro do MCC, existem básicamente 5 collections

- base
- projeto_mcc_broker
- projeto_mcc_monitor
- projeto_mcc_portal
- projeto_mcc_processor

Segue exemplo de jundiai abaixo:

![image.png](/.attachments/image-5d61f0a1-3a1e-457b-98ba-1d5bc606527c.png)
<br><br>

**ONDE:**

_Base_

Aqui existirão configurações referentes ao GAMA sua url, ao banco Oracle, entre outros:
![image.png](/.attachments/image-411e199a-230f-4364-9dfb-3d729b8fdb6e.png)

Onde _id e active, são respectivamente o ID dessa collection e se a mesma está ativa ou não.

_api_

Informações sobre replica do broker e URL do gama:
![image.png](/.attachments/image-38107dd6-87e9-4399-87a9-32c75830b35e.png)

<br>

_date_

Provavelmente é a data de inserção dessa collection

<br>

_language_

Idioma utilizado.

<br>

_mongo_

Checar o que significa isso:

![image.png](/.attachments/image-3ef8ab2a-e639-4fc7-bc04-f659da1ec87f.png)

<br>

_Oracle_
Conexão com o banco de dados Mercury, já atualizado com os scripts do MCC
![image.png](/.attachments/image-05523c34-fd75-412a-aefa-2992731c18b3.png)






