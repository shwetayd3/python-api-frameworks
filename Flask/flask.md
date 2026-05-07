# Use Flask when:

You want a simple, flexible app with minimal setup.

## Example:

“For a small URL shortener or a simple internal API, I would choose Flask because it is lightweight and gives me full control over project structure.”

## Simple design:

```mermaid
flowchart TD
    A[Client] --> B[Flask Route];
    B --> C[Business Logic];
    C --> D[Database / File / External API];
```

## Example use cases:

* Small REST API
* Prototype
* Internal tool
* Simple webhook receiver
* Basic dashboard
