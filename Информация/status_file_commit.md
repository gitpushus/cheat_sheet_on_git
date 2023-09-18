Варианты статусов:  untracked/tracked, staged и modified

```mermaid
graph LR;
  untracked -- "git add" --> staged;
  staged    -- "git commit"     --> tracked/comitted;
  tracked/comitted -- "change" --> modified;
  modified --> "git add" --> staged;

``` 
