# Esteban-Warinet

## Descripcion

Aplicacion para simular un servicio de mensajes utilizando WebSckets. Mediante SpringBoot

## Inicializar

Desde la raiz del proyecto ejecutar

```bash
./mvnw spring-boot:run
```

## End points

### Enviar mensajes

**URL**: /app/chat/send-message

**Tipo**: MessageMapping

**Body**

```json
{
    "sender": "username",
    "content": "Mensage",
    "type": "CHAT"
}
```

### Agregar usuario

**URL**: /app/chat/add-user

**Tipo**: MessageMapping

**Body**

```json
{
    "sender": "username",
    "type": "JOIN"
}
```