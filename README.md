:skull_and_crossbones:

Fuentes fontawesome, no funcionan en Typora pero sí en MKdocs con pip:  :fa-coffee:   :fa-beer: :fa-cc-paypal: :fa-comments:

```
!!! todo
```

```sql
/* 
	Comentario
*/
SELECT C1,C2 
FROM TABLE1
WHERE C1='kakita'
```
```python
print('Hola mundo!!')
```
```mermaid
erDiagram
    Persona 					||--o| Recurso_Humano 			: "id.Persona RRHH"
    Recurso_Humano				||--o| Periodo_Recurso_Humano	: "id.Persona RRHH"
    Periodo_Recurso_Humano		||--|{ Rol_Recurso_Humano		: "id.sociedad, Id.RRHH, Núm. Periodo RRHH"
    Rol_Recurso_Humano			||--|| Unidad_Organizativa		: "id.sociedad, unidad organizativa"
    Periodo_Recurso_Humano		||--o| Contrato_Interno			: "id.contrato interno"
    Contrato_Interno			||--|| Contrato_Legal			: "id.contrato legal"

```
