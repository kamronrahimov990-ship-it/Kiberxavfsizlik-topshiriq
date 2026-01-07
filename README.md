# Kiberxavfsizlik-topshiriq
```mermaid
flowchart TD
    A[Start] --> B[public.pem faylni o‘qish]
    B --> C[Ochiq kalitni yuklash]
    C --> D[Message = "Kamron Rahimov"]
    D --> E[Foydalanuvchidan Base64 imzo kiritish]
    E --> F[Base64 imzoni decode qilish]
    F --> G[Imzoni verify qilish]
    G -->|To‘g‘ri| H[✔️ Imzo to‘g‘ri!]
    G -->|Xato| I[❌ Imzo noto‘g‘ri!]
    H --> J[End]
    I --> J[End]
```
