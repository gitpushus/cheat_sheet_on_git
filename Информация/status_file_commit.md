Варианты статусов:  untracked/tracked, staged и modified

```mermaid
graph TD;
    untracked -- "git add" --> staged;
    staged + tracked    -- "git commit"     --> tracked/comitted;
    %%tracked/comitted -- "change"   --> staged + tracked;
```
