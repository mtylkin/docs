The name for each audit log entry is composed of the `action` object or category qualifier, followed by an operation type. For example, the `repo.create` entry refers to the `create` operation on the `repo` category.

Cada entrada del registro de auditoría muestra información vigente acerca de un evento, como:

- The {% ifversion ghec or ghes or ghae %}enterprise or {% endif %}organization an action was performed in
- The user (actor) who performed the action
- The user affected by the action
- En qué repositorio se realizó una acción
- La acción que se realizó
- En qué país se realizó la acción
- La fecha y hora en que ocurrió la acción
{%- ifversion enterprise-audit-log-ip-addresses %}
- Opcionalmente, la dirección IP origen para el usuario (actor) que realizó la acción
{%- endif %}
