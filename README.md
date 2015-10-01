# ColinLoggableBundle

Listen create and update on doctrine entities to store dates and user.

```yml
colin_loggable:
  entities:
    Acme\Entity\Foobar:
      createdAt: true
      updatedAt: true
      createdBy: true
      updatedBy: true
```
