Варианты статусов:  untracked/tracked, staged и modified

```mermaid
graph LR;
  untracked -- "git add" --> staged;
  staged + tracked    -- "git commit"     --> tracked/comitted;
  tracked/comitted -- "Изменения"   --> staged + tracked;
```

