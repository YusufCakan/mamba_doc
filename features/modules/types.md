⬅ [🏠 Home](../../README.md)

⬅ [2 🛠 Features](../README.md)

⬅ [2.3 📦 Modules](README.md)

# 2.3.2 Type

A type describes the properties a value of that type should have.
Each such property is a definition.
A definition is then either a method or a immutable variable.
Only classes can implement types.

Say I have a server, I could define the type as follows:
```
    type Server
    
    def name: String?

    def connect:      IPAddress -> Boolean
    def send_message: String -> Boolean
    def disconnect:   _ -> Boolean
```

Now any `stateless` or `stateful` that implements this type must have these definitions.
