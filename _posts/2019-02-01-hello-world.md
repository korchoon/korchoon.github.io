---
tags: [sample, demo]
title: Hello World Post
---

## Async statemachines are awesome


```csharp
public async Routine Shoot(int capacity, float cooldown)
{
    for (int i = 0; i < capacity; i++)
    {
        Bang();
        await cooldown;
    }
}
```
